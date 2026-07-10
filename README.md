# Spotify — Web Player Clone

A responsive recreation of Spotify's web player interface, built from scratch using pure HTML and CSS — no frameworks, no JavaScript, no libraries beyond Google Fonts and Font Awesome icons.

> **Disclaimer:** This is a non-functional student project built purely for learning frontend web development. It is **not affiliated with, endorsed by, or connected to Spotify AB** in any way. No audio playback, streaming, or account functionality is implemented — all player controls are static UI elements for demonstration only. "Spotify" is a registered trademark of Spotify AB.

---

##  Features

- Sidebar navigation with Home, Search, and Your Library sections
- "Create Playlist" and "Browse Podcasts" promo cards
- Sticky top navigation bar with playback and install-app shortcuts
- Scrollable content sections — Recently Played, Trending Now, Featured Charts
- Custom-styled album/track cards with hover-ready layout
- Fixed bottom music player with album info, playback controls, and progress bar
- Custom-styled range sliders for progress and volume
- **Fully responsive** — sidebar collapses into a compact top bar and the player simplifies on mobile
- Google Fonts — Montserrat
- Font Awesome 7 icons throughout

## Built With

- HTML5
- CSS3 (Flexbox, media queries)
- Font Awesome 7
- Google Fonts
- Deployed on [Vercel](https://vercel.com/)

## Project Structure

```
spotify-clone/
├── index.html
├── style.css
└── assets/
    ├── library_icon.png
    ├── backward_icon.png
    ├── forward_icon.png
    ├── album.jpg
    ├── player_icon1-5.png
    └── card1-6img.jpeg
```

##  How to Run Locally

No installation or build step needed.

1. Clone the repo
   ```bash
   git clone https://github.com/singhriya78/Spotify-Clone.git
   ```
2. Open `index.html` directly in your browser — that's it.

##  Responsive Design

The layout adapts across two breakpoints (mobile ≤768px and small mobile ≤420px):
- The sidebar collapses into a slim horizontal top bar, and the playlist/podcast promo boxes are hidden to save space
- Content switches from a fixed layout to normal page scroll
- The bottom music player simplifies to show only album info and playback controls — the progress bar and secondary controls (volume, queue, devices) are hidden, similar to Spotify's own mobile player

## What I Learned

- Building multi-panel app layouts with Flexbox (sidebar + main content + fixed player)
- Styling native `<input type="range">` sliders with custom thumbs and tracks
- Managing `position: sticky` and `position: fixed` together in a scrollable layout
- Progressive simplification for mobile — deciding what to hide vs. restructure rather than just shrinking everything
- Git/GitHub workflow for version control and deployment
- Deploying and troubleshooting a live site on Vercel

## Author

Made with effort and curiosity by **Riya Raj**
Learning web development, one clone at a time.

## License

This project is for educational purposes only and is not intended for commercial use.