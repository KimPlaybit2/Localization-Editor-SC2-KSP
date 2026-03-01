# Localization-Editor-SC2-KSP
A localization editor for StarCraft II maps and mods. Opens GameStrings.txt files, translates them into selected languages, and automatically saves them into the correct SC2Data directory structure.
---

## LibreTranslate Setup (Optional – for auto-translation)

The editor uses a local LibreTranslate server for automatic translation.

The application expects LibreTranslate running at:

http://127.0.0.1:5000

### Installation (without Docker)

1. Install **Python 3.9+**  
   https://www.python.org/downloads/

2. Install LibreTranslate:

```bash
pip install libretranslate
