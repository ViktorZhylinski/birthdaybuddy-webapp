# 📱 Birthday Buddy - Telegram Web App

This folder contains the Telegram Mini App for importing birthdays.

## 🚀 Quick Deploy to Vercel

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Deploy:
```bash
cd webapp-repo
vercel --prod
```

3. Copy the URL (e.g., `https://birthday-buddy-xxx.vercel.app/telegram-import.html`)

4. Use that URL when setting up Telegram bot!

## 🤖 Or Deploy to GitHub Pages

1. Push this folder to GitHub
2. Enable GitHub Pages in repo settings
3. Use the GitHub Pages URL

## 📝 File Structure

- `telegram-import.html` - Main Web App (HTML/CSS/JS all-in-one)
- `README.md` - This file

## 🎨 Design

Uses Purple-Grape design system matching iOS app:
- Background: gradient from midnight to plum
- Colors: matching DesignSystem.Colors
- Typography: SF Pro Display
- Animations: smooth easeInOut

## 🔒 Privacy

- All processing happens in browser (client-side JavaScript)
- No data sent to any server (except iOS app via URL scheme)
- No analytics, no tracking

