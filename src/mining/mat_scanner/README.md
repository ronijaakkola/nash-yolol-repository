# Material Scanner
This script reads values from the material scanner device and displays them on a text panel. This script only shows the most valuable material of the scan array. The amount is shown both in kv and stack amount.

## Prerequisites
### Devices
- YOLOL chip (basic)
- YOLOL socket or rack
- Material point scanner
- Text panel 24×24
- Hybrid button

## Installing
### Device fields
Device | Device field | Field name
------------ | ------------- | ------------- |
Material scanner | Active | Scan
Material scanner | Index | I
Material scanner | ScanResults | R
Material scanner | Material | M
Material scanner | Volume | V
Material scanner | Scan | S
Hybrid button | ButtonState | Scan
Text panel | PanelValue | LastScan

### Installation
1. Install all devices to your ship. They must be connected to the same network.
2. Rename needed device fields. See the table above.
3. Press the scan button

## Known issues
- The material scanner often returns the same results 1-3 times after the beam hits something else. This seems to be a bug in the game.

## Authors
Nash#0197

