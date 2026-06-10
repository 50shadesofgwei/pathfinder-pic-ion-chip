# Pathfinder PIC Ion Chip

CAD model for the Pathfinder PIC chip, a photonic-integrated trapped-ion chip built to support a hybrid-locality quantum computing architecture.

## Architecture overview

Two planar ion-trap arrays sit above a silicon-nitride photonic integrated circuit. Each array holds a 3-ion <sup>138</sup>Ba<sup>+</sup> Coulomb crystal:

- one **communication ion** that interfaces with the photonic network
- two **memory ions** that store computational states

The chip combines two forms of entanglement:

- **Local** entanglement inside each array, using motional Mølmer–Sørensen (MS) gates
- **Non-local** entanglement between arrays, using photon-mediated time-bin entanglement and teleportation

## Repository contents

| File | Description |
| --- | --- |
| `Ba138_v2.f3d` | Autodesk Fusion 360 source file for the chip |

## Opening the file

`.f3d` is the native Autodesk Fusion 360 format. To open it:

1. Open Fusion 360
2. File → Open → From My Computer
3. Select `Ba138_v2.f3d`

A read-only viewer is available via the Autodesk Viewer (https://viewer.autodesk.com).

## Status

This design is an early-stage sketch; exact powers, waists, crosstalk budgets, and many fabrication-level details are still being worked out. Feedback from PIC designers and trapped-ion experimentalists is welcome and encouraged.

## Contact

Jonathan Feasby — Pathfinder Quantum Technologies
