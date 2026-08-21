# Enterprise IT Ops Admin Portal

A high-end, production-ready Android application for IT Operations and Infrastructure management. Built with Jetpack Compose, Material 3 (Material You), and a Headless NoSQL-style Google Apps Script backend.

## 🚀 Features
- **Dynamic Theming**: Full Material You support with adaptive colorful gradients.
- **Enterprise Management**: Unified interface for Corporate Users, IT Staff, and Company Entities.
- **ITSM Incident Queue**: Advanced triage system with Gemini AI diagnostics.
- **Infrastructure Monitoring**: Real-time network speed diagnostics and server node health.
- **Secure Persistence**: Persistent sessions powered by Jetpack DataStore.
- **Universal Backend**: Flexible Google Apps Script engine (V6.2+) with auto-header generation.

## 🛠️ Tech Stack
- **UI**: Jetpack Compose (Material 3)
- **Networking**: Retrofit 2 + OkHttp 4
- **State Management**: Kotlin Flow + ViewModel (MVI-ish Architecture)
- **Database**: Google Sheets via Apps Script (Headless Engine)
- **Security**: Jetpack DataStore (Session Management)

## 📥 Import to Google AI Studio
1. Clone this repository.
2. Ensure you have the `google-services.json` (if using Firebase features).
3. Open the project in Android Studio.
4. Set up your Google Apps Script using the provided revamp script in the documentation.
5. Deploy the script as a Web App and paste the URL into `ApiClient.kt` or the in-app Settings.

## 📄 License
Enterprise License - Confidential Internal Use Only.
