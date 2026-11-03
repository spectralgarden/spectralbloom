# Spectral Bloom - Audio Plugin
**Developer:** Spectral Garden  
**Target Environment:** Visual Studio 2026 (v145 Toolset)  
**Framework:** JUCE 8.0.14  
**Format:** Windows-only VST3 Synthesizer Instrument (No macOS, no Standalone, no CMake)  
**Source Architecture:** Exactly 4 source files (`PluginProcessor.h`, `PluginProcessor.cpp`, `PluginEditor.h`, `PluginEditor.cpp`)

---

## Overview
Spectral Bloom is a premium hybrid analog-digital synthesizer tailored for:
- Witch House
- Darkwave & Coldwave
- Shoegaze & Dream Pop
- Industrial & Ambient Cinematic
- Synthwave & Atmospheric Electronic

## Features
- **Dual Oscillators:** Saw, Square, PWM, Triangle, Sine, SuperSaw (7-voice detuned unison stack), Noise, Wavetable Hybrid, Spectral Oscillator.
- **Dedicated Sub Oscillator:** Sine, Triangle, Square (-1 / -2 octaves).
- **Oscillator Modulation:** Sync, Ring Modulation, FM Amount, Stereo Spread, Detune, Phase, Analog Drift, Vintage Instability, and **Haunted Drift** (chaotic multi-axis pitch, filter, and stereo movement).
- **Multimode Filter:** LP12, LP24, HP12, HP24, Bandpass, Notch, Ladder, SVF, Morph, with Drive, Warmth, Saturation, and proprietary **Bloom Resonance** stage.
- **Spectral Layer Engine:**
  - **Mist:** Atmospheric harmonic noise.
  - **Bloom:** Lush harmonic overtone expansion.
  - **Ghost:** Reverse-like spatial ambience and ethereal trails.
  - **Dust:** Analog tape flutter, age, and imperfection.
- **Integrated FX Rack:** Chorus, Ensemble, Flanger, Phaser, Ping-Pong Delay, Reverb, Tape Saturation, Analog Saturation, Bitcrusher, Vinyl Wear, Stereo Imaging, Compressor.
- **Smart Randomize:** Intelligently creates new patches while strictly preserving the selected category (Basses stay Basses, Leads stay Leads, Pads stay Pads, etc.).
- **Inspire Button:** Creates musically coherent variations of the current patch.
- **100 Factory Presets:** 20 Bass, 20 Lead, 20 Pad, 10 Arp, 10 Pluck, 10 Texture, 10 Atmospheric. User presets stored at `%APPDATA%/SpectralGarden/SpectralBloom/UserPresets/`.
- **Visualizers:** Animated OpenGL spectral bloom flower, real-time oscilloscope, harmonic analyzer, ambience field, CPU meter.
- **Workflow:** A/B state switching, Undo/Redo, Scalable UI (100%, 125%, 150%, 200%), full APVTS automation, MIDI Learn.

---

## Installation (Windows)

This release is distributed as a prebuilt VST3 plug-in. You do not need Projucer, JUCE, or Visual Studio to install it.

1. If the download is compressed, extract it and locate `SpectralBloom.vst3`.
2. Copy the entire `SpectralBloom.vst3` bundle to a VST3 plug-in folder. Common locations are:
   - System-wide: `C:\Program Files\Common Files\VST3`
   - For the current user: `%LOCALAPPDATA%\Programs\Common\VST3`
   - A custom VST3 folder configured in your DAW
3. If prompted for administrator permission when installing system-wide, approve the copy or install it in the current-user folder instead.
4. Restart your DAW or rescan its VST3 plug-ins, then look for **Spectral Bloom** among the instruments.

Use the folder your DAW scans if it has a custom VST3 location. Do not copy only the contents inside `SpectralBloom.vst3`; copy the complete bundle.
