# Micro-Adventure Tracker

The Micro-Adventure Tracker is a simple, offline-first web app designed to help you find and track small, local, and achievable adventures. It's for anyone looking to add a little more exploration, spontaneity, and fun into their routine without needing a lot of time, money, or gear.

This application is inspired by the "microadventure" concept popularized by Alastair Humphreys.

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/nextfiveinc/micro-adventures/blob/main/screenshots/Screenshot%20from%202025-08-12%2017-35-20.png" alt="Home screen" width="300">
      <br>
      <em>Keep clicking Suggest Adventures for fresh suggestions</em>
    </td>
    <td align="center">
      <img src="https://github.com/nextfiveinc/micro-adventures/blob/main/screenshots/Screenshot%20from%202025-08-12%2017-35-42.png" alt="Example suggestion" width="300">
      <br>
      <em>Click "Plan this" to bookmark a suggestion</em>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/nextfiveinc/micro-adventures/blob/main/screenshots/Screenshot%20from%202025-08-12%2017-35-57.png" alt="Selected adventures screen" width="300">
      <br>
      <em>View your planned and completed adventures</em>
    </td>
    <td align="center">
      <img src="https://github.com/nextfiveinc/micro-adventures/blob/main/screenshots/Screenshot%20from%202025-08-12%2017-37-08.png" alt="Browse all adventures by category" width="300">
      <br>
      <em>Browse all adventures by category</em>
    </td>
  </tr>
</table>


## What's a Micro-Adventure?

A micro-adventure is an adventure that is short, simple, local, and cheap—yet still exciting, refreshing, and rewarding. It's about changing your perspective and finding the wildness that exists on your own doorstep. Examples could be anything from exploring a new neighborhood to watching the sunrise from a local hill.

## Why Use This App?

*   **Overcome Inertia:** With a large, built-in library of ideas, the app's "Suggest" feature helps you break through decision paralysis and get out the door.
*   **Stay Aligned With Your Goals:** This app's unique feature is its ability to connect adventures to your personal goals (e.g., Health, Writing, Networking). The progress tracker shows you how your fun activities are contributing to your bigger ambitions.
*   **Completely Private & Offline:** Your list of planned and completed adventures is stored only on your local device. The app is a single HTML file that works perfectly without an internet connection.
*   **See Your Progress:** Watch your "Completed Adventures" list grow and see your goal counts tick up, providing a powerful sense of accomplishment and motivation.
*   **Free & Open:** No accounts, no ads, no distractions. Just a simple tool for a richer life.

## Features

*   **Suggestion Engine:** Get a random adventure suggestion from the built-in library.
*   **Browse and Filter:** Explore the full list of adventures and filter them by themes like "Nature & Outdoors," "Urban Exploration," or "Arts & Crafts."
*   **Personal Adventure Lists:** Keep track of the adventures you want to do ("Planned") and the ones you've already done ("Completed").
*   **Goal-Oriented Tracking:** Each adventure is tagged with life goals it can contribute to. The progress view gives you a summary of how many adventures you've completed for each goal.
*   **No Setup Required:** Just download the single `micro-adventure.html` file and open it in your browser to get started.

## How to Get Started

1.  **Download:** Save the `microadventure.html` file from this folder.
2.  **Open:** Open the file in any modern web browser (like Chrome, Firefox, or Safari).
3.  **Explore:** Use the "Suggest," "Browse," and "My Adventures" tabs to plan your next outing!

Your progress is automatically saved in the browser you use. To continue, just open the same file in the same browser.

## For Developers and Tinkerers

The beauty of this single-file app is how easy it is to customize. The entire list of adventures is contained in plain text within a `<script>` tag at the bottom of the `micro-adventure.html` file.

You can easily fork this project and:
*   Add, remove, or edit adventures.
*   Change the `GOAL_MAP` constant to reflect your own personal goals.
*   Tailor the entire adventure list to your city, hobbies, or interests.

The format is simple:
```
* Adventure description `[goal_code, another_code]`
```

## License

GNU General Public License v3.0 or later. See [COPYING](COPYING) for more details.
