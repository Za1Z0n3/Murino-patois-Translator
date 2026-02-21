# Murinsky Translator (Burmalda-GPT)

A Python-based "dialect" translator that converts standard Russian text into the viral **"Murinsky Slang"** (popularized by Mellstroy memes). This tool mimics intentional typos, bizarre suffixes like `-ost` and `-un`, and specific meme vocabulary.

## Features

* **Meme Dictionary:** Hardcoded transformations for iconic words (e.g., `друг` -> `друн`, `дед` -> `дод`).
* **The "-ost" Logic:** Automatically mutates nouns by adding "slavic-absurdist" suffixes.
* **The "-un" Rule:** Dynamically converts roles and professions (e.g., `физрук` -> `физрун`).
* **Fat-Finger Typos:** Simulates keyboard misses based on the Russian JCUKEN layout.
* **Bormalda-Generator:** Randomly transforms long words into "Bormalda" style versions.
* **Censor Bypass:** Automatically masks sensitive words using "Leet Speak" (Latin look-alike characters).

## Contributing
If you found a new "Murinsky" word or rule in TikTok, feel free to open a Pull Request! Let's build the most cursed dictionary together.

## Disclaimer
This project is for entertainment purposes only. It is a parody of internet subcultures and meme trends.

### Example of using
```python
from translator import MurinskyTranslator

mt = MurinskyTranslator()
print(mt.process_text("Мой друг зашел в магазин и купил пиво"))
# Output: Мой друн зашел в магазун и купил пивность
```
### Instalation
Copy repositorie
```bash
git clone [https://github.com/Za1Z0n3/Murino-patois-Translator.git](https://github.com/Za1Z0n3/Murino-patois-Translator.git)
cd murinsky-translator
