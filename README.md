# AI Auto Video Downloader & Social Media Cross-Poster

An automated n8n workflow that downloads video files and seamlessly publishes them across TikTok, Instagram, and Facebook.

## 🚀 Features
- **Auto-Download:** Fetches videos from target sources instantly.
- **Cross-Posting:** Formats and publishes content to TikTok, Instagram, and Facebook simultaneously.
- **Secure Architecture:** Built using native n8n credential management to keep API keys hidden.

## 🛠️ Setup Instructions
1. **Prerequisites:** Ensure you have an active [n8n instance](https://n8n.io) (Cloud or Self-Hosted).
2. **Import Workflow:** Download the `workflow.json` file from this repository. Inside n8n, create a blank workflow, click the top-right menu, and select **Import from File**.
3. **Connect API Credentials:** You must configure your own API tokens/OAuth accounts for the following nodes:
   - TikTok Graph API / Content Posting API
   - Meta Graph API (Instagram Business & Facebook Pages)
4. **Activate:** Toggle the workflow status to **Active** to start running it automatically.
5.
