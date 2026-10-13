Spotify-Inspired Music Player
A browser-based music player built with HTML, CSS, and vanilla JavaScript. It features a selectable song list, playback controls, album artwork, and a seekable progress bar. The project is deployed as a static website on Render.
<p align="center">
  <a href="https://spotify-music-player-hh8a.onrender.com/">
    <strong>▶ Open the Live Music Player</strong>
  </a>
  &nbsp; · &nbsp;
  <a href="https://github.com/nitinkanasnale93/spotify-project">
    View Source Code
  </a>
</p>
<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-markup-orange?logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-styling-1572B6?logo=css3&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?logo=javascript&logoColor=222222">
  <img alt="Deployment" src="https://img.shields.io/badge/Deployed-Render-46E3B7?logo=render&logoColor=222222">
</p>
Overview
This project recreates the core experience of a simple music player in the browser. The interface and playback behavior are implemented using standard web technologies, with the browser's HTML Audio API handling audio playback.
Features
Play and pause the currently selected track.
Choose a song from the playlist.
Skip forward and backward through the playlist, including wrapping around at either end.
Seek through a track by clicking or dragging the progress slider.
Live playback progress updated as the song plays.
Track titles and album artwork displayed in the playlist and player interface.
Playback-state indicators for the main player and playlist.
Live Demo
Try it here: https://spotify-music-player-hh8a.onrender.com/
The site is hosted on Render as a static website.
Tech Stack
Technology	Purpose
HTML5	Page structure and audio-player controls
CSS3	Layout and visual styling
Vanilla JavaScript	Playlist interactions, playback controls, and progress updates
HTML Audio API	Playing audio and changing the current playback time
Font Awesome	Player-control icons
Git & GitHub	Version control and source-code hosting
Render	Static-site deployment
Run Locally
1. Clone the repository
```bash
git clone https://github.com/nitinkanasnale93/spotify-project.git
cd spotify-project
```
2. Start the website
No build command or package installation is required for this static project.
Recommended: open the folder in VS Code and launch `index.html` with the Live Server extension.
Alternatively, open `index.html` directly in a browser.
Keep the HTML file, JavaScript, stylesheet, audio files, and image assets in their expected relative locations so the playlist can load correctly.
Project Structure
```text
spotify-project/
├── index.html       # Music-player interface
├── style.css        # Layout and styling
├── script.js        # Playlist and playback logic
├── logo.png         # Project logo asset
├── bg.jpg           # Background image
├── playing.gif      # Playback animation
├── 1.jpg ... 10.jpg # Track artwork
└── 1.mp3 ... 10.mp3 # Audio tracks
```
What I Practised
Selecting and updating DOM elements with JavaScript.
Handling click and input events.
Managing playback with `Audio.play()`, `Audio.pause()`, `currentTime`, and `duration`.
Synchronising the progress slider with playback time.
Updating track names, artwork, and play/pause indicators when the selected song changes.
Publishing a static frontend project and maintaining its source on GitHub.
Future Improvements
Show each track's actual duration and the current playback timestamp.
Improve keyboard accessibility and use semantic buttons for playback controls.
Refine responsive behavior and test on different screen sizes and mobile browsers.
Add search, shuffle, repeat, and saved favourites.
Audio & Attribution
This is an independent learning project inspired by music-player interfaces. It is not affiliated with or endorsed by Spotify. Spotify is a trademark of its respective owner.
Before sharing or hosting audio files publicly, make sure you have permission or an appropriate licence for each track. Replace any tracks you do not have rights to distribute with properly licensed or royalty-free audio.
---
Built as a frontend learning project using HTML, CSS, and JavaScript.
