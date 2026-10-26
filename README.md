# Shutter Tools

Browser tools for checking a film camera's shutter speeds with an iPhone.

- **Shutter Trace** (`shutter-trace.html`): measures each firing from a slo-mo video of light through the film gate.
- **Shutter Sound** (`shutter-sound.html`): records or loads audio of a photodiode on the mic input, or of shutter clicks, and measures the open time. In-page recording turns off echo cancellation, noise suppression and auto gain, and can save a 32-bit WAV.
- **Shutter Sim** (`shutter-sim.html`): plays screen flashes, clicks or pulses of known length to test the other two tools.

Everything runs locally in the browser. Microphone recording needs HTTPS, which GitHub Pages provides.

## Hosting

Served by GitHub Pages from the `main` branch root. To run locally, open `index.html` in Chrome or run `python3 -m http.server` in this folder.
