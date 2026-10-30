# Script Identifier

🔗 [Open App](https://tgm-hub.github.io/script-identifier-geoguessr)
💻 [GitHub Repository](https://github.com/TGM-hub)

## What it does

Read a sign, name the language. 78 languages in 14 clusters of look-alikes:
Cyrillic · Slavic (Latin) · Baltic · Nordic & Finnic · Germanic · Romance · Other European Latin · Latin outside Europe ·
Greek & Caucasus · Arabic, Urdu, Hebrew · North India & Bengal · South India & Sri Lanka · South-East Asian · East Asian.

- Variants of one script are separate answers (Hindi / Marathi / Nepali, Bengali / Assamese, Arabic / Urdu / Persian,
  Serbian Cyrillic / Macedonian…), each with the letters that prove it (ळ Marathi, ৰ ৱ Assamese, ў Belarusian).
- **Can't tell — pick two** (key `0`): when the text really cannot decide (भारत could be Hindi, Marathi or Nepali),
  naming both is full credit; if one was right but the text did decide, half credit.
- **GeoGuessr countries only** hides languages with no coverage; **As often as in GeoGuessr** draws languages by how
  often their countries come up (same frequency tiers as City Placer, read from its settings).
- "Full sign" text can show two or three panels: extra signs are added until one carries a decisive letter, as you would pan around.
- Map rounds for Indic scripts: place the language on the map, with the major cities drawn for orientation (more appear as you zoom).
  With one or more groups selected, every zone of those groups is clickable (Settings → Map rounds).
- **Map** (study mode): every group, with its cheat sheet, one card per language (where, the rule, its letters, real sample text)
  and a map; tap a card to light up its area and its cities. **Practise this group** starts a drill on it.
- After each answer: what proves it, what only narrows it, what it never has, and the cluster's cheat sheet.

Progress is kept in the browser (`localStorage`, key `signreader.v2`).
