# JavaScript Drum Kit

A simple browser-based drum kit built with vanilla HTML, CSS, and JavaScript. Press the mapped keys on your keyboard to play drum sounds and see the matching key highlight on screen.

## Features

- Keyboard-triggered drum sounds
- Visual key feedback while a sound plays
- Lightweight setup with no build tools or dependencies
- Custom audio files stored locally in the `Songs/` folder

## Controls

Press these keys to trigger sounds:

- `A` - Clap
- `S` - Snare
- `D` - Drum
- `F` - Boom
- `G` - Ride
- `H` - Tink
- `J` - Hi-hat
- `K` - Kick
- `L` - Open hat

## Project Structure

```text
.
|-- index.html
|-- style.css
|-- script.js
`-- Songs/
    |-- boom.mp3
    |-- clap.mp3
    |-- drum.mp3
    |-- hihat.mp3
    |-- kick.mp3
    |-- openhat.mp3
    |-- ride.mp3
    |-- snare.mp3
    `-- tink.mp3
```

## How It Works

- `index.html` defines the drum pads and loads the audio files.
- `style.css` handles the layout and the active key animation.
- `script.js` listens for keyboard input, plays the matching sound, and highlights the pressed key.

## Getting Started

1. Clone or download the project.
2. Open `index.html` in your browser.
3. Press the mapped keys to start playing.

## Notes

- The project is designed to run directly in the browser.
- If you add more sounds, update both the key markup in `index.html` and the keyboard logic in `script.js`.
