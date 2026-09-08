# NFL Football Squares Web Application

A real-time, interactive NFL Football Squares board featuring live synchronization via Firebase, automated score tracking, pool financial management, and a dedicated quarter winner scoreboard.

## Features

* **Real-Time Collaboration:** Share a live board link so participants can view real-time updates and square selections as they happen.
* **Team Selection:** Choose Home (Top Axis) and Away (Left Axis) teams from a full list of NFL franchises, complete with official team colors and logos.
* **Randomized Axis Numbers:** Automatically shuffle and generate the 0–9 grid numbers for both axes.
* **Pool Financials & Cost Tracking:** 
  * Set a custom cost per square (e.g., $1, $5, $10).
  * Automatically counts claimed squares to calculate the **Total Pot**.
  * Dynamically splits the pot evenly across Q1 through Q4 to show the exact **Payout per Quarter**.
* **Quarter Winner Scoreboard:** A dedicated summary dashboard displaying Q1, Q2 (Half), Q3, and Q4 (Final) scores, winning square owners, and calculated cash payouts at a glance.
* **Automated Winner Detection & Popups:** Automatically maps final or quarter scores to the corresponding grid coordinates, highlights winning squares on the board, and triggers celebration alerts when a winner is decided.
* **Print-Friendly Layout:** Formats cleanly for physical printing when needed.

## Setup & Configuration

1. Make sure you have your Firebase project configured within the script tags of `index.html` (the app utilizes Firebase Realtime Database).
2. Open `index.html` in any modern web browser or host it via a static file server (such as GitHub Pages or Netlify).
3. Click **"Share Live Link"** to distribute the board to participants.

## How to Play

1. **Claim Squares:** Click on any square on the grid to assign a participant's name (Host view only).
2. **Set Pricing:** Input the desired dollar amount into the **Cost Per Square** field under Pool Financials.
3. **Generate Numbers:** Click **"Generate Axis Numbers"** once all squares are filled to randomly assign the 0–9 digits to the top and left axes.
4. **Enter Scores:** As the game progresses, type the quarterly scores for both teams. The scoreboard and payouts will update automatically!
