# 🎧 DMA-Pcileech-CreativeSoundBlaster

This project was a passion a passion project developed by me and utilises a Creative Sound Blaster sound card as the donor device utilising the **PCILeech framework**. This project is intended for developers, hardware hackers, and researchers interested in DMA (Direct Memory Access) attack surfaces, hardware debugging, or low-level OS and driver development.


This project is strictly for Educational Purposes Only!
---

## ⚙️ Project Overview

This repository aims to:

- Interface with **Creative Sound Blaster cards** via PCILeech.
- Explore memory-mapped registers and behavior of Sound Blaster devices.
- Document findings from reverse engineering efforts.
- Provide code for interacting with the hardware in real-time via DMA.

This project leverages the PCILeech platform to access PCIe devices from a separate system via DMA, enabling analysis without OS interference.
This allows read/write memory functions bypassing the CPU via a pci DMA Card.

---
## 🛠 Features

- **Zero4k.coe file correctly filled out for correct driver loading.**
- **1:1 Config Space of real device**
- **Full Emulation of the original device**
