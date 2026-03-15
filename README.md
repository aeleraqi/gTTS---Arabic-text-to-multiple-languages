# Arabic Text to Multiple Languages TTS 🌍🔊

[![Language](https://img.shields.io/badge/Language-Python%20%7C%20Jupyter-blue)](https://github.com/aeleraqi/gTTS---Arabic-text-to-multiple-languages)
[![Stars](https://img.shields.io/github/stars/aeleraqi/gTTS---Arabic-text-to-multiple-languages?style=social)](https://github.com/aeleraqi/gTTS---Arabic-text-to-multiple-languages/stargazers)

Convert **Arabic text** to speech in multiple languages using gTTS and Google's TTS engine.

## 📖 About

This notebook goes beyond simple Arabic TTS — it translates Arabic text and generates speech in various target languages, enabling multilingual voice output from a single Arabic input.

## ✨ Features

- Accept Arabic text input
- Translate to multiple target languages
- Generate speech in each target language
- Supports 20+ languages including English, French, Spanish, German, Turkish
- Batch export all audio files

## 🚀 Getting Started

```bash
pip install gtts googletrans==4.0.0rc1
```

## 💡 Usage

```python
from gtts import gTTS

languages = {"en": "English", "fr": "French", "es": "Spanish"}
for lang_code, lang_name in languages.items():
    tts = gTTS(text=translated_text, lang=lang_code)
    tts.save(f"output_{lang_name}.mp3")
```

---
**Author:** [Amr Eleraqi](https://github.com/aeleraqi) — Data Analyst | NLP Specialist | Machine Learning Expert | Educator  
**Affiliation:** Toronto Metropolitan University, Ontario, Canada  
[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--0935--0026-brightgreen)](https://orcid.org/0000-0003-0935-0026) [![GitHub](https://img.shields.io/github/followers/aeleraqi?label=Follow&style=social)](https://github.com/aeleraqi)
