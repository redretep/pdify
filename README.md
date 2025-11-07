# 🎵 Custom Music Player

A modern, responsive web music player with **Spotify‑inspired UI**.  
Features include dark/light mode, smooth animations, drag‑and‑drop playlist management, and custom controls for playback, volume, auto‑play, and repeat.

---

## ✨ Features

- **Spotify‑like playlist styling**: sleek dark theme, hover highlights, green accents.
- **Dark/Light mode toggle** with smooth transitions.
- **Drag & Drop playlist management** with ghost previews and reorder indicators.
- **Custom controls**: play/pause, next/previous, repeat, auto‑play toggle.
- **Progress bar & time display** with draggable seek.
- **Volume control** with custom slider and thumb.
- **Album art display** with rotation animation while playing.
- **Responsive design**: adapts to mobile, tablet, and desktop.
- **Floating settings menu** with animated toggle button.

---

## 🚀 Getting Started

1. fork the repository.
2. Deploy on Github Pages in your browser.
3. Add your songs to the playlist via the UI or script.
4. Enjoy your custom player!

---

## Screenshots
![Alt text](resource/image/1.png)
![Alt text](resource/image/2.png)
![Alt text](resource/image/3.png)
![Alt text](resource/image/4.png)
![Alt text](resource/image/5.png)

## 🚀 Setup Instructions

### YouTube Search Functionality (GitHub Secrets Method - Recommended)

For secure API key management, this project uses GitHub Secrets:

1. **Get a YouTube Data API Key**:
   - Go to the [Google Cloud Console](https://console.cloud.google.com/)
   - Create a new project or select an existing one
   - Enable the **YouTube Data API v3**
   - Create credentials (API key)
   - Restrict the API key to YouTube Data API v3 for security

2. **Add Your API Key to GitHub Secrets**:
   - Go to your repository on GitHub
   - Click on **Settings** → **Secrets and variables** → **Actions**
   - Click **New repository secret**
   - Name: `YOUTUBE_API_KEY`
   - Value: Your actual YouTube Data API key
   - Click **Add secret**

3. **Deploy**:
   - The GitHub Actions workflow will automatically inject your API key during deployment
   - Push any changes to the `main` branch to trigger a new deployment
   - Your API key remains secure and is never exposed in your code
