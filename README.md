# npmx
## Overview
npmx is a set of drivers for peripherals present in Nordic Semiconductor's Power Management ICs (PMICs).

For the user's convenience, the drivers come with the MDK package. This package contains definitions of register structures and bitfields for PMICs.

## Supported devices

* nPM1300 Engineering B

## Directories
```
 .
 ├── backends        # npmx backend files
 ├── doc             # Project documentation files
 ├── drivers         # npmx driver files
 │   ├── include     # npmx driver headers
 │   └── src         # npmx driver sources
 ├── mdk             # nPM MDK files
 ├── templates       # Templates of npmx integration files
 └── zephyr          # Zephyr integration files
```