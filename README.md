
# Deploy a Simple Web App on Google Cloud Platform (GCP)

This tutorial walks through launching a basic Apache web server on a GCP Compute Engine instance. Perfect for testing, learning, or deploying small static websites.

---

## 🚀 Steps

### 1. Create a Google Cloud Account
Go to [https://cloud.google.com](https://cloud.google.com) and sign up. Google offers $300 in free credits for new users.

### 2. Create a VM Instance
- Go to Compute Engine > VM Instances
- Click "Create"
- Use `e2-micro` (free tier eligible)
- Choose Ubuntu/Debian
- Allow HTTP/HTTPS traffic

### 3. Connect via SSH & Install Apache

```bash
sudo apt update && sudo apt install apache2 -y
