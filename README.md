# NEXUS 2x3 Wired Macro Pad

NEXUS is a small, wired macro pad with six keys and a tiny OLED screen. It is designed to make common computer and media controls easier to use.

## Hardware

- Six MX-style keys in two rows of three
- Hack Club Orpheus Pico 2 controller with USB-C
- 0.91-inch SSD1306 OLED display
- Custom PCB made in KiCad
- Two-piece 3D-printed case

## Example key layers

- **NEXUS:** wake the PC, open NEXUS, control the microphone, or check Jellyfin and Pi-hole/Tailscale.
- **Media:** play or pause, skip tracks, change volume, and mute.

These are planned macro uses. The final key assignments depend on the firmware and setup.

## Build status

The schematic, two-layer PCB routing, case CAD, and starter firmware are prepared. The switches use 19.05 mm pitch. A manufacturer drawing exposed an incorrect switch stack, which was corrected in the v1.2 case; nominal CAD envelopes and KiCad electrical checks were then run. See the [fit check](photos/FIT-CHECK.md) for the calculations and limitations. Physical fit, fabrication, and firmware behavior on the assembled device remain unverified.

## Files

- `bom.csv` — parts list
- `kicad/` — board design files
- `case/` — case design files
- `firmware/` — firmware source
- `NEXUS-Gerbers.zip` — files for making the PCB
- `NEXUS-Firmware.zip` — firmware package

Check the part numbers and dimensions before ordering parts or manufacturing the board.
