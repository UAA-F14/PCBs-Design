# DC-AC Inverter (STM32-Controlled)

An inverter board with an STM32F411 handling switching control.

**Known issue:** the board outline in `Inversor.kicad_pcb` is missing/malformed (KiCad DRC flags it), so a clean 3D render isn't possible until that's fixed — no render included here yet, just the raw files.

**Photos of the built board — coming soon**

## Files
- `Inversor.kicad_sch` / `.kicad_pcb` / `.kicad_pro` — KiCad design
- `firmware-STM32F411/` — STM32F411 firmware (Core sources + .ioc)

## Credit
Built as coursework with [DasReyxr](https://github.com/DasReyxr) — original project history in [DasReyxr/HW-Projects](https://github.com/DasReyxr/HW-Projects). This copy is curated separately with a proper writeup and renders.
