# AWS CLI Installation & Configuration Lab

This repository documents the process of installing, configuring, and utilizing the AWS Command Line Interface (CLI) on a Red Hat Enterprise Linux (RHEL) environment to manage IAM resources.

## Objectives
* Install the AWS CLI v2 on a Linux-based EC2 instance.
* Configure the CLI with secure IAM credentials.
* Interact with AWS Identity and Access Management (IAM) via the terminal.
* Retrieve and document specific IAM policies using CLI commands.

## Technical Stack
* **Cloud Provider:** Amazon Web Services (AWS)
* **Operating System:** Red Hat Enterprise Linux (RHEL)
* **Tooling:** AWS CLI v2, SSH (PuTTY/Terminal)

## Lab Steps

### 1. Installation
The AWS CLI was installed by downloading the x86_64 installation package and executing the install script:
```bash
curl "[https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip](https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip)" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install
