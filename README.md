# aggregat 02 IOControls PCB

User interface peripheral board.

For project info see: https://gitlab.zhdk.ch/aggregat-02/a01-firmware


https://gitlab.zhdk.ch/aggregat-02/a01-pcb-iocontrols

## License

This work is licensed under a Creative Commons Attribution 4.0 International License (CC BY 4.0)

## Revisions

### v1.2

- Replaced small footprint molex connectors with regular 1.00" pin headers.

### v1.1

- fixed not connected 3V3 between DIP switches
- fixed not connected button to GPIO line
- **BREAKING CHANGE** corrected CN3 connector pin assignment to fit with NUCLEO out connector (also see schematics)

## Bill of Materials

Number | Item | Cost per (10/100) Unit(s)  | Cost
--- | --- | --- | ---
1 | PCB Prototype (https://www.pcbway.com/) | 25.00* (10) | 2.50
1 | [DIP Switch SPST 8 Through Hole](https://www.digikey.ch/product-detail/en/78B08ST/GH7192-ND/726250) | 1.26 | 1.26
2 | [DIP Switch SPST 4 Through Hole](https://www.digikey.ch/product-detail/en/78B04T/GH7185-ND/726243) | 1.06 | 2.12
1 | 1 Pin header | |
1 | 2 Pin header 1.00" |  |
2 | 15 Pin header 1.00" |  |
8 | [SMD Res 270Ohm 1% 1/8W 0805 (2012 Metric)](https://www.digikey.ch/product-detail/en/CR0805-FX-2700ELF/118-CR0805-FX-2700ELFCT-ND/10673809) | 2.67 (100) | < 1.00
19 | [SMD Res 330Ohm 1% 1/8W 0805 (2012 Metric)](https://www.digikey.ch/product-detail/en/CRG0805F330R/A106061CT-ND/3477707) | 1.82 (100) | < 1.00
8 | [SMD Res 47kOhm 1% 1/8W 0805 (2012 Metric)](https://www.digikey.ch/product-detail/en/RC0805FR-0747KL/311-47.0KCRCT-ND/730920) |  1.49 (100) | < 1.00
27 | [SMD Res 100kOhm 1% 1/8W 0805 (2012 Metric)](https://www.digikey.ch/product-detail/en/RC0805FR-07100KL/311-100KCRCT-ND/730491) |  1.49 (100) | < 1.00
19| [SMD Cap 0.1uF 10% 6.3V 0805 (2012 Metric)](https://www.digikey.ch/product-detail/en/C0805C104K9RACTU/399-9155-6-ND/3523226) | 7.65 (100) | < 1.00
8 | [Bipolar (BJT) Transistor NPN 40V 800mA SOT-23-3](https://www.digikey.ch/product-detail/en/BSR14/BSR14CT-ND/965560) | 7.37 (100) | < 1.00
4 | Tactile switches |
8 | LEDs ~2 20mA | | ~2.00

* Delivery (~25.00) not included

Total material cost ~< 20.-
