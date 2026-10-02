# For Rudri — birthday scrapbook

A mobile-first birthday story built with vanilla HTML, CSS, and JavaScript. Open `index.html` directly, or serve this folder locally with `python -m http.server 8000` and visit `http://localhost:8000`.

The chapter flow is Opening → keypad → seven-song songbook → Record Club → Photo Booth → Bouquet + Memories → Letter → rolling credits → final-message framework. Every fresh load starts at Opening.

## Assets

- The seven Rudri portraits in `assets/photos/` are mapped by visual identification in `script.js`.
- The seven song files in `assets/audio/` are wired into the songbook and Record Club.
- The supplied bouquet and paper artwork remain in `assets/stickers/` and are used directly.
- Future photo-booth images can be named `photo-01.jpg`, `photo-02.jpg`, and `photo-03.jpg` in `assets/photobooth/`.
- A future Frost photo can be added as `assets/frost/frost.jpg`.
- `assets/opening/`, `assets/sfx/`, `assets/bouquet/`, and `assets/memories/` are ready for later source assets. The current build also uses the supplied cake, paper, and bouquet references directly.
- Add the Spotify playlist URL to `spotifyPlaylistUrl` in `script.js` when available. The external button stays inert until then.

The letter and final message intentionally contain insertion placeholders rather than invented personal text.
