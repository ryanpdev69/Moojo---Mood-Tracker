# MooJo - Mood Tracker

A beautifully designed, offline-first Mood Journal app built with Flutter. MooJo allows users to track their emotional journey, log deeply reflective entries, and gain valuable insights through analytics — all wrapped in a premium, modern user interface.

## ✨ Features

- **Offline-First Architecture**: Journal entries are securely stored locally using SQFlite, ensuring the app works flawlessly without an internet connection.
- **Seamless Cloud Sync**: Syncs your data with Firebase Cloud Firestore in the background using a robust "Last Write Wins" strategy, so your data is safe across devices.
- **Modern & Premium UI**: A highly polished, sleek user interface with beautiful typography, subtle micro-animations, and calming gradients.
- **Guest Mode**: Users can skip registration and immediately start tracking their mood locally. Data is gracefully migrated to the cloud if they sign up later.
- **Rich Analytics**: Visualizes your weekly and monthly mood trends with interactive charts (powered by `fl_chart`), helping you spot emotional patterns.
- **Privacy & Security**: Built-in App Lock (PIN and Biometrics support via Fingerprint/FaceID) to keep your journal totally private.
- **Export Data**: Easily export your journal entries to a CSV file.
- **Comfort Bot**: Integrates an AI-driven comfort bot that provides thoughtful, empathetic responses (powered by Hugging Face Inference API).


