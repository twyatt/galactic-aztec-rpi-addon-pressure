# About
[![OSHPark PCB Top Thumbnail](artwork/thumb_top.png?raw=true)](artwork/top.png?raw=true)
[![OSHPark PCB Bottom Thumbnail](artwork/thumb_bottom.png?raw=true)](artwork/bottom.png?raw=true)

Custom Raspberry Pi Add-on board used as a pressure transducer interface board for the [Galactic Aztec] rocket. The board has a single JST XH port for power input (Supply Voltage), 4 ethernet ports for interfacing with custom [pressure transducer connector boards] and 2 header pin ports (pressure transducer stepped-down voltage output) for optional ribbon cable connectivity.

The ethernet ports adhere to the following [T-568B] wiring configuration:

| Pin | Color        | Function       |
|:---:|:------------:|:--------------:|
| 1   | Orange/White | Signal         |
| 2   | Orange       | Signal         |
| 3   | Green/White  |                |
| 4   | Blue         | Supply Voltage |
| 5   | Blue/White   | Supply Voltage |
| 6   | Green        |                |
| 7   | Brown/White  | Ground         |
| 8   | Brown        | Ground         |

For the [Galactic Aztec April 18th, 2015 launch], the following pressure transducers were used:
* 3 x [P51-500-A-A-I36-5V-000-000]
  * LOX, Kerosene and motor pressure
* 1 x [MSP-300-2K5-P-4-N-1]
  * Helium pressure

Custom EagleCAD parts on this board can be found in the [SDSU Rocket Eagle Libraries].

# Bill of Materials
| Qty | Description                               | Part Number       | Vendor   |
|:---:|-------------------------------------------|------------------:|----------|
| 4   | Jack RJ45 CAT5/CAT5e                      | [380-1046-ND]     | DigiKey  |
| 1   | Header JST XH 2.5mm 4-pos Right Angle SMD | [455-2262-1-ND]   | DigiKey  |
| 2   | Header Male 2x5 0.1" Pitch                | [609-3236-ND]     | DigiKey  |
| 4   | Resistor 10kΩ 1/4W 1% 0603                | [P10KBYCT-ND]     | DigiKey  |
| 4   | Resistor 15kΩ 1/4W 1% 0603                | [RHM15.0KADCT-ND] | DigiKey  |
| 1   | Header Stacking 2x20 Tall 23mm            | [1979]            | Adafruit |


[Galactic Aztec]: http://rocket.sdsu.edu/rockets
[pressure transducer connector boards]: https://github.com/twyatt/galactic-aztec-pressure-transducer-connector
[T-568B]: https://en.wikipedia.org/wiki/TIA/EIA-568#Wiring
[Galactic Aztec April 18th, 2015 launch]: https://github.com/twyatt/galactic-aztec-launch-data
[P51-500-A-A-I36-5V-000-000]: http://www.ssi-sensors.com/pdfs/Pressure%20Sensors/P51/PS-AN2_FAMILY%20PRODUCT%20OVERVIEW.pdf
[MSP-300-2K5-P-4-N-1]: http://www.mouser.com/ds/2/418/MSP300-710393.pdf
[SDSU Rocket Eagle Libraries]: https://github.com/twyatt/SDSURocket-Eagle-Libraries
[380-1046-ND]: http://www.digikey.com/product-detail/en/SS-7188-NF/380-1046-ND/388308
[455-2262-1-ND]: http://www.digikey.com/product-detail/en/S4B-XH-SM4-TB(LF)(SN)/455-2262-1-ND/1651060
[609-3236-ND]: http://www.digikey.com/product-detail/en/67997-210HLF/609-3236-ND/1878541
[P10KBYCT-ND]: http://www.digikey.com/product-detail/en/ERJ-PA3F1002V/P10KBYCT-ND/5036115
[RHM15.0KADCT-ND]: http://www.digikey.com/product-detail/en/ESR03EZPF1502/RHM15.0KADCT-ND/1983758
[1979]: https://www.adafruit.com/product/1979