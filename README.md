# ÆtherStrum 🎵

An ethereal musical instrument that combines visual art with sound synthesis. Create mesmerizing music by interacting with vibrating strings in a beautiful, particle-rich environment. [Demo](https://drbaph.dev)

![og-image](https://github.com/user-attachments/assets/a3636bb9-9d8b-4d8b-8b49-b5c29edd013b)


## ✨ Features

- **Multi-Instrument Support**
  - Hang Drum
    - Custom scale with D Minor tuning (F3 root)
    - Square waveform for metallic "ping"
    - Rich harmonics profile [1.0(0.8), 2.0(0.5), 2.8(0.3), 3.8(0.15), 5.0(0.05)]
    - Quick attack (50ms), medium decay (500ms), low sustain (0.2)
  - Bass Guitar
    - Major scale with A1 base frequency (55 Hz)
    - Triangle waveform for warm bass tones
    - Deep harmonics [1.0(1.0), 2.0(0.6), 3.0(0.2), 4.0(0.1)]
  - Ocarina
    - Minor scale with C4 base (261.63 Hz)
    - Pure sine wave with subtle harmonics [1.0(1.0), 2.0(0.2), 3.0(0.1)]
    - Smooth envelope: attack(0.1), decay(1.0), sustain(0.3), release(0.5)
    - Built-in vibrato (5Hz rate, 0.02 depth)
    - Integrated reverb (0.3 mix, 1.5s decay)
    - Auto-play feature: Click the music note button in the bottom right to play:
      - Saria's Song
      - Tetris Theme (Korobeiniki)

- **Visual Effects**
  - Dynamic particle systems that react to string vibrations
  - Colorful tracer effects that follow string movement
  - Customizable color themes

- **Audio Processing**
  - High-quality reverb with adjustable mix
  - Professional-grade audio synthesis
  - Built-in recording functionality

- **Interactive Elements**
  - Touch/mouse-based string plucking
  - Real-time parameter controls
  - Built-in song playback system

## 🎮 How to Play

1. **Select an Instrument**: Choose between Hang Drum, Bass Guitar, or Ocarina
2. **Pluck the Strings**: Click or drag across the strings to create sound
3. **Adjust Effects**: Use the control panel to modify:
   - Particle density
   - Tracer complexity
   - Reverb amount
   - Overall volume
4. **Play Songs**: When using the Ocarina, click the music note button in the bottom right to play built-in songs

## 🎵 Built-in Songs (Ocarina)

The Ocarina features an auto-play system with two classic tunes:
- Saria's Song
- Tetris Theme (Korobeiniki)

Access these by clicking the music note button in the bottom right corner. The songs will alternate with each click.

## 🛠️ Technical Details

ÆtherStrum is built using:
- Web Audio API for sound synthesis
- Canvas API for visual effects
- Pure JavaScript for physics simulation

https://github.com/user-attachments/assets/15a882db-64ff-4dd4-b65a-4bf92f6fb113

## 📜 License

ÆtherStrum is licensed under the Apache License 2.0. See [LICENSE](LICENSE) for more information.

## 🌐 Author

by DrBaph  
Visit [drbaph.dev](https://drbaph.dev) for more projects
