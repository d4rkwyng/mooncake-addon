# Mooncake Shitty Addon

A #badgelife shitty addon PCB inspired by Mooncake from Final Space, designed for DEF CON 26.

Created by @d4rkwyng. Thanks to [AND!XOR](https://www.andnxor.com/) and SparX for their help with this project.

## Preview

| Front | Back |
|:-:|:-:|
| ![Front](design/example/front.png) | ![Back](design/example/back.png) |

## Bill of Materials

| Ref | Component | Package | Qty |
|-----|-----------|---------|-----|
| U1 | MCP23017 | SOIC28 | 1 |
| D1-D10 | LED | 1206 | 10 |
| R1-R10 | 220 ohm | 1206 | 10 |
| C1 | 0.1uF | 1206 | 1 |
| X1 | Shitty connector | 2x2 | 1 |

## Revisions

- **Rev C** — Final revision with ESO variant
- **Rev B** — Updated layout and routing
- **Rev A** — Initial prototype

## Project Structure

```
mooncake-addon/
├── design/          # Artwork, silkscreen, and soldermask KiCad footprints
├── gerbers/         # Manufacturing files (Rev B, C, and C ESO)
├── lib/             # KiCad component libraries
└── mooncake_*       # Schematic, PCB, and netlist files
```

## Tools

- [KiCad](https://www.kicad.org/) — Schematic and PCB design

## License

MIT License. See [LICENSE](LICENSE) file.
