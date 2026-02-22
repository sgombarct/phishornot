# 🎣 Phish or Legit? — Real-Time Inbox Simulator

Interactive cybersecurity awareness training game. Users analyze realistic emails, Slack messages, SMS, calendar invites, and AI-generated requests to identify phishing attacks.

**Built by [Nwaj Tech](https://nwajtech.com)** — We Speak Human. We Secure Tech.

## Features

- **3 Game Modes**: Standard, Advanced, Full Simulation
- **14 Realistic Scenarios**: Emails, Slack, SMS, calendar invites, push notifications, voicemail transcripts
- **Advanced Threats**: MFA fatigue, OAuth consent phishing, vendor invoice fraud, deepfake voice attacks, supply chain attacks
- **Detailed Metrics**: Accuracy, response time, weak spot identification, per-category breakdown

## Deploy to Netlify

### Option A: One-Click (Easiest)

1. Push this folder to a GitHub repo
2. Go to [app.netlify.com](https://app.netlify.com)
3. Click **"Add new site" → "Import an existing project"**
4. Connect your GitHub repo
5. Netlify auto-detects the `netlify.toml` config — just click **Deploy**
6. Your site is live at `https://your-site-name.netlify.app`

### Option B: Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# From this project folder:
npm install
npm run build
netlify deploy --prod --dir=dist
```

### Option C: Drag & Drop

```bash
npm install
npm run build
```
Then drag the `dist/` folder onto [app.netlify.com/drop](https://app.netlify.com/drop)

## Custom Domain

1. In Netlify dashboard → **Domain management → Add custom domain**
2. Add a CNAME record in your DNS:
   - **Name**: `training` (or whatever subdomain)
   - **Value**: `your-site-name.netlify.app`
3. Netlify auto-provisions SSL

Example: `training.nwajtech.com`

## Local Development

```bash
npm install
npm run dev
```

Opens at `http://localhost:5173`
