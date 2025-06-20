# 🎶 BotChime

🚧 This project is a work in progress. Not stable. Not ready for production use. 🚧

---

**BotChime** is a musical protocol for sending short ASCII messages using sound alone. It works entirely in-browser - no backend, Bluetooth, or WiFi needed. Just good vibrations.

This project explores the boundary between communication protocols, music, and play. You can try it yourself using any two browser-enabled devices.

---


## 🔗 Live Demo

👉 Try it here: [https://chuckmichelson.github.io/botchime](https://chuckmichelson.github.io/botchime)

> Works best in a quiet room with devices placed 6–24 inches apart.

---

### How to Use

- Open the transmitter on one device, type a message, and choose a chord progression.
- Open the receiver on another device, press Record Audio, and it will listen and decode for 8 seconds.
- On the transmitter, Press Play.
- Aim the receiver's mic toward the sound source.

---

## 🧪 How It Works

1. **Transmitter**: Converts a short ASCII message into a sequence of musical chords, each encoded with an 8-bit symbol.
2. **Receiver**: Listens for chord transitions and decodes the original message using spectral analysis.
3. **Meta chords:** Indicate how to interpret each symbol, allowing flexible musical progressions with embedded data.

---

## 📁 File Structure

| File | Purpose |
|------|---------|
| `index.html` | Entry point: choose Transmitter or Receiver |
| `transmitter.html` | Sends musical messages |
| `receiver.html` | Listens and decodes messages |
| `constants.json` | Defines notes, chords, and progressions, etc. |
| `recording.wav` | Test audio for loading |
| `README.md` | You’re here! |

---

## 🧠 Concepts

BotChime draws from several domains:

Digital communication: Messages are encoded in 8-bit symbols like old-school ASCII.
Music theory: Each chord is constructed to carry both musical meaning and data.
Signal processing: The receiver performs spectral analysis to extract information from sound.
Playful tech: It’s designed to be fun.

---

## 🎵 Musical Foundations

BotChime uses a visual representation of harmony called the **Tonnetz** (German for "tone network"). Originally devised by mathematician **Leonhard Euler**, the Tonnetz maps pitch classes into a geometric space where harmonic relationships — like major and minor chords — become visually adjacent.

---

## 🧬 Inspiration

BotChime draws inspiration from projects like **Gibberlink**, which also explores real-time communication through sound and signal.

---

## 🚧 Limitations

Works best in quiet environments.
Requires reasonably modern devices (especially for accurate microphone input).
Transmission speed is balanced with musical aesthetics - roughly 8 characters per second.

---

## ✨ Credits

Created by Chuck Michelson
With help from GPT-4 for code, concept shaping, and tweaks.

---

## 📄 License

MIT License.
See LICENSE for full terms.