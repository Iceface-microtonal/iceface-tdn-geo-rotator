# TDN Geo-Rotating Arpeggiator

**Kinetic music instrument with cloth-physics interaction** — Iceface Toys series

A browser-based instrument where notes are triggered by movement, not keystrokes. Drag on a cloth-mesh canvas to bend pitch, velocity, and timing in real time. Built on the **T(D,N) Relational-Temporal** transformation framework.

### What is T(D,N)?

A single parameter **N** simultaneously controls two musical dimensions for non-diatonic notes:
- **Time**: step distance is multiplied by N (shorter at low N)
- **Pitch**: cents offset of (1 − N) × 100¢ toward the nearest diatonic note

At N = 1.0, standard equal temperament. At N → 0, non-diatonic notes compress in both pitch and time.

### Features

- **Cloth-physics Field Drag** — canvas mesh deforms with spring-damper physics; drag modulates pitch, filter, swing, and velocity in real time
- **15 geometric auto-play patterns** — Lissajous, Rose curves, Double Pendulum, Random Walk, and more
- **10 Global Presets** — from Acid Saw to Zen Garden, each a complete configuration
- **11 tuning systems** — Equal, Iceface, Just Intonation, Pythagorean, Maqam Rast, Kotori, Balloon, and Iceface variants
- **9 scales** — Major, Minor, Chromatic, Pentatonic, Dorian, Phrygian, Lydian, Whole Tone, Diminished
- **Synthesizer** — oscillator with 4 waveforms, low-pass filter, resonance, convolution reverb, glide
- **Drum machine** — 3-voice synthesized drums (kick, snare, hi-hat), 6 built-in patterns, pattern editor
- **T(D,N) + LEAP modes** — two timing algorithms: note-identity-based and interval-distance-based
- **Z-Depth & Swing** — additional expression controls for velocity depth and rhythmic shuffle
- **Mobile-friendly** — touch-optimized, works on smartphone and tablet
- **Pure HTML / JavaScript** — no installation, no dependencies, no build step

### How to Use

1. Open `index.html` (or visit the GitHub Pages URL)
2. Press **PLAY** — the cursor follows a geometric path and generates music
3. **Drag on the canvas** — the cloth mesh deforms, modulating the sound in real time
4. Explore **Global Presets** for instant sonic characters
5. Adjust T(D,N) N slider, tuning, scale, and synth parameters to sculpt your sound

### Documentation

- [English Manual](manual.html)
- [日本語マニュアル](manual_ja.html)
- [Drum Pattern Guide (PDF)](DrumPatternGuide.pdf)
- [TDN Theory Reference (PDF)](TDN_Theory_Reference.pdf)

### Related Projects

- Iceface TOY One
- IcefaceTDN Beat Machine

Made with love by @H__Wakabayashi (Iceface / PuppeTwin)
