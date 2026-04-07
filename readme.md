# Music Playlist Explorer

A dynamic web app for browsing, searching, and interacting with curated music playlists. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies.

![Music Playlist Explorer](assets/img/playlist.png)

## Features

- **Browse Playlists** — Horizontally scrollable playlist cards with cover art, creator info, and like counts
- **Playlist Details** — Click any playlist to open a modal with the full song list, album art, and durations
- **Like Playlists** — Toggle likes with animated heart icons
- **Shuffle Songs** — Randomize the track order within any playlist
- **Search** — Filter playlists in real time by name or creator
- **Featured Page** — A dedicated page spotlighting a random playlist alongside other recommendations

## Demo

<div>
    <a href="https://www.loom.com/share/57bb4157134f4a17bfd2db43e63e0c95">
      <p>Watch the walkthrough</p>
    </a>
    <a href="https://www.loom.com/share/57bb4157134f4a17bfd2db43e63e0c95">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/57bb4157134f4a17bfd2db43e63e0c95-with-play.gif">
    </a>
</div>

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/marcebd/music-playlist-explorer.git
   ```
2. Open `index.html` in your browser — no build step required.

## Project Structure

```
├── index.html        # Home page — playlist grid and search
├── featured.html     # Featured playlist spotlight page
├── style.css         # All styles
├── script.js         # Home page logic (cards, modal, search, shuffle)
├── featured.js       # Featured page logic
├── data/
│   └── data.js       # Playlist and song dataset
└── assets/
    └── img/          # Icons and static images
```

## Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Flexbox layout, transitions, responsive design
- **JavaScript (ES6)** — DOM manipulation, event handling, array methods
- **Font Awesome** — Icon library for like buttons

## Author

**Marcela Billingslea**
