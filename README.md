# 500-Workout-Tracker
Tracker for BarStarz 500 Workout

This file clearly explains:

	•	What the app does
	•	How to use it
	•	How to install it to home screen
	•	How the rounds work
	•	App folder structure
	•	Future upgrade options

# 500 Workout Tracker (Web App)

This is a simple tap-to-track workout app based on the BarStarzz 500
workout structure.

## Purpose

The app helps you track your **10 workout rounds**, where each round
consists of performing: - 2×5 Squats - 2×5 Pull-Ups (or assisted) - 2×5
Push-Ups - 2×5 Dips - 2×5 Knee Raises / Leg Raises - 5--10 Minutes of
Jogging / Conditioning

Each round equals **10 reps per exercise**. After 10 rounds, you reach
**100 reps per exercise**.

## Features

-   **One-tap round completion**
-   **Auto time log** for each round
-   **Progress saved automatically**
-   Works **offline**
-   Can be **installed to Home Screen** and used like a native app

## How to Use

1.  Open `index.html` directly or host the files in a web server.
2.  On your phone, open the page in Safari (iPhone) or Chrome (Android).
3.  Add the app to home screen:
    -   **iPhone:** Share → Add to Home Screen
    -   **Android:** Menu → Add to Home Screen
4.  Tap **Complete Round** every time you finish a full round.
5.  When you're done or starting a new session, tap **Reset**.

## File Structure

    your-folder/
     ├ index.html
     ├ manifest.json
     ├ service-worker.js
     ├ icon_192.png
     └ icon_512.png

## App Behavior

-   Progress is stored locally on your device (no internet needed).
-   Closing the app does **not** reset your progress.
-   Reset removes all progress intentionally.

## Updating the App

If you make design or logic updates, you may need to: - Clear browser
cache OR - Remove and re-add the app to your home screen

## Future Enhancements (Optional)

-   Round timer
-   Rep tempo cues
-   Sound / vibration feedback
-   Weekly progress charts

Enjoy your training and stay consistent.
