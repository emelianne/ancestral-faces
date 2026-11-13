# Ancestral Faces

Interactive website about animal masks in old rituals of four cultures.

- **Russia** — the Yuletide Goat of Slavic mummers · threads that ring like the **gusli**, a **balalaika** strum on the mask
- **Bulgaria** — the Kukeri · wooden pipes that sing like the **kaval**, heavy kukeri bells on the mask
- **Bali** — Barong · little bronze gongs like the **reyong**, the great gong on the mask
- **Japan** — Kitsune · **suzu** shrine bells, a **koto** phrase on the mask

## How it works

- One `index.html`: Canvas 2D, no libraries. Fonts: Anton and Inter Tight (Google Fonts).
- Masks are images generated in Higgsfield (`*.webp`, transparent background).
- Hanging decorations are chains of points with physics (Verlet), drawn in code.
- All sounds are synthesized with the Web Audio API (Karplus–Strong strings, flute, gongs, bells). Sound starts only after the button.
- Settings: volume, echo, length, density, decor, breeze, sensitivity.

## Ethics

Stylised images inspired by these traditions — not copies of museum objects. Sources are listed on the page.

Prototype by Emelianne Efremova.
