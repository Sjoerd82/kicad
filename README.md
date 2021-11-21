# kicad
Personal KiCad repository for KiCad 5

kicad-library		Symbol library
kicad-footprints	Footprints
kicad-template		Board Templates

## Usage
### Symbols
Symbol Library Editor
 > Add Library > Browse to the .lib file > Open > Add as Global
 
### Templates
KiCad
 > Preferences > Configure Paths... > KICAD_USER_TEMPLATE_DIR > Edit > Set Value to kicad-template path

### Footprints
Footprint Library Editor
 > Preferences > Manage Footprint Libraries... > Add a record to the "Global Libraries" tab:
 
 Active: Check
 Nickname: MyFootprints (or whatever)
 Library path: Point to the kicad-footprints directory
 Plugin Type: KiCad
 