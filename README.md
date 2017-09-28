# Serious Templates
This repository provides KiCAD templates developed by employees of the [seriöse Gesellschaft ](https://serioese.gmbh).

## [ESP32-D2WD](http://esp32.net/#Hardware)
This is supposed to be a template for the new (28-09-2017) 2.4 GHz Wi-Fi with
16Mibit (2MiB) of integrated flash. The template sports the necessary bypass
capacitors, the RF filter and a SMD Antenna.

Most of the parts are found in [Seeedstudio OPL](https://www.seeedstudio.com/opl.html).

The files in this template depend on our
[ESP32 foorprints](https://github.com/serioeseGmbH/ESP32-kiCAD-Footprints) and
[Seeedstudio OPL](https://github.com/serioeseGmbH/OPL_Kicad_Library) repositories.
To reduce redundancy we omitted from including them as a submodule in this repository.
Please clone them yourself and include them in KiCAD.
