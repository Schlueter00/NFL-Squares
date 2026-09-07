# 🏈 NFL Football Squares Board

A dynamic, web-based NFL Football Squares app for running game squares pools, tracking quarter-by-quarter scores, auto-evaluating winners, and sharing read-only boards. Built using vanilla HTML5, CSS3, and JavaScript with zero external dependencies.

---

## ✨ Features

* **🎨 Dynamic Team Branding**: Select any two of the 32 official NFL teams. The board layout, axis labels, headers, and score input boxes dynamically update with team primary colors and high-resolution logos.
* **🏈 Quarter-by-Quarter Score Tracking**: Enter scores for Q1, Q2, Q3, and Q4. Score input boxes adjust to match each team's primary team color.
* **⚡ Automatic Winner Evaluation**:
  * Automatically calculates last-digit grid intersections for each quarter.
  * Highlights winning squares directly on the grid (e.g., `Q1 Win`, `Q2 Win`).
  * Triggers a winner celebration popup modal when new scores are entered.
* **🛡️ Built-in Score Validation**: Ensures non-decreasing cumulative scores and alerts the host if an invalid score sequence is entered.
* **🔗 Read-Only URL Sharing**: Generate and share lightweight, base64-encoded links allowing participants to view live board states without accidentally modifying data.
* **🖨️ Print-Optimized Layout**: Includes CSS print styles designed to hide UI controls and expand the grid cleanly onto standard 8.5x11 portrait paper.
* **💾 Local Storage Persistence**: Automatically saves team choices, quarter scores, axis numbers, and claimed squares to your browser.

---

## 🚀 Quick Start & Installation

Because this project is built using native web technologies, no installation, server setup, or build process (`npm`, `node`, etc.) is required.

### Local Usage
1. Download or clone this repository:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git](https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git)
