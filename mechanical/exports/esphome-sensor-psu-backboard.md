# ESPHome Sensor PSU Backboard

## Overview
The PSU backboard is a 3D printed mounting and protection component for the power supply unit of the ESPHome sensor boards. It provides structural support, cable management, and safety isolation for the power electronics.

## Design Decisions

### Structural Design
- **Material**: Designed for PETG printing for outdoor use
- **Wall Thickness**: 4 loops for mechanical strength and heat inserts
- **Mounting Points**: Standardized mounting holes compatible with polycarbonate enclosure
- **Cable Management**: Integrated strain relief cable tie connection points for cables
- **Fixings**:  Insert diameter of 3.9mm with 0.2mm chamfer
- **Fillets**:  2mm main board, 1mm everything else

### Safety Considerations
- **Isolation**: Covered terminals to prevent accidental contact with AC power components  
- **Ventilation**: Not needed, low dissapation @250ma fused
- **Fuse Access**: Accessible fuse holder mounting for easy maintenance

## Print Settings

### Recommended Settings
- Default on Bambu Labs P2S for PETG-HF (calibrated flow rate defaults)

### Print Orientation
- **Recommended Orientation**: Backboard flat, fuse holder and terminal copvers on the side
- **Support Material**: None
- **Build Plate Adhesion**: None

### Quality Settings
- **Walls**: 4
- **Top/Bottom Layers**: 5
- **Ironing**: Top surfaces
- **Ironing speed**: 15mm/s
- **Ironing flow**: 20%
- **Ironing line spacing**: 0.08mm

## Assembly Notes

### Required Hardware
- Bambu Lab PETG HF
- M3 Threaded Inserts for plastic M3xL4xD4.2 - https://www.amazon.com.au/dp/B0BBSLL6G7
- Meanwell 30W 12V 2.5A Mini Power Supply - https://www.jaycar.com.au/30w-12v-2-5a-mini-power-supply/p/MP3302
- 250VAC 10A M205 Panel Mount Fuse Holder - https://www.jaycar.com.au/250vac-10a-m205-panel-mount-fuse-holder/p/SZ2030
- 250mA M205 Quick Blow Fuse 250VAC - https://www.jaycar.com.au/250ma-m205-quick-blow-fuse-250vac/p/SF2154
- 6 Amp 12-way Screw Terminal Strip - https://www.jaycar.com.au/6-amp-12-way-screw-terminal-strip/p/HM3194
- Polycarbonate Enclosure with Flange 171 x 121 x 80mm - https://www.jaycar.com.au/polycarbonate-enclosure-with-flange-171-x-121-x-80mm/p/HB6221

### Assembly Sequence
- Soldering Iron at 250C for inserts

## Version History

## Design Files
- **Source**: `mechanical\fusion360\esphome-sensor-psu-backboard.f3d` (Fusion 360)
- **Backboard Export**: `mechanical\exports\esphome-sensor-psu-backboard[-vx].stl`
- **Fuse Holder**: `mechanical\exports\esphome-sensor-psu-fuse_holder[-vx].stl`
- **Terminal Covers**: `mechanical\exports\esphome-sensor-psu-terminal-cover[-vx].stl`
