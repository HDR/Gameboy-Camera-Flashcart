## Make sure you read the License (Attribution-NonCommercial-ShareAlike 4.0 International)

[![Purchase on PCBWay](/assets/purchase-on-pcbway.png)](https://www.pcbway.com/project/shareproject/Game_Boy_Camera_Flashcart___2x1MB___FRAM__.html)

[![Purchase Advanced](/assets/advanced-pcb.png)](https://www.pcbway.com/project/shareproject/Game_Boy_Camera_Flashcart_2x1MB_FRAM_Advanced_PCB_73cba77a.html)

If you want to support me for free (and get 5 USD in new user credit) you can use my PCBWay [Referral link](https://www.pcbway.com/setinvite.aspx?inviteid=388393) when signing up on PCBWay

![](https://i.imgur.com/Iy5TtAD.png)

[![PCBWay Referral](/assets/referral-link.png)](https://www.pcbway.com/setinvite.aspx?inviteid=388393)

**Make sure you read the License!**



**Flashing:**

Flashing has only been tested with a [GBxCart](https://www.insidegadgets.com/projects/gbxcart-rw/), flashing both 1MB sections requires [this custom software](GBxCart_RW_GB_Camera_2x1MB_Flasher.zip), which is a modified version of InsideGadget's 2x2MB MBC3 software, or [FlashGBX](https://github.com/lesserkuma/FlashGBX/releases) v3.2 and above.

**BOM:**

| Reference | Part Number | Description |
|-|-|-|
| C1 | [4x4.5mm 22uF](https://www.aliexpress.com/item/32377971645.html) | 22uF 16V 4x4.5 Electrolytic Capacitor |
| C2, C3, C4, C12, C13 | [TCC0603X7R104J500CT](https://www.lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_CCTC-TCC0603X7R104J500CT_C282518.html) | 100nF 0603 Capacitor |
| C5, C6, C7, C8, C9, C10, C11 | [CC0402KRX7R7BB104](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_YAGEO-CC0402KRX7R7BB104_C60474.html) | 100nF 0402 Capacitor |
| C14, C15 | [CC0603JRNPO9BN220](https://www.lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_YAGEO-CC0603JRNPO9BN220_C105620.html) | 22pF 0603 Capacitor |
| R1 | [RC0603JR-071KL](https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_YAGEO-RC0603JR-071KL_C14676.html) | 1K Ω 0603 Resistor |
| D1 | Diode | Harvest D2 from original cartridge |
| J1 | [B9B-ZR-SM4-TF](https://www.aliexpress.com/item/32920487056.html) | Camera Connector, Harvest or buy (JST ZH1.5MM 9 Pin) |
| SW1 | [K3-1296S-E1](https://www.lcsc.com/product-detail/Slide-Switches_Korean-Hroparts-Elec-K3-1296S-E1_C128955.html)| SPDT Switch (For 2x1MB Rom Switching) |
| U1 | MAC-GBD | Harvest U1 from original cartridge |
| U2 | [AM29F016](https://www.aliexpress.com/item/33043533022.html) | 2MB Flash |
| U3 | [FM28V100](https://www.aliexpress.com/item/4001322883101.html) | 1MB FRAM |
| U4 | [TPRT9013-33G](https://www.lcsc.com/product-detail/Linear-Voltage-Regulators-LDO_TECH-PUBLIC-TPRT9013-33GB_C587158.html) | 3.3V Voltage Regulator |


[Interactive BOM](https://martinrefseth.com/ibom/Game%20Boy%20Camera%20Flashcart)


Makes use of [djedditt's](https://github.com/djedditt/s) [gamepak footprint](https://github.com/djedditt/kicad-gamepaks)

Looking for a ready to use flashcart? check out InsideGadgets custom flashcart, the [Insidegadgets' PicNRec AIO](https://shop.insidegadgets.com/product/gameboy-camera-picnrec-aio/)
![](/assets/Front.png)
