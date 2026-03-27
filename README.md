# Mood Music Recommender

A web app that recommends music based on how you're feeling. Pick a mood and it shows you a playlist of songs that match, with a YouTube link for each one.

---

## What it does

- Pick from 8 moods: Happy, Sad, Focused, Chill, Energetic, Romantic, Nostalgic, Anxious
- Get a playlist of 6 songs for that mood
- Each song has a YouTube button that opens the song directly in YouTube
- Also shows a vibe description, hashtag tags, and a colour palette for each mood

---

## Technologies Used

- **HTML/CSS/JavaScript** — structure and styling
- **React** (loaded from CDN) — manages which mood is selected and re-renders the song list
- **Babel** (loaded from CDN) — lets me write JSX without needing a build step

---

## How to run it

1. Download or clone this repo
2. Open `index.html` in any browser

No npm, no install, no server needed.

---

## How to use it

1. Open the app in your browser
2. Click one of the mood buttons (e.g. "😌 Chill")
3. Your playlist appears straight away
4. Click **▶ YouTube** next to any song to open it on YouTube
5. Click a different mood to switch playlists

---

## AI Acknowledgment

- **Claude (claude.ai)** — helped plan the structure of the project and the data format for storing moods and songs. Also helped debug an issue where the display wasn't updating when a mood was clicked (the fix was using `setSelectedMoodId` correctly instead of mutating state directly). Reviewed the README.

- **GitHub Copilot** — autocomplete while writing CSS and JSX, mainly for syntax.

All code was written and tested by me. I understand how it works and can explain any part of it.

---

## Known issues / future improvements

- Playlists are hardcoded — ideally I'd connect to the Spotify API for real personalised recommendations
- No way to save or share a playlist
- Could add a shuffle button to randomise song order

---

## Author

BSc Computing Software Development, Year 2, Liew Jun Min
