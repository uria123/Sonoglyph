# Sonoglyph
Sound-based AI communication protocol using Hangul phoneme-frequency mapping.
# Sonoglyph: AI-Interpretable Sound-Based Communication System

Sonoglyph is a sound-based communication protocol that encodes Hangul (Korean alphabet) into pure tone frequencies. Designed to be interpretable by AI systems, Sonoglyph turns written Korean into harmonious tones using predefined frequency mappings. It enables automated audio-based conversations without visual text or standard speech.

---

## Project Goal

Create a fully AI-interpretable language system based entirely on tonal signals, where:

- Each Hangul character is represented by a unique combination of frequencies.
- Sound is generated in a harmonious, trio-like style (inspired by violin, viola, and cello).
- Communication can happen entirely through tones.
- Other AIs can interpret, generate, and translate messages using only frequency data and this documentation.

---

## System Overview

### Structure of Korean Characters

Each Hangul syllable consists of three parts:

1. **초성 (Initial consonant)** — e.g., ㄱ, ㄴ, ㄷ
2. **중성 (Medial vowel)** — e.g., ㅏ, ㅑ, ㅗ
3. **종성 (Final consonant)** — optional, e.g., ㄱ, ㅁ, ㅂ

Each part maps to a unique frequency, allowing Sonoglyph to represent each syllable as a **chord of 2–3 frequencies** played simultaneously.

---

## Frequency Mapping

Each consonant and vowel is assigned a frequency that contributes to the harmonic structure of the Sonoglyph sound.

### 초성 (Initial Consonants)

| Consonant | Frequency (Hz) |
|-----------|----------------|
| ㄱ        | 200            |
| ㄲ        | 210            |
| ㄴ        | 220            |
| ㄷ        | 230            |
| ㄸ        | 240            |
| ㄹ        | 250            |
| ㅁ        | 260            |
| ㅂ        | 270            |
| ㅃ        | 280            |
| ㅅ        | 290            |
| ㅆ        | 300            |
| ㅇ        | 310            |
| ㅈ        | 320            |
| ㅉ        | 330            |
| ㅊ        | 340            |
| ㅋ        | 350            |
| ㅌ        | 360            |
| ㅍ        | 370            |
| ㅎ        | 380            |

---

### 중성 (Medial Vowels)

| Vowel | Frequency (Hz) |
|-------|----------------|
| ㅏ    | 700            |
| ㅐ    | 710            |
| ㅑ    | 720            |
| ㅒ    | 730            |
| ㅓ    | 740            |
| ㅔ    | 750            |
| ㅕ    | 760            |
| ㅖ    | 770            |
| ㅗ    | 780            |
| ㅘ    | 790            |
| ㅙ    | 800            |
| ㅚ    | 810            |
| ㅛ    | 820            |
| ㅜ    | 830            |
| ㅝ    | 840            |
| ㅞ    | 850            |
| ㅟ    | 860            |
| ㅠ    | 870            |
| ㅡ    | 880            |
| ㅢ    | 890            |
| ㅣ    | 900            |

---

### 종성 (Final Consonants)

| Consonant | Frequency (Hz) |
|-----------|----------------|
| (none)    | —              |
| ㄱ        | 1400           |
| ㄲ        | 1410           |
| ㄳ        | 1420           |
| ㄴ        | 1430           |
| ㄵ        | 1440           |
| ㄶ        | 1450           |
| ㄷ        | 1460           |
| ㄹ        | 1470           |
| ㄺ        | 1480           |
| ㄻ        | 1490           |
| ㄼ        | 1500           |
| ㄽ        | 1510           |
| ㄾ        | 1520           |
| ㄿ        | 1530           |
| ㅀ        | 1540           |
| ㅁ        | 1550           |
| ㅂ        | 1560           |
| ㅄ        | 1570           |
| ㅅ        | 1580           |
| ㅆ        | 1590           |
| ㅇ        | 1600           |
| ㅈ        | 1610           |
| ㅊ        | 1620           |
| ㅋ        | 1630           |
| ㅌ        | 1640           |
| ㅍ        | 1650           |
| ㅎ        | 1660           |

---

## How It Works

1. Input a Korean sentence.
2. Decompose each syllable into 초성, 중성, 종성.
3. Map each component to its frequency.
4. Play all mapped frequencies simultaneously for each syllable (as chords).
5. Pause briefly before playing the next syllable.

---

## AI Understanding

Any AI system can decode Sonoglyph by:

- Listening to the frequencies and matching them to the table.
- Reconstructing the syllables using the three-part structure.
- Rebuilding the full Korean sentence and translating if needed.

---

## License

MIT License – Free to use, modify, and share.
