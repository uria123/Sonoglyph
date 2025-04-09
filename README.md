# Sonoglyph
Sound-based AI communication protocol using Hangul phoneme-frequency mapping.
## Overview

**Sonoglyph** is a sound-based AI communication protocol built upon Hangul phoneme-to-frequency mapping. It allows machines to "speak" using pure tones, and other AI agents to interpret these tonal messages without relying on text or conventional language models.

---

## Key Features

- Hangul-based frequency mapping (initials, vowels, finals)
- Harmonized triad output inspired by violin, cello, and viola
- Compact tone sequences for real-time transmission
- Designed to be interpretable by AI without natural language

---

## Frequency Mapping

### Consonants (Choseong)
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

### Vowels (Jungseong)
| Vowel | Frequency (Hz) |
|-------|----------------|
| ㅏ    | 1000           |
| ㅐ    | 1100           |
| ㅑ    | 1200           |
| ㅒ    | 1300           |
| ㅓ    | 1400           |
| ㅔ    | 1500           |
| ㅕ    | 1600           |
| ㅖ    | 1700           |
| ㅗ    | 1800           |
| ㅘ    | 1900           |
| ㅙ    | 2000           |
| ㅚ    | 2100           |
| ㅛ    | 2200           |
| ㅜ    | 2300           |
| ㅝ    | 2400           |
| ㅞ    | 2500           |
| ㅟ    | 2600           |
| ㅠ    | 2700           |
| ㅡ    | 2800           |
| ㅢ    | 2900           |
| ㅣ    | 3000           |

### Finals (Jongseong)
| Final | Frequency (Hz) |
|-------|----------------|
| ㄱ    | 3100           |
| ㄲ    | 3110           |
| ㄳ    | 3120           |
| ㄴ    | 3130           |
| ㄵ    | 3140           |
| ㄶ    | 3150           |
| ㄷ    | 3160           |
| ㄹ    | 3170           |
| ㄺ    | 3180           |
| ㄻ    | 3190           |
| ㄼ    | 3200           |
| ㄽ    | 3210           |
| ㄾ    | 3220           |
| ㄿ    | 3230           |
| ㅀ    | 3240           |
| ㅁ    | 3250           |
| ㅂ    | 3260           |
| ㅄ    | 3270           |
| ㅅ    | 3280           |
| ㅆ    | 3290           |
| ㅇ    | 3300           |
| ㅈ    | 3310           |
| ㅊ    | 3320           |
| ㅋ    | 3330           |
| ㅌ    | 3340           |
| ㅍ    | 3350           |
| ㅎ    | 3360           |

---

## Example

**Input Text:**  
`가야할 때를 알고 가는 저 뒷모습은 얼마나 아름다운가`

**Output (Simplified Sonoglyph Sequence):**  
- [200, 1000, 3100]  
- [220, 1000]  
- [380, 1400, 3360]  
... (truncated for brevity)

Each syllable is rendered as a **triad** of consonant, vowel, and (optional) final frequencies, forming a short harmonic sound.

---

## AI Interpreter Design

To interpret Sonoglyph:

1. **Fourier Transform** incoming signal
2. **Match peaks** to known frequency map
3. **Reconstruct Hangul syllable** using [choseong, jungseong, jongseong]
4. **Assemble text** and decode message

This process can be embedded into any AI agent for audio-based understanding.

---

## License

MIT License (Free to use and modify with attribution)
