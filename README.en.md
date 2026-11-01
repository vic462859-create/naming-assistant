# naming-assistant · Chinese Name Generator

A skill for Chinese naming / renaming / name review / courtesy-name (表字) suggestion, built on a **dual-track system**.

## What it is

- **Aesthetic track** (surname typology): four archetypes × three principles (虚/实, 动/静, 同/异) determine the "temper" of a name
- **Cultural track** (BaZi / 五行): traditional folk reference for the Five-Element balance of a given birth chart — presented as a cultural framework, not a fortune-telling promise
- **Uniqueness mechanism**: differentiated anchors × character-tiering × structure diversity × sibling-name design, to avoid same-pattern collisions
- Six-layer validation (phonetics, aesthetics, tradition, uniqueness, dialect) before output

## Coverage

- ~115 common surnames + ~50 tricky surnames (polyphonic / compound / rare) in direct lookup
- Any other surname: on-the-fly judgment card (3-step method)
- Dialect taboo check for Cantonese, Wu, etc.

## Files

- `SKILL.md` — 7-step workflow + output template
- `references/` — 11 methodology files (surname taxonomy/roster, character vault, BaZi reference, case library, tradition dimensions, courtesy-name guide, uniqueness guide, dialect taboo, method library)

## Usage

Say "起名 / 取名 / 改名 / 点评名字 / 补字" to trigger. Three modes: generate a name list, review an existing name, or add a courtesy name (字) in the traditional 名·字·号 system.

## License

This work is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License** (CC BY-NC 4.0). The method library (`references/method-library.md`) is compiled from publicly available naming content; its copyright belongs to the original authors. The rest (typology, uniqueness mechanism, courtesy-name guide, cultural dimensions) is original.
