# Kruba-Chat

## 🤖 KrubaChat

A modern Flutter-based AI chat application with conversation history, customizable settings, and a clean chat UI.
Built with Dart + Flutter and integrates with ChatGPT-style AI APIs.

## 📌 Overview

KrubaChat is a lightweight, cross-platform mobile application that allows users to chat with an AI using a simple, elegant interface.
It includes chat history storage, settings management, and smooth navigation across pages.

## 🚀 Features

**💬 Chat Features** :

  - Real-time AI conversation

  - Typing animation & smooth UI

  - Question input component

  - Automatic keyboard hiding

**🗂️ Chat History** :

  - Saves previous conversations

  - Load & view past chats

  - Persistent storage

**⚙️ App Settings** :

  - API Key configuration

  - Language/Model preferences (based on config)

  - Clean settings page UI

**📱 Flutter UI** :

  - Home page

  - Chat page

  - Chat history page

  - App Open / Splash page

**🔧 Utilities** :

  - Centralized API handler (Chatgpt.dart)

  - Global configuration (Config.dart)

  - State management via Stores (AIChatStore.dart)

## 🛠️ Tech Stack

**Core Technology** :

   - Flutter (Dart)

**Material Design UI** :

  - State Management: MobX / Simple stores

  - Cross-platform: Android & iOS

**Backend / API** :

   - ChatGPT-style API integration using custom request handler

   - JSON-based responses

## 📂 Project Structure

<img width="677" height="614" alt="image" src="https://github.com/user-attachments/assets/651fc77e-befc-4e4b-983b-0d7aff1d3f75" />

## ⚙️ Installation & Setup

1️⃣ Install Flutter

Make sure Flutter SDK is installed:

    https://flutter.dev/docs/get-started/install

Check version:

    flutter --version

2️⃣ Install Dependencies

Inside the project folder:

    flutter pub get

3️⃣ Configure Your API Key

Open:

    lib/utils/Config.dart


Set your API key:

    class Config {
       static const String apiKey = "YOUR_API_KEY_HERE";
    }

4️⃣ Run the App

For Android:

    flutter run


For iOS:

    flutter run


Or run directly from Android Studio / VS Code.

## 🧪 Building Release APK

   - flutter build apk

   - iOS (requires macOS):

   - flutter build ios

## 🌟 Future Improvements

   - Add streaming responses

   - Add image generation

   - Add theme customization

   - Add user profiles

   - Cloud sync of chat history

## 👨‍💻 Author

Udit Chowdary Jasti
