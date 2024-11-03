# dSIB-Si

Design files for dSIB-Si board in Altium Designer format.

This board attaches to the HD15 and HD26 connectors on the rear of the dVRK-Si controller, which are mounted on the [DRAC PCB](https://github.com/jhu-dvrk/drac) inside the controller.

It provides the connectors for interfacing to the active arm (PSM or ECM) and the brakes for the corresponding SUJ.

Currently, the SUJ potentiometers are not handled by this board, and instead are sent via Bluetooth from the [dESSJ boards](https://github.com/jhu-dvrk/dESSJ-pcba) to the PC.

This board contains an STM32 microprocessor. The firmware is in the [dSIB-Si-firmware](https://github.com/jhu-dvrk/dSIB-Si-firmware) repository.

For more information, see the [dVRK Si SUJ documentation](https://dvrk.readthedocs.io/en/latest/pages/setup/Si/SUJ.html).
