# ClearSound

A macOS menu bar application that automatically manages your audio input devices to maintain optimal sound quality when using AirPods or other Bluetooth headphones.

## 🎧 The Problem

When using AirPods' microphone on a Mac, the sound quality significantly degrades. This is a known limitation that can't be fixed at the system level. The best solution is to avoid using the AirPods' microphone entirely to preserve audio quality.

This issue also affects other Bluetooth devices with built-in microphones, such as:
- **AirPods Pro/Max** - Similar quality degradation when using built-in mic
- **Beats headphones** - Wireless Beats with microphone functionality
- **Sony/Bose headphones** - Premium wireless headphones with mics
- **Other Bluetooth earbuds** - Various brands with microphone capabilities

## 💡 The Solution

ClearSound automatically detects when your input device changes and switches it back to your preferred audio input device, ensuring you always get the best possible sound quality from your AirPods and other Bluetooth headphones.

## ✨ Features

- **Real-time Detection**: Instantly responds to audio device changes (no more polling delays)
- **Smart Device Management**: Remembers your preferred devices and automatically switches back
- **Menu Bar Interface**: Clean, accessible interface that stays out of your way
- **Onboarding System**: Easy setup for new users
- **Multi-language Support**: Available in multiple languages
- **Persistent Preferences**: Your settings are remembered between app restarts
- **Background Operation**: Runs silently in the background, hidden from dock

## 🔧 How It Works

The application monitors your system's audio input devices in real-time. When it detects that your input device has changed (e.g., when you answer a call and your AirPods switch to microphone mode), it automatically switches back to your specified preferred input device, maintaining the best possible audio quality.

## 📱 System Requirements

- macOS 10.15 (Catalina) or later
- Compatible with all Bluetooth audio devices
- No additional dependencies required
