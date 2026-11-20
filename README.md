# Community Event Calendar

A mobile-friendly web and mobile application built with FlutterFlow and Firebase Firestore that allows community members to browse dates, schedule upcoming events, and manage event listings in real time.

## Live Demo
- **Interactive App Preview (Run Mode):** [Open Community Event Calendar](https://app.flutterflow.io/run/f7jLATD1Q7DnO8RSApDn)
- **Portfolio Page:** [https://rosechelmaealmazan.github.io](https://rosechelmaealmazan.github.io)

## Features
- **Interactive Calendar View:** Select any date on the calendar to view or schedule events for that day.
- **Create Events:** Add new community events with a title, description, and selected date saved directly to Firebase Firestore.
- **Real-Time Event List:** Automatically syncs and displays stored events from the Firestore `events` collection.
- **Safe Event Deletion:** Delete events directly from the list with a confirmation dialog prompt to prevent accidental removal.

## How to Install and Run

### Option 1: Run Directly in Your Browser (No Installation Required)
1. Open the live demo link: [https://app.flutterflow.io/run/f7jLATD1Q7DnO8RSApDn](https://app.flutterflow.io/run/f7jLATD1Q7DnO8RSApDn)
2. Wait for the FlutterFlow web build to load, then click **Add Event** or select dates on the calendar to test the app.

### Option 2: Run Locally via Flutter SDK
1. Export or clone the Flutter project source code from FlutterFlow (`comm-cal-2026`).
2. Open a terminal inside the project folder and install dependencies:
   ```bash
   flutter pub get
   
