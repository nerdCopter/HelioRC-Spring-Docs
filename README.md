# HelioRC Spring Docs
* "Documentation" for Helio Spring FC's

### Recommended resources:
* https://fpv-flightclub.com/proton-long-range-drone/
* https://fpv-flightclub.com/6s-quadcopter-build/

### Images and Wiring Diagrams in the folders
* Spring-V1
* Spring-V2
* Spring-AIO
* Spring-Mini

### Helio RC Youtube
* https://www.youtube.com/c/HelioRC/videos

### Soft-Bricked FC
* If IMUF flash went wrong, plugin USB and wait 5 full minutes for recovery and re-flash IMUF.
* If cannot enter DFU mode, temporarily short-circuit the "boot" pads while plugging in USB, it should enter DFU.

### Unable to flash flight-firmware via Configurator
* RX and USB both use same resources -- recommend soldering RX positive to 5v rail to avoid the need to disconnect RX.

### HelioRC / ButterFlight is defunct
* [EmuFlight](https://github.com/emuflight) flight firmware supports the HelioRC Spring FC and derivatives.
