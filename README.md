# Mecha Matrix 2030

This is a WIP keyboard project aimed around approximating the layout of the
TypeMatrix 2030 keyboard using off-the-shelf components and firmware.

The goal is that this keyboard pcb, switch plate, and case will be created in
ergogen and routing will be done with tooling centered around kicad automations.

![Current progress of keyboard](assets/ergogen-current.png)

## Some relevat url's around ergogen and other tooling:

[ergogen.cache.works](https://ergogen.cache.works/)\
Visualize the generated ergogen keyboard layout in real-time

[docs.ergogen.xyz](https://docs.ergogen.xyz/)

![TypeMatrix 2030 key layout](https://i.pinimg.com/originals/62/ba/0e/62ba0eac84a6d61062809af8791b59c8.png)

[![Ben Vallack: Design Your Own Keyboard!](https://img.youtube.com/vi/M_VuXVErD6E/0.jpg)](https://www.youtube.com/watch?v=M_VuXVErD6E)

[![Ben Vallack: "The REAL Ergonomic Keyboard Endgame! - How To Design & Make A Totally Custom Keyboard"](https://img.youtube.com/vi/kbqR4sMR-ng/0.jpg)](https://www.youtube.com/watch?v=kbqR4sMR-ng)

[![Keyboard Kitchen: Ergogen and whatnot!](https://img.youtube.com/vi/UKfeJrRIcxw/0.jpg)](https://www.youtube.com/watch?v=UKfeJrRIcxw)

## GH projects centered around automating pcb design:

[soundmonster/samoklava](https://github.com/soundmonster/samoklava)\
Generated keyboard: The interesting thing about this keyboard is that it's a
declarative design:

- Layout is declared using Ergogen. New: no fork needed!
- The build system uses Ergogen to translate YAML to a KiCad PCB and plate files
  for FR-4 fab or laser cutting
- uses kicad-automation-scripts and FreeRouting to automatically route the
  traces on the PCB
- uses KiKit to render PCB previews (see top of this file) and production-ready
  Gerber files

[InteractiveHtmlBom](https://github.com/openscopeproject/InteractiveHtmlBom)\
Interactive HTML BOM generation plugin for KiCad, EasyEDA, Eagle, Fusion360 and
Allegro PCB designer

[KiKit](https://github.com/yaqwsx/KiKit)\
Automation tools for KiCAD

[Pinion](https://github.com/yaqwsx/Pinion)\
Generate interactive and nice-looking diagrams for your PCBs!

[KiBot](https://github.com/INTI-CMNB/KiBot)\
KiCad automation utility

[Ergogen (fork)](https://github.com/ImStuBTW/ergogen)\
Ergogen for with a few more footprints. Don't know if useful or not.

[kicad-kbdplacer](https://github.com/adamws/kicad-kbplacer)\
KiCad plugin for automatic keyboard's key placement and routing

## Kicad part libraries:

https://github.com/daprice/keyswitches.pretty

https://github.com/kiswitch/kiswitch

## Custom keycaps:

https://github.com/levpopov/LPX

https://github.com/wolfwood/printed-keycap-mods

https://github.com/braindefender/KLP-Lame-Keycaps

https://github.com/vvhg1/clp-keycaps

## Misc:

https://github.com/Zambumon/SKUF
