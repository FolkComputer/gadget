# gadget
🔦

Very tentative design. Sort of minimum viable design to prototype
handheld interactions.

Open-back until it's more stable (sometimes you want to replug
the projector, sometimes you want to plug in a USB keyboard to
manually reconfigure if it's off Wi-Fi)

## Bill of materials

### 3D prints

- Gadget chassis
  - This prints in 2 parts: Chassis and front panel
- Handle grip with trigger button (in vendor/)
  - This prints in 3 parts so far: Main grip, thumbwheel, block
  - (Trigger inset itself is TODO)

(can view in https://3dviewer.net -- the .shapr file is canonical /
used to edit, the derived files are generated from it)

### Electronics

- Ultimems HD305D1-C1 (recommended) or Nebra AnyBeam (should fit)
  - There is a newer Ultimems unit [HD309D1-C1](https://raspberry-pi.ksyic.com/main/index/pdp.id/1053/pdp.open/1053) which I haven't tested yet
- Raspberry Pi 5
  - (only the Pi 5 is guaranteed to supply the 5V1.1A
    over USB port to power the projector)
  - microSD
  - 27W Pi 5 USB-C power supply
    - (you cannot use an off-the-shelf USB-C power supply; you must
      use this one)
    - TODO: battery system
- Pi wide angle camera module 3 (not noir) (? need to test)
  - Pi camera ribbon cable (special, not the one that comes with
    camera? Pi 5 has narrower MIPI ports)

### Cables

- [USB-C male-to-female 180-degree angle
  adapter](https://www.amazon.com/gp/product/B0BXCTRN7F?ie=UTF8&psc=1)
  - <img src="doc/usbc-180.jpg" height="60">
- [20cm USB-C male-to-female extension cable with panel-mount screw
  hole](https://www.amazon.com/gp/product/B075P2FF7L?ie=UTF8&psc=1)
  - <img src="doc/usbc-ext.jpg" height="60">
- [7.5cm 65W USB-C Type C to USB-C Ultra Slim Flat Power USB2.0 Data Angled
Cable](https://www.amazon.com/gp/product/B0D25V9QYG?ie=UTF8&th=1)
  - (to power projector from Pi)
  - <img src="doc/usbc-short-1.jpg" height="60"> <img src="doc/usbc-short-2.jpg" height="60">
- short microhdmi to hdmi ribbon cable

### Other

- 4x M2 bolts for camera
  - 4x M2 nylock nuts for camera
- 4x M2.5 bolts for pi 5
  - 4x M2.5 standoffs for pi 5
- 2x M2.5 bolts for front panel
  - 2x M2.5 heat set insert for front (to bolt front panel onto)
- 1x 1/4 in bolt for top
- 1x 1/4 in heat set insert for bottom

