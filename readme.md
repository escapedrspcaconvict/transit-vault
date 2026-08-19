# Travel Mate 🚌🔒

A highly secure, privacy-first Progressive Web App (PWA) for managing local transit routes and safely storing sensitive personal data. Travel Mate operates completely on-device with zero external backends, ensuring your data never leaves your phone.

> **⚠️ STRICTLY FOR PRIVATE USE ONLY**
> This application is built explicitly for personal, individual use. Distributing this application for public use utilizing the "Bring Your Own Key" (BYOK) architecture is a direct violation of the Terms of Service for both the Real Time Trains (RTT) and Transport for West Midlands (TfWM) APIs. Instructing end-users to mass-create developer accounts to fuel a third-party application is considered rate-limit circumvention and abuse of the open data portals. 

## Key Features
*   **Zero-Backend Architecture:** All data is kept strictly in local storage.
*   **Enterprise-Grade Security:** Data is protected via AES-256-GCM encryption.
*   **Multi-Tier Authentication:** Integrates native device biometrics (WebAuthn) and an unrecoverable 2FA passcode lock.
*   **Bring Your Own Key (BYOK):** Securely encrypts personal transit API keys directly on your device.

## Getting Your API Keys (For Personal Owner Use)
To enable live routing for your personal deployment, you must supply your own developer keys. 

**Real Time Trains (RTT)**
1. Go to `api.rtt.io` and click Sign Up.
2. Register for a free Personal/Non-Commercial account.
3. Log in and navigate to the developer dashboard to view your API credentials.

**Transport for West Midlands (TfWM)**
1. Go to `developer.tfwm.org.uk`.
2. Create a free developer account and log in.
3. Go to the API Products section and subscribe to the open data/GTFS feeds.
4. Navigate to your profile to reveal your API keys.

## License
Copyright (c) 2026. All Rights Reserved.

This source code is hosted publicly for transparency and personal deployment purposes only. Downloading, modifying, reproducing, or distributing this source code, or utilizing the hosted application for anything other than the original author's personal use, is strictly prohibited without explicit permission.
