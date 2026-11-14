# RP1 Hardware

English | [简体中文](README_CN.md)

Hardware design and manufacturing files for the RoboParty RP1 humanoid robot: mechanical parts, PCB production data, wiring harnesses and bills of materials.

![RP1 front, side and rear views](assets/images/robot-overview.png)

## Documentation

[Hardware architecture (PDF)](00_Docs/RP1_Hardware_Architecture.pdf)

| Resource | Contents |
| --- | --- |
| [Mechanical files](01_Mechanic/README.md) | SolidWorks sources, editable drawings, Parasolid model and manufacturing files |
| [PCB files](02_PCB/README.md) | Board BOMs, Gerbers, placement data, 3D models and fabrication requirements |
| [Wiring harnesses](03_Harness/README.md) | Harness BOM, drawings and assembly requirements |
| [Robot BOMs](04_BOM/README.md) | Part numbers and quantities for each configuration |

### Robot configurations

| Configuration | BOM |
| --- | --- |
| 5DOF + MotionHead | [RP1.3.4 （五自由度+运控头）BOM表.xlsx](<04_BOM/RP1.3.4 （五自由度+运控头）BOM表.xlsx>) |
| 7DOF + MotionHead | [RP1.3.4 （七自由度+运控头）BOM表.xlsx](<04_BOM/RP1.3.4 （七自由度+运控头）BOM表.xlsx>) |

## CAD Downloads

| File | Contents |
| --- | --- |
| [RP1_SolidWorks_Source.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_SolidWorks_Source.zip) | SolidWorks assembly and part source files |
| [RP1_Parasolid_Model.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Parasolid_Model.zip) | Parasolid whole-robot model (.x_t) |
| [RP1_Drawings.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Drawings.zip) | Editable SolidWorks drawings (.SLDDRW) |

Extract the source archive and open `RP1_SolidWorks_Source/RP1.3.4整机.SLDASM`. Keep the source files together. For drawing editing, place the `.SLDDRW` files from `RP1_Drawings` beside their corresponding source models.

## Drawing Previews

### CNC part drawing · YCL.M000642

![YCL.M000642 upper-arm body machining drawing](assets/images/cnc-part-drawing.png)

### BACKHUB PCB layout

[![BACKHUB V2.1 component placement drawing](assets/images/pcb-layout.png)](02_PCB/12_RBE_PWR_BACKHUB/06_PCB_PDF_BACKHUB_V2.1.pdf)

[Open the board drawing (PDF)](02_PCB/12_RBE_PWR_BACKHUB/06_PCB_PDF_BACKHUB_V2.1.pdf)

### BODY01 wiring harness

[![BODY01 wiring harness drawing](assets/images/harness-drawing.png)](03_Harness/Drawings/RP1-BODY01-0线材.pdf)

[Open the harness drawing (PDF)](03_Harness/Drawings/RP1-BODY01-0线材.pdf)

## Contributing

Found a file error or have a design improvement? Open an [issue](https://github.com/Roboparty/rp1_hardware/issues) with the part number or board revision and the relevant file path.

## License

RoboParty-owned hardware designs are licensed under [CERN-OHL-W-2.0](LICENSE). Documentation is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Third-party files retain their original terms. See [LICENSES.md](LICENSES.md) for the scope of each licence.
