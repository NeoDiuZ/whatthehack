# 🧠 Neural Assist

*Empowering Singapore's elderly to reclaim their independence through thought-controlled technology*

## 💔 The Problem We're Solving

In Singapore, 500,000+ elderly citizens need daily assistance, and by 2026, our nation will be super-aged. We watched our grandparents lose control over the simplest aspects of their daily lives - waiting 20 minutes just to adjust their bed position, their eyes filled with frustration and hopelessness. No one should have to feel that way.

## ✨ What Neural Assist Does

Neural Assist is a neuro headband that translates brain signals into actions, allowing elderly users to control their environment using thought and blinks. No voice commands when your throat is dry. No buttons to fumble with arthritic hands. Just think, and it happens.

### 🏠 Environmental Control
- Control lights, air conditioning, TV, and smart home devices
- Focus on visual cues to activate commands
- Add new actions easily through the dashboard

### 🚨 Emergency Communication
- Double-blink activation for immediate caregiver alerts
- Real-time response with sub-second latency

### 🔗 Smart Integration
- Works with 600+ existing smart devices
- No need to buy special "compatible" equipment
- Your grandmother can control her existing TV

## 🚀 Why We Stand Out

### ⚡ **10-Second Setup vs 2+ Hours**
While competitors require extensive training and cost $25,000+, Neural Assist works in 10 seconds. An 82-year-old grandmother can control her room immediately.

### 🇸🇬 **Singapore-Built for Singapore's Elderly**
We're the only brain-computer interface designed specifically for Singapore's super-aged society. No 6-month shipping delays or foreign customer service. We understand HDB layouts and speak Singlish.

### 🔓 **Open Ecosystem vs Walled Gardens**
Unlike Neurostyle, Emotiv, and Tobii's proprietary systems, our open API integrates with existing devices. No vendor lock-in.

## 🛠️ How It Works

### 🧠 **EEG Signal Processing**
- Single forehead electrode detects both EOG (eye blinks) and EEG (brain focus signals)
- Modified ADS620 amplifier module for clean signal detection
- Custom Fast Fourier Transform algorithm for signal processing

### 🤖 **AI Classification**
- Machine learning algorithms distinguish intentional commands from background noise
- 6 different signal types detected: clean EEG, eye blinks, eye movement, muscle activity, pulse, and line noise

### 📡 **Hardware Integration**
- ESP32-C6 Board for processing and BLE transmission
- Haptic feedback for user confirmation
- Sub-second latency through BLE connectivity

## 🎮 How to Use

### 👁️ **Navigation (S Mode)**
- Blink to navigate through communication cards
- Visual highlighting shows current selection

### 🎯 **Selection (A Mode)**
- Focus on the highlighted card to activate it
- Instant audio feedback confirms your choice

### ➕ **Adding Custom Commands**
1. Click "Add Communication Card"
2. Enter command name and choose icon
3. New command appears in your dashboard

## 🚀 Quick Start

1. **📦 Install dependencies**
   ```bash
   npm install
   ```

2. **🔗 Connect neural device**
   - Click "Connect" button
   - Select "ESP32C6_EEG" from Bluetooth devices
   - Start controlling in 10 seconds!

3. **🎮 Begin using**
   - Blink to navigate
   - Focus to select
   - Control your environment with thought

## 📋 Requirements

- 📱 Bluetooth-enabled device
- 🧠 Neural Assist headband (ESP32C6_EEG)
- 🌐 Modern web browser with Web Bluetooth support

## 🏗️ Built With

- **Frontend**: Next.js, React, TypeScript, Tailwind CSS
- **Hardware**: ESP32-C6, ADS620 amplifier, 3D-printed housing
- **AI**: Python, Fast Fourier Transform, Machine Learning
- **Integration**: Web Bluetooth API, YouTube API, Smart Home APIs

## 🌟 What's Next

- **🤖 AI Enhancement**: Adaptive learning for personalized command recognition
- **🏥 Healthcare Partnerships**: Integration with local healthcare providers
- **📈 Scale Production**: Move from prototype to mass production
- **💰 Affordability**: Maintain accessibility for Singapore's elderly

---

*Built with love for Singapore's elderly community. Because dignity is priceless.*