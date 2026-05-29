bitaxeProto miner with quad Block Proto MC3 ASICs
![](doc/render.png)

It is still an untested prototype! Don't build this expecting it to work yet.


- [Open Hardware License](LICENSE); Real Open Source.
	- [KiCAD](https://kicad.org) design files. 
- Four Proto MC3 ASICs, two stacks of two ASICs
	- Each MC3 is nominally 1.12V with approx 675 GH/s.
- 11-13V XT30 input voltage
- TPS546D24S single-phase voltage regulator tuned for 2.4V output @ 30A
	- The voltage regulator backside power plane is exposed to hopefully thermally bond it with the main heatsink.
- TPS546D24 backside busbar to cool the voltage regulator from the main heatsink.
- Fan controlled from the ESP32
- ESP32S3 for [esp-miner](https://github.com/bitaxeorg/esp-miner) support.
- Display moved off the main board. Should support the [bonanzaDisplay](https://github.com/bitaxeorg/bonanzadisplay)
- Gerbers _not_ provided to discourage side hacks and AliEx slop. HMU if you need help generating gerbers with KiCad.

©️ [bitaxeorg](https://bitaxe.org)