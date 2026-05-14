# Eurorack-2164-Quad-Exponential-VCA

A Eurorack Quad Exponential VCA module based on the AS2164 chip (Electric Druid, drop-in replacement for the SSI/SSM 2164).

## Features

- 4 independent exponential VCAs
- Normalled signal chain: I1→I2→I3→I4 (signal in jack 1 routes to all VCAs unless overridden)
- Normalled CV chain: CV1→CV2→CV3→CV4 (one CV controls all unless overridden)
- Unity gain at 0V CV; ~100 dB attenuation at +5V CV (post-inversion stage; chip is fed inverted)
- ±12V Eurorack power

## Schematic

- Latest: **Rev 0.1.4** — [PDF](Schematic%20PDFs/Eurorack-2164-Quad-Exponential-VCA-Schematic-Rev0.1.4.pdf)
- All revisions: [Schematic PDFs/](Schematic%20PDFs/)

## Hardware

- KiCad project: [kicad/](kicad/)
- 3D-printed front panel STL: [3D printed front panel/](3D%20printed%20front%20panel/)
- Falstad simulations: [falstad/](falstad/)

## References

- [SSI2164 datasheet](https://www.amazingsynth.com/parts/ssi2164/ssi2164-datasheet.pdf)
- [Analog Devices SSM2164 datasheet](https://www.analog.com/media/en/technical-documentation/data-sheets/SSM2164.pdf)
- Design inspiration: [Intellijel Quad VCA](https://intellijel.com/shop/eurorack/quad-vca/), [Hagiwo Dual log/lin VCA](https://note.com/solder_state/n/n14a8be5f7118)

## Build status

What's ready for builders today, and what's still on the TODO list:

**Production assets** (what you need to actually fabricate and assemble a final unit)

- [x] Schematic — Rev 0.1.4 ([Eurorack-2164-Quad-Exponential-VCA-Schematic-Rev0.1.4.pdf](Schematic%20PDFs/Eurorack-2164-Quad-Exponential-VCA-Schematic-Rev0.1.4.pdf))
- [ ] PCB layout — in progress — single working layout in `kicad/`, not yet separated for fab
- [ ] Gerber files for fabrication — none yet
- [ ] BOM — none yet
- [ ] Final front panel (SVG/PDF for fab) — none yet
- [ ] License — none yet

**Prototype assets** (for breadboard / perfboard / 3D-printed-panel builds before final PCB)

- [x] 3D-printed prototype panel STL — [2164_Quad_VCA.stl](3D%20printed%20front%20panel/2164_Quad_VCA.stl)

**Documentation**

- [ ] Photos of the assembled module — none yet
- [ ] Demo video — none yet
- [ ] Build / assembly instructions — none yet
- [ ] Calibration / tuning notes — none yet

Want to help fill a gap (build photos, gerbers, an assembly guide)? Open an issue or PR.
