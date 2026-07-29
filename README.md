<p align="center">
  <img src="logo.jpg" width="120" alt="SafeLink logo" />
</p>

# SafeLink:

https://github.com/user-attachments/assets/51b1ef82-ed8f-4352-b2b5-10ff64caef22

A Safety wristband companion app built for Imperial College London's MEng Design Engineering programme.

Two paired users each wear an ESP32-C3 wristband. Pressing the wristband button sends a real-time alert to the paired user's phone with live GPS location.

- **COMFORT** — short press: gentle check-in, banner notification.
- **SOS** — long press: urgent alert, local notification, SMS to emergency contacts.

## Stack:

- Flutter / Dart — iOS.
- Firebase Auth + Firestore (real-time alerts).
- flutter_blue_plus (BLE scan + GATT).
- flutter_local_notifications (lock-screen alerts).
- flutter_map (OSM, no API key).

## App Source:

The Flutter app lives in [`safelink_flutter/`](./safelink_flutter), including full setup and deploy instructions in its own README.

## Team:

Built for the Human Centred Design Engineering Module (DESE40004) by a team of 5 students.
