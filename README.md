# 🎵 MusicApp

A modern music player web application built with React, featuring playback controls, search, playlists, and a liked songs library. Includes a curated collection of Bollywood and South Indian songs.

## Features

- 🎧 **Music Player** — Play, pause, and browse through a library of songs
- 🔍 **Search** — Find songs by name, artist, or category
- 📋 **Playlists** — Organize your music into playlists
- ❤️ **Liked Songs** — Save your favourite tracks
- 🎨 **Responsive UI** — Clean, modern interface with Tailwind CSS

## Tech Stack

- **React 19** with Vite
- **React Router** — Client-side routing (Home, Search, Playlist, Liked)
- **Redux Toolkit** — State management
- **Tailwind CSS** — Styling
- **React Icons** — Icon library

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later)

### Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/MusicApp.git
cd MusicApp

# Install dependencies
npm install

# Start the development server
npm run dev
```

The app will be available at `http://localhost:5173`.

### Build for Production

```bash
npm run build
npm run preview
```

## Project Structure

```
src/
├── assets/          # Images and MP3 audio files
├── components/      # Reusable UI components (Card, Nav, Player)
├── context/         # React context providers
├── pages/           # Route pages (Home, Search, Playlist, Liked)
├── redux/           # Redux store and slices
├── songs.js         # Song data (titles, artists, categories)
├── App.jsx          # Root component with routing
└── main.jsx         # Entry point
```

## License

This project is for educational purposes.
