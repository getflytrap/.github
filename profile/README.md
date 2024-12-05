![Organization Logo](https://raw.githubusercontent.com/getflytrap/.github/main/profile/flytrap_logo.png)

# Flytrap: Lightweight Error Monitoring for Development Teams
Welcome to Flytrap, the lightweight, self-hosted error monitoring tool built for small to mid-sized development teams. Flytrap is designed to help you focus on what matters most: identifying, diagnosing, and resolving errors quickly and efficiently. By offering a streamlined alternative to traditional error monitoring tools, Flytrap eliminates the bloat of broader observability platforms, prioritizing simplicity, usability, and full data ownership.

## 🚀 What Is Flytrap?
Flytrap is a developer-first tool that:

- Captures frontend and backend errors across frameworks and languages.
- Provides near real-time notifications via email and in-dashboard pop-ups.
- Ensures privacy and compliance by keeping your error data within your infrastructure.
- Is fully provisioned through Terraform on your own AWS account.

With Flytrap, you own your data and control your infrastructure, giving you peace of mind while simplifying error tracking and resolution.

## 🧩 Why Choose Flytrap?
### 1. Focused Functionality
Unlike bloated platforms, Flytrap focuses exclusively on error monitoring. This targeted approach reduces distractions, helping you quickly address issues without navigating unnecessary features.

### 2. Minimal Overhead
Flytrap’s lightweight SDKs capture only the data you need for debugging, ensuring no performance trade-offs for your applications.

### 3. Full Data Ownership
Flytrap’s self-hosted architecture ensures your error data never leaves your infrastructure, aligning with privacy and compliance requirements while eliminating vendor lock-in.

### 4. Streamlined Deployment
Provision Flytrap in your AWS account using Terraform, with setup designed to be quick, reliable, and developer-friendly.

## 🛠️ Key Features
- **SDKs for Diverse Frameworks:** Flytrap supports React, Vanilla JavaScript, Express, and Flask, offering seamless integration with your tech stack.
- **Near Real-Time Alerts:** Stay updated on errors via WebSocket dashboard pop-ups and email notifications through Amazon SNS.
- **Context-Rich Error Reports:** Detailed error logs include stack traces, session metadata, and more for efficient debugging.
- **Source Map Support:** Resolve errors in minified JavaScript by securely uploading source maps to your AWS S3 bucket.

## 📂 How to Get Started
1. **Provision Your Infrastructure:** Deploy Flytrap in your AWS account using our Terraform script.
2. **Integrate the SDK:** Add Flytrap’s SDK to your applications to begin capturing errors.
3. **Monitor and Resolve:** Use the Flytrap dashboard to track, prioritize, and fix errors with ease.

For detailed setup instructions, visit our documentation (link to how to use page?).