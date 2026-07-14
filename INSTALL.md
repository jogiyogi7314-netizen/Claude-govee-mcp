# Installation Guide

## Quick Start

### 1. Get Govee API Key
- Open Govee Home app
- Settings → Developer → Apply for API Key
- Wait for email confirmation (instant usually)

### 2. Deploy Server
Choose one:

#### Option A: Replit (Easiest)
- Go to replit.com
- Create Node.js project
- Add this repo
- Set GOVEE_API_KEY secret
- Click Run
- Copy public URL

#### Option B: Railway
- Go to railway.app
- Deploy from GitHub
- Add GOVEE_API_KEY variable
- Copy public URL

#### Option C: Local Testing
```bash
npm install
npm run build
export GOVEE_API_KEY=your_key
npm start
