# BOAT APP

Florida vessel intel desk for CaseClosed Scout.

**Preview the app:**
https://htmlpreview.github.io/?https://github.com/ABBYCRM/BOAT-APP/blob/main/index.html

Repo: https://github.com/ABBYCRM/BOAT-APP

## Run it
Open `index.html` in any browser. No build step. Autosaves locally.

## What it does
- Input HIN, FL number, title number, year/make/model, length, engine, case notes
- Decode HIN (MIC, builder, serial, month, model year) per 33 CFR 181
- Normalize Florida registration numbers (`FL 1234 AB`)
- Classify vessel length and show Florida registration fee band
- One-tap official lookups: MVCheck, HSMV 90510, PSIX, NVDC, J.D. Power (former NADA), Boat Trader, FDLE stolen boats, NICB
- Capture title status, liens, book values, market comps
- Owners-in-order fields after the $1 title-history printout
- Export JSON / print / copy the full packet

## What it cannot do
Florida owner names are restricted by the Driver Privacy Protection Act. This app does not scrape owner PII. Owners in order come from Form HSMV 90510 Title History Printout ($1).

NADA Guides marine is now J.D. Power. Values are captured from the official catalog.

Not a law firm. No legal advice.
