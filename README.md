# M926 · Renaissance

Ward-Beck Systems M926, 1994|27. Wiki page: [M926 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/WBSps.ca/Github.WardBeckSystems/MODULES.RENAISSANCE.M926/)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 9 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 4 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 3 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 2 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 13 |

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [M926.kicad_sym](KICAD/M926.kicad_sym)
- [PCB M926-1 - M926](KICAD/PCB%20M926-1%20-%20M926)

## Software

- [1994 - M926 - #ESP_OUT.txt](SOFTWARE/1994%20-%20M926%20-%20%23ESP_OUT.txt)

## 3-D model

[`MECHANICAL/M926.stl`](MECHANICAL/M926.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M926)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (assumed: 1.6" x 7" x 6.5", the common module)
- **From the drawing:** 0 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M926 - front panel.svg`)
- no drawing of the front panel: the panel is blank
- Made by `tools/module_models.py` (→ `MECHANICAL/M926.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
