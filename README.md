# 🧠 Neural Assist

A communication interface that allows users to express their needs through neural signals and Bluetooth connectivity. Designed for individuals with motor disabilities to communicate using brain signals.

## 📋 Overview

Neural Assist Interface processes real-time brain signals via Bluetooth to control a visual communication board. Users can navigate through communication cards using neural signals and select their needs with audio feedback.

## ✨ Features

- 🧠 **Neural Signal Control**: Navigate and select using brain signals
- 🃏 **Communication Cards**: Food, Help, Outing, Television, Lights, YouTube
- ➕ **Custom Cards**: Add personalized communication options
- 🌍 **Multi-language**: English, Bahasa Melayu, Tamil, Chinese
- 🔊 **Audio Feedback**: Instant sound responses
- 💡 **Smart Lighting**: Control connected light systems
- 📺 **YouTube Integration**: Access relaxation videos

## 🚀 Quick Start

1. **📦 Install dependencies**
   ```bash
   npm install
   ```

2. **🔑 Set up YouTube API** (optional)
   Create `.env.local`:
   ```env
   NEXT_PUBLIC_YT_API_KEY=your_youtube_api_key
   ```

3. **▶️ Run the app**
   ```bash
   npm run dev
   ```

4. **🔗 Connect neural device**
   - Click "Connect" button
   - Select "ESP32C6_EEG" from Bluetooth devices
   - Wait for connection confirmation

## 🎮 How to Use

### 🧠 Neural Navigation
- **👁️ S Mode**: Navigate through cards by blinking
- **🎯 A Mode**: focus to select the highlighted card

### ➕ Adding Custom Cards
1. Click "Add Communication Card"
2. Enter card name and choose icon
3. Card appears in the interface

### 🌍 Language Selection
Click the language dropdown in the header to change interface language.

## 📋 Requirements

- 📱 Bluetooth-enabled device
- 🧠 Neural signal device (ESP32C6_EEG)
- 🌐 Modern web browser with Web Bluetooth support

## 🛠️ Technology

Built with Next.js, React, TypeScript, and Tailwind CSS. Uses Web Bluetooth API for neural device communication.