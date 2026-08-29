# Buck Converter (24 V &rarr; 120 V design exam)

## Directory structure
```
├── design
│   ├── KicadDesign
│   │   ├── Design.kicad_pcb
│   │   ├── Design.kicad_pro
│   │   ├── Design.kicad_sch
│   └── Schematic.pdf
├── README.md
├── render
│   └── render.png
├── scripts
│   └── 5-5 ExamenPot.wxmx
├── sim
│   └── BuckConv.ms14
└── simulation.asc
```


A buck converter built for a power electronics exam. 

![3D render](src/render.png)

**Photos of the built board — coming soon**

## Files
- `BuckConverter.kicad_sch` / `.kicad_pcb` / `.kicad_pro` — KiCad design
- `Schematic.pdf` — schematic printout
- `simulation.asc` — LTspice simulation

## Credit
Built as coursework with [DasReyxr](https://github.com/DasReyxr)  and [Kevin Lara](https://github.com/Gyonyu) — original project history in [DasReyxr/HW-Projects](https://github.com/DasReyxr/HW-Projects). This copy is curated separately with a proper writeup and renders.

## Template
```
mkdir code design doc scripts sim src
```

```
tree >> Readme.md
```