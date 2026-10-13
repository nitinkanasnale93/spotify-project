Spotify-Inspired Music Player
A browser-based music player built with HTML, CSS, and vanilla JavaScript. It includes a selectable playlist, playback controls, album artwork, and a seekable progress bar.
Live Demo
Open the Music Player
Features
- Play and pause the selected song.
- Choose a song from the playlist.
- Skip to the next or previous track.
- Click or drag the progress bar to seek through a song.
- Display track titles and album artwork.
- Show playback indicators in the player interface.
Tech Stack
- HTML5 — page structure and player interface
- CSS3 — layout and styling
- JavaScript — playlist interactions, playback controls, and progress updates
- HTML Audio API — audio playback and seeking in the browser
- Font Awesome — player-control icons
- Git and GitHub — version control and source-code hosting
- Render — static-site deployment
Run Locally
1. Clone this repository:
   git clone https://github.com/nitinkanasnale93/spotify-project.git
2. Move into the project folder:
   cd spotify-project
3. Open index.html in your browser, or use the Live Server extension in VS Code.
This is a static website, so no build command or package installation is required. Keep the HTML, CSS, JavaScript, audio, and image files in their expected relative locations so the playlist loads correctly.
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
- Controlling playback with HTMLAudioElement
- Updating playback progress using currentTime and duration
- Connecting a static website to GitHub and deploying it on Render
Future Improvements
- Improve keyboard and screen-reader accessibility.
- Test and refine the layout on more mobile screen sizes.
- Add track duration and elapsed-time labels.
- Add clearer loading and playback-error states.
Note
This is a learning project inspired by music-player interfaces. It is not affiliated with or endorsed by Spotify. Make sure any audio files distributed with a public deployment are licensed for that use.
