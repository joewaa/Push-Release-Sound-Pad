# Push-Release-Sound-Pad

## Key Highlights & Features Included
1. Push & Release Dual Action:
  - Sound A triggers immediately on pointerdown (or keyboard Space / Enter) and plays for up to 3.0 seconds.
  - Releasing the button triggers Sound B immediately, with an option (checked by default) to cleanly cut off Sound A upon release.
  - Sound B plays for exactly 3.0 seconds.
2. Zero External Dependencies Required:
  - Ships with procedural Web Audio API synthesizers (Sci-Fi Beam, Sub Bass, Cyber Rev for Press, and Warp Burst, Crystal Chime, Retro Glitch for Release), ensuring audio plays without needing external MP3 files.
3. Custom Audio Upload & URL Loaders:
  - Dedicated file pickers for Sound A and Sound B to upload custom .mp3, .wav, or .ogg clips.
  - Remote URL audio input with asynchronous decoding via Web Audio API.
4. Visual Indicators & Feedback:
  - Dual 3-second animated countdown and progress bars with live timestamps.
  - Real-time oscilloscope / audio waveform visualizer powered by AnalyserNode.
  - 3D tactile button with realistic depth, ambient glows, status indicators, and toast alerts (avoiding alert()).
  - Unified support for touch screens (pointerdown/pointerup), mouse clicks, and keyboard navigation.
