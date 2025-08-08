# WhatsApp-Driven Google Drive Assistant (n8n)

## 🚀 Overview
This n8n workflow lets users perform Google Drive actions via WhatsApp using Twilio Sandbox.

## 🛠 Features
- LIST, DELETE, MOVE, SUMMARY commands
- Google Drive OAuth2 integration
- OpenAI GPT-4o for document summaries
- Logging & error handling
- Safe delete (with confirmation)

## 🎥 Demo Video

Watch the full demo here:  
👉 [Click to Watch Demo Video](https://www.loom.com/share/b38edda02b944c6ab1e6265a7fe3a08a)

## 🧾 Commands Format
- LIST /ProjectX
- DELETE /ProjectX/report.pdf
- MOVE /ProjectX/report.pdf /Archive
- SUMMARY /ProjectX

## 🧩 Setup Instructions

### 1. Twilio Sandbox Setup
1. Go to [Twilio Console](https://twilio.com/console)
2. Create Sandbox for WhatsApp
3. Get Account SID, Auth Token, From Number

### 2. Google OAuth2 Setup
1. Create project in [Google Cloud Console](https://console.cloud.google.com)
2. Enable Google Drive API
3. Get Client ID, Client Secret
4. Add scopes

### 3. Run n8n with Docker
```bash

docker-compose up -d
