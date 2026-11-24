# Keyboard Key Visualizer

A canvas-based exercise that categorizes keyboard input.

**Repository created:** 2021-07-25  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2021-07-25

## Features and implementation

- Keyboard event listeners.
- Key-code comparisons.
- Category-specific image assets.
- Status text.

## Technologies

HTML, CSS, JavaScript, Bootstrap, jQuery.

## Project structure

| File | Purpose |
| --- | --- |
| [`index.html`](index.html) | Main page and user interface |
| [`main.js`](main.js) | Project-specific JavaScript |

Key functions in the source:
- `main.js`: `add()`, `uploadimg()`, `my_keydown()`, `aplhabetkey()`, `numberkey()`, `arrowkey()`, `specialkey()`, `otherkey()`.

## Run or explore locally

```bash
git clone https://github.com/Avenger-Sonic123/ASCII-keyboard.git
cd ASCII-keyboard
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. The local server requires Python 3; browser-based dependencies may also require internet access.

Press alphabet, number or arrow keys and inspect the canvas and console.

## Current status and limitations

The special/other key conditions contain incorrect expressions, so not every key category works reliably.

---

Source reference: [`f0d36854`](https://github.com/Avenger-Sonic123/ASCII-keyboard/tree/f0d36854f9350d9bb25a73f62fd7977893bdfe5f) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
