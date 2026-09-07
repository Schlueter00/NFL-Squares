# NFL Football Squares Board

A responsive, web-based NFL Football Squares application hosted on GitHub Pages and powered by Firebase Realtime Database for live, real-time syncing between a host and viewers.

## Features

* **Dynamic Board Generation:** Create custom football squares grids for any matchup.
* **Live Sharing:** Instantly generate a shareable link (`?board=...`) that updates automatically for viewers whenever the host makes changes.
* **Real-Time Syncing:** Uses Firebase Realtime Database listeners so changes propagate instantly across all connected browsers.
* **Print & Export Friendly:** Includes a clean print layout option to take your board offline.

---

## Setup & Configuration

### 1. Firebase Backend
1. Create a project in the [Firebase Console](https://console.firebase.google.com/).
2. Provision a **Realtime Database** under the **Build** menu.
3. Set your database rules to allow public read/write access so shared links can fetch and sync board data without requiring user authentication:
   ```json
   {
     "rules": {
       ".read": true,
       ".write": true
     }
   }
