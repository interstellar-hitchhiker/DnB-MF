# DnB-MF
DnB MeltFlow is a full-screen Butterchurn/MilkDrop radio visualiser

DnB MeltFlow is a single-page browser visualiser built around Butterchurn, the WebGL version of the classic MilkDrop visual engine. It turns internet radio stations or local audio files into full-screen psychedelic visuals, with preset browsing, random preset switching, auto-morphing, brightness control, saturation control, and a clean hidden-interface mode for watching the visuals without distraction.

The app is designed as a simple GitHub Pages project. Save the file as `index.html`, upload it to a repository, enable GitHub Pages, and open the published page in a modern browser. Because it loads Butterchurn, Butterchurn preset packs, and online radio streams from the internet, the page needs a network connection.

## What it does

DnB MeltFlow loads a Butterchurn/MilkDrop visual canvas in the browser and gives the user a simple control panel for music and visuals. You can choose a radio station, browse hundreds of MilkDrop-style presets, filter presets by rough visual mood, randomise the current look, or let the app auto-morph between presets over time.

The main purpose is enjoyment: a quick, free, full-screen visual music toy for drum and bass, ambient, downtempo, trance, space music, and trippy late-night listening.

## Audio sources

The app includes preset stream options for:

* Bassdrive — drum and bass radio.
* SomaFM Drone Zone — atmospheric ambient textures with minimal beats.
* SomaFM Deep Space One — deep ambient electronic and space music.
* SomaFM Groove Salad — ambient, downtempo, and chillout electronica.
* SomaFM The Trip — trance and progressive electronic music.
* Local audio file — best for true audio-reactive Butterchurn behaviour.
* Silent visuals — visuals only, with no sound.

## Important audio note

Radio playback is kept separate from Butterchurn audio analysis so the stream does not mute or break if browser security blocks cross-origin audio analysis. This means radio stations should still play and the visuals should still animate beautifully.

For the strongest real audio-reactive behaviour, use a local MP3, WAV, or OGG file. Local audio can be connected more directly to Butterchurn’s WebAudio pipeline, so the visuals are more likely to respond properly to the music.

## Visual controls

DnB MeltFlow includes:

* preset dropdown with hundreds of Butterchurn/MilkDrop visuals;
* vibe filters such as space, tunnel, liquid, calm, and psychedelic;
* random preset button;
* next preset button;
* auto-morph mode;
* auto-morph interval control;
* blend/morph duration control;
* brightness limit;
* saturation control;
* soft dim overlay;
* hide-controls mode;
* fullscreen mode.

## Keyboard shortcuts

* Space: play or pause.
* F: fullscreen.
* R: random preset.
* N: next preset.
* A: toggle auto-morph.
* C or H: hide or show controls.

## Why single HTML?

The project is intentionally built as one HTML file. The HTML, CSS, and JavaScript are kept together so the app is easy to save, upload, share, modify, and publish through GitHub Pages without build tools, package managers, servers, accounts, or setup steps.

It is not meant to be a professional music platform. It is a compact browser-based visual toy: one file, one page, instant psychedelic radio visuals.
