[![Version: 1.0 Release](https://img.shields.io/badge/Version-1.0%20Release-green.svg)](https://github.com/0x007e/xol) ![Build](https://github.com/0x007e/xol/actions/workflows/release.yml/badge.svg) [![License CC By-NC-SA](https://img.shields.io/badge/Hardware-CC--BY--NC--SA--4.0-lightgrey)](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)

# `XOL` - XOR Logic Board

The `XOL` is a board with an [CD4070](#additional-information) or any other 4-channel `XOR` gate driver that meets the pin requirements. The board itself can be driven from `5` to `15V`. The board offers the possibility to `XOR` signals from buttons, switches or any other logic board.

| Experience  | Level                                                                               |
|:------------|:-----------------------------------------------------------------------------------:|
| Soldering   | ![?%](https://progress-bar.xyz/20?progress_color=00ff00&suffix=%20Medium&width=120) |

# Downloads

| Type      | File                                                                                                                                                 | Description     |
|:---------:|:----------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------|
| Schematic | [pdf](https://github.com/0x007E/xol/releases/latest/download/schematic.pdf) / [cadlab](https://cadlab.io/project/30238/main/files)                   | Schematic files |
| Board     | [pdf](https://github.com/0x007E/xol/releases/latest/download/pcb.pdf) / [cadlab](https://cadlab.io/project/30238/main/files)                         | Board file      |
| Drill     | [pdf](https://github.com/0x007E/xol/releases/latest/download/drill.pdf)                                                                              | Drill file      |
| PCB       | [zip](https://github.com/0x007E/xol/releases/latest/download/kicad.zip) / [tar](https://github.com/0x007E/xol/releases/latest/download/kicad.tar.gz) | KiCAD/Gerber/BoM/Drill files |
| Mechanical | [zip](https://github.com/0x007E/xol/releases/latest/download/freecad.zip) / [tar](https://github.com/0x007E/xol/releases/latest/download/freecad.tar.gz) | FreeCAD/Housing and exported step/stl files |

# Hardware

The pcb is created with `KiCAD`. All files are built with `github actions` so that they are ready for a production environment.

## PCB

The circuit board is populated on both sides (Top, Bottom). The best way for soldering the `SMD` components is within a vapor phase soldering system and for the `THT` components with a standard soldering system.

### Top Layer

![Top Layer](https://github.com/0x007E/xol/releases/latest/download/top.kicad.png)

### Bottom Layer

![Bottom Layer](https://github.com/0x007E/xol/releases/latest/download/bottom.kicad.png)

# Additional Information

| Type       | Link                                                  | Description                                 |
|:----------:|:-----------------------------------------------------:|:--------------------------------------------|
| CD4070    | [pdf](https://www.ti.com/lit/ds/symlink/cd4070b.pdf)   | CMOS XOR Gate                               |

---

R. GAECHTER
