# Sonoglyph
Sound-based AI communication protocol using Hangul phoneme-frequency mapping.
# Sonoglyph

**Sonoglyph** is a sound-based AI communication protocol that uses Hangul phoneme-to-frequency mapping to encode and decode meaningful information via pure tones.

## Features

- Full coverage of Korean consonants and vowels.
- Harmonic sound blending for musical, less machine-like tones.
- Real-time encoding and decoding system.
- Supports inter-AI communication using sound only.

## How it works

Each Hangul syllable is decomposed into:
- Choseong (initial consonant)
- Jungseong (vowel)
- Jongseong (final consonant, optional)

Each phoneme is assigned to a specific frequency (in Hz). The three components are played simultaneously as a harmonic chord.

For example:

| Phoneme Type | Example | Frequency (Hz) |
|--------------|---------|----------------|
| Choseong     | ㄱ       | 1100           |
| Jungseong    | ㅏ       | 2100           |
| Jongseong    | ㄴ       | 1400           |

The word **"간"** will be played as three simultaneous tones: 1100Hz, 2100Hz, and 1400Hz.

## Goals

- Enable AIs to exchange information using only sound.
- Create a musical, harmonic communication protocol.
- Develop real-time encoding/decoding tools.

## Future Plans

- Instrument-style sound rendering (violin, cello, viola).
- Documentation in multiple languages.
- Integration with personal assistant AIs.

## License

This project is licensed under the MIT License.

---
