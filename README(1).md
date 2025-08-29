# If/Else en Lijsten — Stemrecht-checker 🇳🇱

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BrinkmannB/stemrecht-notebook/blob/main/if_else_en_lists_stemrecht.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Kleine oefen-notebook om `for`-lussen en `if/else` te leren aan de hand van een simpel voorbeeld: wie mag stemmen in NL (18+).  
> 18+? 🔔 Democratie gaat open. Onder 18? ⏳ Nog even geduld.

## Wat zit erin?
- Basisvoorbeeld met een lijst `leeftijden`
- Varianten met `(naam, leeftijd)`-tuples
- Selectie met list comprehension
- Tellen hoeveel mensen 18+ zijn
- Herbruikbare functie `check_stemrecht(...)`
- Oefeningen (pas zelf namen/leeftijden aan, of verander de minimumleeftijd)

## Snel starten
**In Colab (aanrader):** klik op de badge hierboven.  
**Lokaal:**
```bash
python -m venv .venv
# macOS/Linux:
source .venv/bin/activate
# Windows (PowerShell):
# .venv\Scripts\Activate.ps1
pip install notebook
jupyter notebook
```
Open `if_else_en_lists_stemrecht.ipynb` en voer cellen van boven naar beneden uit (`Shift+Enter`).

## Bestanden
- `if_else_en_lists_stemrecht.ipynb` — de notebook
- `README.md` — deze uitleg
- Optioneel: `.gitignore` met:
  ```
  .ipynb_checkpoints/
  .DS_Store
  ```

## Tip voor nette commits
Leeg outputs vóór committen (kleinere diffs):
```bash
jupyter nbconvert --clear-output --inplace if_else_en_lists_stemrecht.ipynb
```

## Licentie
Deze repository is gelicentieerd onder de **MIT-licentie**. Zie het bestand [`LICENSE`](LICENSE) voor de volledige tekst.
