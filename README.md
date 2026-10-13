Spotify-Inspired Music Player
A browser-based music player built with HTML, CSS, and vanilla JavaScript. It includes a selectable playlist, playback controls, album artwork, and a seekable progress bar.
<p align="center">
  <a href="https://spotify-music-player-hh8a.onrender.com/"><strong>▶ Open the Live Music Player</strong></a>
  &nbsp; · &nbsp;
  <a href="https://github.com/nitinkanasnale93/spotify-project">View Source Code</a>
</p>

Features
- Play and pause the selected song.
- Choose a track from the playlist.
- Skip to the next or previous track.
- Click or drag the progress slider to seek through a song.
- Display track titles and album artwork.
- Show playback indicators in the player interface.
Tech Stack
- HTML5 — page structure and audio player interface
- CSS3 — layout and styling
- JavaScript — playlist interaction, playback controls, and progress updates
- HTML Audio API — browser-based audio playback and seeking
- Font Awesome — player-control icons
- Git and GitHub — version control and source-code hosting
- Render — static-site deployment
Live Demo
Try it here: https://spotify-music-player-hh8a.onrender.com/
Run Locally
1. Clone the repository:
   git clone https://github.com/nitinkanasnale93/spotify-project.git
2. Open the project folder:
   cd spotify-project
3. Open index.html in your browser, or use the Live Server extension in VS Code.
No build command or package installation is required for this static project. Keep the HTML file, JavaScript, stylesheet, audio files, and image assets in their expected relative locations so the playlist can load correctly.
Project Structure
spotify-project/
├── index.html       # Music-player interface
├── style.css        # Layout and styling
├── script.js        # Playlist and playback logic
├── logo.png         # Project logo
├── bg.jpg           # Background image
├── playing.gif      # Playback animation
├── 1.jpg ... 10.jpg # Track artwork
└── 1.mp3 ... 10.mp3 # Audio tracks
What I Practised
- Selecting and updating DOM elements with JavaScript
- Handling click and input events
- Controlling audio playback with HTMLAudioElement
- Updating playback progress using currentTime and duration
- Connecting a static website to GitHub and deploying it on Render
Future Improvements
- Improve keyboard and screen-reader accessibility.
- Test and refine the layout on more mobile screen sizes.
- Add track duration and elapsed-time labels.
- Add clearer loading and playback-error states.
Note
This is a learning project inspired by music-player interfaces. It is not affiliated with or endorsed by Spotify. Make sure any audio files distributed with a public deployment are licensed for that use.
