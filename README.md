# Burr Action demo

Real STEP assemblies and PRs demonstrating
[`fraylabs/burr-action@v1`](https://github.com/fraylabs/burr-action).

The workflow checks changed STEP files, fails on interference or unresolved
geometry, uploads the JSON reports, and updates one comment as GitHub Actions.

## Assembly sources and licenses

These models are redistributed in their original STEP source form. They are
licensed separately from the workflow and documentation.

| File | Original source | License |
| --- | --- | --- |
| `models/manta-mount.step` | [VoronDesign/Voron-0, Manta M4P DIN mount](https://github.com/VoronDesign/Voron-0/blob/a53fc87562fd630c846af38d7de850c894dc3d85/CAD/Electronics%20Mounts/Manta_M4P_Din_Mount_2pc.step) | GPL-3.0; [full license](licenses/Voron-GPL-3.0.txt) |
| `models/openamr-cover.step` | [openAMRobot/openamr-platform-hw, cover assembly](https://github.com/openAMRobot/openamr-platform-hw/blob/9703a5f13ffc009db8ff3fa979470179afe3d26b/mechanical/cad/production_files/MMP.01.00.00.000%20Cover%20assembly.STEP) | CERN-OHL-P-2.0; [full license](licenses/openamr-CERN-OHL-P-2.0.txt) |

Copyright remains with the original authors. License texts permit redistribution
with their notices and source; the STEP source and original source links are
included here. Modified demo variants identify their changes in their PR.
