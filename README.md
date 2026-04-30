# Simple Terraform Project

## 📌 Overview

This project demonstrates a basic setup using Terraform to provision AWS resources (e.g., an S3 static website).

---

## ⚙️ Prerequisites

Before getting started, ensure the following:

### 1. AWS CLI Configuration

Make sure you are authenticated with AWS:

```bash
aws configure
```

Provide:

* AWS Access Key ID
* AWS Secret Access Key
* Default region (e.g., `us-east-1`)
* Output format (e.g., `json`)

---

### 2. Verify Installed Versions

Check your Terraform version:

```bash
terraform version
```

Check AWS CLI:

```bash
aws --version
```

---

## 🧪 Tested Environment

This project has been tested with:

* Terraform: **v1.15.0** (darwin_arm64)
* AWS Provider: **hashicorp/aws v6.43.0**

---

## 🚀 Getting Started

Initialize Terraform:

```bash
terraform init
```

Preview changes:

```bash
terraform plan
```

Apply configuration:

```bash
terraform apply
```

---

## 📁 Notes

* Ensure your AWS credentials have sufficient permissions.
* Always review the execution plan before applying changes.
* Keep your Terraform and provider versions updated for compatibility.

---
