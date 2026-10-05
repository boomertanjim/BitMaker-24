# BitMaker 24

Bitmaker 24 is a digital drum sequencer sized at only 3kb

## Description

Bitmaker 24 is a lightweight, browser based drum sequencer that plays synthesized kicks, snares and hi-hats. It is built with HTML, JS, Canvas API and Web Audio API

The sequencer features a 16 x 3 grid of buttons, allowing the user to create and loop various beats, while adjusting the tempo with the given slider.

### Screenshots

## How To Use

- Copy the text from `dist/uri.txt` and paste it in the browser

- Each row of buttons represent Hi-Hat, Snare and kick from top to bottom

- Each row has 16 buttons that determine when to play the corresponding drum sound

- Click any step to activate or deactivate it

- As the sequencer plays, active steps play corresponding drum sounds

- The playhead below the buttons moves through the steps continuously

- Use the Tempo slider to adjust the BPM(Beats Per Minute)

- Experiment with different kick, snare and hi-hat combination to create your own beats

TLDR:
Row 1 --> Hi-hat
Row 1 --> Snare
Row 1 --> Kick
The controls are fully similar to any sequencer available in the internet

## Building From Source

First, Download Node.js from [the official website](https://nodejs.org/en/download/current)

Install Terser

```bash
npm install --save-dev terser
```

Download the `src` folder with the `index.html` file inside.

Download and put the `build.mjs` next to the `src` folder.

Run this code

```bash
node build.mjs
```

The URI file and the shrunken `index.html` file will be made in the `dist` folder
