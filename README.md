# pcb-name-card-sp

My name or business card that is on a Printed Circuit Board (PCB). Comes with an white LED, UV LED and a ruler. Not forgetting a QR code containing my contact details in [Vcard](https://en.wikipedia.org/wiki/VCard) format. This is an update to my [previous version](https://github.com/yeokm1/pcb-name-card) since I have changed my company.

![Screen](images/front-censored.jpg)

### PCB Design software and addons/references used

1. Eagle 8.0.2
2. Modified CR2032 library based on [here](https://github.com/nickaknudson/eagle-nickaknudson/blob/master/cr2032.lbr)
2. Elecrow Design Rule Check for 2 layers (in repo as `Elecrow_2-layer_eagle_rule.dru`)
3. Elecrow Gerber Generater 2-layer board (in repo as `Elecrow_Gerber_Generater_DrillAlign.cam`)
4. QR code generated from [here](http://goqr.me/)

### Schematic drawings

Image are exported from Eagle at 600dpi.

![Screen](images/schematic.png)

The board schematic as seen in Eagle. The connections are slightly convoluted to prevent the traces from crossing in the board layout.

### Bill of Materials (BOM) for components only

Assume minimum order 10 pieces, cost in Singapore dollars. There are additional savings if I order more say 50 units but the savings are still small. Delivery for BOM not included.

The BOM is available in the odt spreadsheets in this repo.

### PCB fabrication

PCB fabrication is currently done by [Elecrow (10-pieces-link)](http://www.elecrow.com/10pcs-2-layer-pcb-p-1175.html) or [(50-pieces-link)](http://www.elecrow.com/50pcs-2-layer-pcb-enig-p-1172.html) based on the following settings. Remember to consult the order submission specifications at the bottom of the previous link before submitting. Use the provided Gerber generator to produce the Gerber files.

#### My Fabrication Settings:

1. Layer: 2
2. PCB Thickness: 0.6mm
3. Copper Weight : 1oz 35um (NA for 50 pieces)
4. PCB Size : 10cm Max * 10cm Max (or 50cm2 for 50 pieces)
5. PCB Color : Blue
6. Surface Finish: ENIG
7. PCB Stencil : NO Stencil
8. Lead time : Shipped in 4 to 7 days (NA for 50 pieces)
9. Panelizing : Single PCB with milling

# References
1. [How to design a 13.56 MHz
customized tag antenna](http://www.st.com/st-web-ui/static/active/jp/resource/technical/document/application_note/CD00221490.pdf)
2. [The impact of high pulse drain on CR2032 coin-cell battery capacity](http://m.eet.com/media/1121454/c0924post.pdf)
3. [Panasonic NFC Design Navigator](http://www.semicon.panasonic.co.jp/en/tool/nfcdesignnavigator/)
