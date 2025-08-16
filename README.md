# Monstrosity

A printer designed in ~~almost 24 hours~~ somewhere around 40-50 hours.

![alt text](renders-final/Monstrosity-full.PNG)

# but why?

Long story short, I didn't realize I still had time to submit things to Hack Clubs Highway event--until I had almost exactly 24 hours left. So, I made this. This monstrosity is a double hbot with a custom toolhead based on the Peopoly Lancer Long, capable of using a Bambu Labs A1 Mini build plate.

Second story slightly longer, I got some extra time when I was asked to do a re-review and decided to make a double hbot. Still the same size (roughly), but now it has twice the drive motors and triple the insanity. Hence the rename to being the Monstrosity.

### [CAD IS HERE](https://cad.onshape.com/documents/a25eb3393e530945c6474152/w/d83d10951cb1e8008c7f68e6/e/854bc744f46243b389612f55?renderMode=0&uiState=688c1bc2fb56dc36b3a2ea53)

# the bom

| PART                         | UNIT COST | QUANTITY | SPONSORED? | NOTES                                                              | ROW COST | SOURCE                                                                                                                                                                 |
| ---------------------------- | --------- | -------- | ---------- | ------------------------------------------------------------------ | -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BTT Octopus w/ 6 drivers     | $59.65    | 1        | FALSE      | I'll be asking many companies for a sponsorship for a mainboard    | $59.65   | [link](https://biqu.equipment/products/bigtreetech-octopus-v1-1?variant=39749193990242)                                                                                |
| Linear Rail Shipping         | $39.00    | 1        | FALSE      |                                                                    | $39.00   | [link](https://limobearing.com/)                                                                                                                                       |
| 10 pack of 1m 2020 extrusion | $44.01    | 1        | FALSE      |                                                                    | $44.01   | [link](https://www.aliexpress.us/item/3256807024011071.html)                                                                                                           |
| Peopoly Lancer Long          | $42.00    | 1        | FALSE      |                                                                    | $42.00   | [link](https://peopoly.net/products/magneto-x-lancer-melt-zone)                                                                                                        |
| T8x4 Leadscrew 250mm         | $10.95    | 3        | FALSE      |                                                                    | $32.85   | [link](https://www.aliexpress.us/item/3256806551253663.html)                                                                                                           |
| MGN9H 250mm Linear Rail      | $9.97     | 3        | FALSE      | Not told of the final cost until checkout because of custom length | $29.91   | [link](https://limobearing.com/)                                                                                                                                       |
| MGN9H 316mm Linear Rail      | $9.97     | 2        | FALSE      | Not told of the final cost until checkout because of custom length | $19.94   | [link](https://limobearing.com/)                                                                                                                                       |
| GT2 6mm Belt 1600mm Belt     | $9.95     | 2        | FALSE      |                                                                    | $19.90   | [link](https://www.aliexpress.us/item/3256805605215455.html)                                                                                                           |
| Bed                          | $17.19    | 1        | FALSE      | Custom made by JLC or PCBWAY, probably sponsored.                  | $17.19   |                                                                                                                                                                        |
| Roborock CPAP Blower         | $15.76    | 1        | FALSE      |                                                                    | $15.76   | [link](https://www.aliexpress.us/item/3256805903154627.html)                                                                                                           |
| HGX Gear Set                 | $15.06    | 1        | FALSE      |                                                                    | $15.06   | [link](https://www.aliexpress.us/item/3256805725355339.html)                                                                                                           |
| BTT Eddy Duo                 | $26.26    | 1        | FALSE      |                                                                    | $26.26   | [link](https://www.pandapi3d.com/product-page/bed-distance-sensor)                                                                                                     |
| PEI Plate and Magnet         | $26.76    | 1        | FALSE      |                                                                    | $26.76   | [link](https://www.aliexpress.us/item/3256809109559068.html)                                                                                                           |
| GT2 6mm 20t Pulleys          | $6.26     | 2        | FALSE      |                                                                    | $12.52   | [link](https://www.aliexpress.us/item/3256809488530404.html)                                                                                                           |
| D5x30 Smooth Pin             | $11.50    | 1        | FALSE      |                                                                    | $11.50   |                                                                                                                                                                        |
| F695 Flanged Bearing 10x     | $6.87     | 1        | FALSE      |                                                                    | $6.87    | [link](https://www.aliexpress.us/item/3256806636423980.html)                                                                                                           |
| MGN12H 265mm Linear Rail     | $10.71    | 1        | FALSE      | Not told of the final cost until checkout because of custom length | $10.71   | [link](https://limobearing.com/)                                                                                                                                       |
| BTT EBB36                    | $9.40     | 1        | FALSE      |                                                                    | $9.40    | [link](https://www.aliexpress.us/item/3256804056513768.html)                                                                                                           |
| 42mm Nema 17 Stepper Motor   | $4.72     | 7        | TRUE       | LDO Sponsorship                                                    | $0.00    | [link](https://www.omc-stepperonline.com/e-series-nema-17-bipolar-42ncm-59-49oz-in-1-5a-42x42x38mm-4-wires-w-1m-cable-connector-17he15-1504s)                          |
| Extruder Motor               | $18.30    | 1        | TRUE       | LDO Sponsorship                                                    | $0.00    | [link](https://biqu.equipment/products/biqu-orbiter-v1-5-extruder-dual-driver-gear-extrusion-3d-printer-parts-for-cr10-10s-ender3-3-pro-ender5?variant=40041793683554) |
| 4010 Hotend Fan              | $1.53     | 1        | FALSE      |                                                                    | $1.53    | [link](https://www.aliexpress.us/item/3256803185681643.html)                                                                                                           |
| 100x T Nuts                  | $0.99     | 1        | FALSE      |                                                                    | $0.99    | [link](https://www.aliexpress.us/item/2251832628044342.html)                                                                                                           |

The overall cost is $441.81

# wiring diagram

![alt text](pictures/wiring.png)

note: this uses an old photo of the design, but the wiring is the same.

# Credits

Thanks to the Voron team for publishing their kinematic Z mounts under the GPL license as part of the Voron Trident. This machine drew a lot of inspiration from the way the bed was used on the Trident.

[The Monolith gantry by CloakedWayne](https://github.com/CloakedWayne/Monolith_Gantry_V2-VT) was previously used in this design and a modified version of the 6mm belt tensioning system is used.
