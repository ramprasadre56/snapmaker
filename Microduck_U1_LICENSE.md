# Microduck_U1.3mf — credits and license

`Microduck_U1.3mf` is an OrcaSlicer project for the Snapmaker U1 built from the
Microduck 3D models by **Pollen Robotics**:
https://github.com/pollen-robotics/microduck_rl

The original models are licensed under
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

**Changes made:** the simulation meshes in `src/mjlab_microduck/robot/microduck/assets/`
were scaled from metres to millimetres, re-oriented flat for printing, and arranged
onto Snapmaker U1 build plates with print settings. No geometry was edited.

This adaptation is shared under the same license, **CC BY-NC-SA 4.0** — non-commercial use only.

## What's in the project

| Plate | Material | Contents |
|---|---|---|
| 1–3 | PLA (slot 1) | Main walking-robot parts |
| 4 | TPU 95A (slot 4) | jaw_soft, soft_mouth_top, sole_left, sole_right, 4 × tire |
| 5 | PLA (slot 1) | Optional roller-skate kit: 2 × roller_blade, 4 × rim, ankle_l_v1, ankle_r_v1 |

Settings: 0.20 mm layers, 3 walls, 20% infill, tree supports (off for TPU parts).
Open it in OrcaSlicer 2.5+ with **File → Open Project**.
