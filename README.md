# DidiPlugins

Audio Plugins for Music Production

A collection of professional audio plugins crafted for modern music production.

## Plugins

### Board (v1.1.0)
VST3 Grid Hotkey Plugin. A customizable grid interface for triggering keyboard shortcuts and hotkeys directly in your DAW. Assign letters, numbers, function keys, and modifier combinations to each cell for instant, one-click access.

### Namsound (v1.55)
Guitar and bass effects processor with Neural Amp Modeler (NAM). Combines neural captures of amplifiers and pedals with a modern signal-graph interface. Available as VST3, AU, CLAP, AAX, and Standalone.

### Spectro (v1.0.0)
Real-time spectral analyzer VST3 plugin and standalone application. Professional-grade FFT visualization with a dark, mixbus-style interface. Supports FFT sizes 512–16384 with 8–256 logarithmically-spaced bands.

### TranceG (v1.0.0)
Trance Gate Sequencer generating rhythmic gating patterns with up to 32 steps. Each step has individual activation, level, accent, and linked state. Modulates audio through a configurable ADSR envelope and optional filters, synced to host tempo.

## Running Locally

This is a static website. To view it locally:

```bash
# Option 1: Open index.html directly in your browser
# Option 2: Use a simple HTTP server
npx serve .
# or
python -m http.server 8080
```

Then navigate to `http://localhost:8080`.

## Structure

```
DidiPlugins/
├── index.html        # Main website
├── style.css         # Styles
├── pinokio.json      # Pinokio metadata
├── board.png         # Board plugin image
├── namsound.png      # Namsound plugin image
├── spectro.png       # Spectro plugin image
├── tranceg.png       # TranceG plugin image
└── README.md         # This file
```
