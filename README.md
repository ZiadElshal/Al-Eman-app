# 🌙 Al-Eman App | تطبيق الإيمان

<div align="center">
  <br/>
  <p><strong>A Comprehensive, Elegant, and Smart Islamic Companion App Built with Flutter.</strong></p>

[![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev)
[![BLoC](https://img.shields.io/badge/State_Management-BLoC_/_Cubit-blue?style=for-the-badge)](https://bloclibrary.dev/)
</div>

---

## 📖 About The App

**Al-Eman** is a feature-rich Islamic application designed to provide Muslims with essential daily tools in a highly optimized, beautifully animated, and user-friendly interface.

Focusing on **Performance (60 FPS)** and **Clean Architecture**, the app leverages modern Flutter capabilities to deliver precise prayer times, Qibla direction, Quranic texts, Audio playback, and much more, ensuring a seamless and spiritually enriching user experience.

## ✨ Key Features

* 🕌 **Smart Prayer Times & Athan:** * Real-time precise prayer calculations based on dynamic Geolocation.
    * **Smart Caching Mechanism:** Zero-loading time upon app startup; location is synced in the background.
    * Customizable local notifications and Athan audio alerts.
* 🕋 **Qibla Compass:** * Hardware-accelerated magnetometer integration for high accuracy.
    * Smooth, decoupled needle animation with an elegant *Islamic Pattern Skeleton Loading* state.
* 📖 **The Holy Quran:** Read and listen to the Quran with high-quality audio streaming.
* 📿 **Electronic Sebha:** A smart tally counter with haptic feedback and beautiful UI.
* 🤲 **Azkar & Supplications:** Morning, evening, and daily Azkar categorized elegantly.
* 📻 **Islamic Radio:** Live streaming of Quranic radio stations.
* 📜 **Hadith Collection:** Authentic sayings of Prophet Muhammad (PBUH).
* 📅 **Hijri Calendar:** Integrated Islamic date tracking.
* 💡 **Daily Spiritual Hints:** An auto-refreshing, state-optimized dynamic banner providing daily Islamic quotes.

## 🛠️ Tech Stack & Packages Used

The application is built using a robust set of modern Flutter packages and architectural patterns:

* **Framework:** Flutter & Dart
* **Architecture:** Feature-First / Clean Architecture
* **State Management:** * `flutter_bloc` (Cubit for scalable and reactive UI).
* **Location & Qibla Services:** * `geolocator` (for precise GPS tracking).
    * `geocoding` (to determine country/city for prayer calculation methods).
    * `flutter_qiblah` (for compass and Qibla direction).
* **Local Storage & Caching:** * `shared_preferences` (for caching location data and user settings).
* **Animations & UI:** * `animate_do` (for elegant entry animations).
    * Built-in Explicit Animations (`TickerProviderStateMixin`, `AnimationController`).
* **Background & Notifications:** * `flutter_local_notifications` (for offline, scheduled Athan and daily alerts).
* **Date & Time formatting:** * `intl` (for precise time formatting).
    * `hijri` / `hijri_calendar` (for Islamic dates).

## 🚀 Performance Optimizations

To ensure a buttery-smooth 60 FPS experience, the following techniques were heavily integrated into the app's core design:

* **RepaintBoundaries:** Strategically employed to isolate heavy UI components (such as blurred cards and gradients) from the scrollable lists, preventing unnecessary repaints during user interaction.
* **ValueNotifiers:** Leveraged for dynamic, auto-refreshing UI elements (like the spiritual hints banner) to ensure targeted, single-widget updates without rebuilding the entire screen.
* **Custom Painters:** Crafted complex geometric backgrounds (like the Octagram Islamic Pattern) mathematically using `CustomPainter`. This ensures a zero-memory footprint and razor-sharp infinite scalability, avoiding the overhead of heavy image assets.


## 📸 App Screenshots

### 🏠 Main Experience & UI
| Splash | Home View | Main Menu | Custom UI | About |
|:---:|:---:|:---:|:---:|:---:|
| <img src="screenshots/splash_screen.jpeg" width="180"> | <img src="screenshots/main_screen.jpeg" width="180"> | <img src="screenshots/main2_screen.jpeg" width="180"> | <img src="screenshots/main3_screen.jpeg" width="180"> | <img src="screenshots/about_screen.jpeg" width="180"> |

### 🕌 Prayer, Athan & Qibla
| Prayer Times | Qibla Compass | Azan Player | Prayer Cards | Cards Detail |
|:---:|:---:|:---:|:---:|:---:|
| <img src="screenshots/prayertime_screen.jpeg" width="180"> | <img src="screenshots/qibla_screen.jpeg" width="180"> | <img src="screenshots/azanplayer_screen.jpeg" width="180"> | <img src="screenshots/parayercards-screen.jpeg" width="180"> | <img src="screenshots/parayercards2-screen.jpeg" width="180"> |

### 📖 Quran & Audio Player
| Surah List | Full Surah | Audio Player | Radio | Readers |
|:---:|:---:|:---:|:---:|:---:|
| <img src="screenshots/allsurah-screen.jpeg" width="180"> | <img src="screenshots/surahfulldetails_screen.jpeg" width="180"> | <img src="screenshots/quiyamplayer_screen.jpeg" width="180"> | <img src="screenshots/radio_screen.jpeg" width="180"> | <img src="screenshots/alreaders_screen.jpeg" width="180"> |

### 🤲 Azkar, Hadith & Sebha
| Azkar Category | Al-Azkar | Hadith | Ahadith | Electronic Sebha |
|:---:|:---:|:---:|:---:|:---:|
| <img src="screenshots/alzkr_screen.jpeg" width="180"> | <img src="screenshots/alazkar_screen.jpeg" width="180"> | <img src="screenshots/hadith_screen.jpeg" width="180"> | <img src="screenshots/ahadith_screen.jpeg" width="180"> | <img src="screenshots/sebha_screen.jpeg" width="180"> |

### ⚙️ Daily Tools & Settings
| Hijri Calendar | Spiritual Hints | Settings | Al-Khatima | El-Roqya |
|:---:|:---:|:---:|:---:|:---:|
| <img src="screenshots/calendar_screen.jpeg" width="180"> | <img src="screenshots/hints_screen.jpeg" width="180"> | <img src="screenshots/setting_screen.jpeg" width="180"> | <img src="screenshots/alkhatima_screen.jpeg" width="180"> | <img src="screenshots/elroqya_screen.jpeg" width="180"> |

---
<p align="center">Built with using Flutter</p>
