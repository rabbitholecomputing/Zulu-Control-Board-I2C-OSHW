# i2c Zulu Control board BOM for partially-assembled PCB kit
## (all surface-mount components mounted)

* SW1 & SW2 - P/N MJTP1230BL Any 6x6mm footprint pushbutton tactile switch/pushbuttons should work.
*  J2 - [0.96" OLED module](https://www.digikey.com/en/products/detail/canaduino/26095/16822116), sourceable via Amazon, AliExpres, eBay, etc.
The 0.96" OLED display modules are commodity items, see https://www.amazon.com/dp/B09T6SJBV5. Any 128x64 SSD1306-based OLED display with the correct pinout (GND, VCC, SCL, SCA, _in that order_) should work.

* D1 - This 5mm activity LED is optional. If you choose to install an LED there, make sure it's intended to operate at ~3-3.3 volts DC.
 
* J2 - Optional two-pin LED activity header on the control board, which must be separately connected to the two-pin activity LED header on the ZuluSCSI, as the Qwiic cable does not carry signals for that. 

* SW4, Rotary encoder: Apls Alpine [EC11E152440D](https://tech.alpsalpine.com/e/products/category/encorders/sub/01/series/ec11e/) or [similar Chinese-made "**EC11E**" equivalent](https://www.amazon.com/s?k=rotary+encoder+EC11).

Please note that **non-pushbutton** rotary encoders **are not supported** by the firmware, so be sure to obtain one that has pushbutton/push-on support.

The following Alps Alpine EC11E rotary encoders are pushbutton-equipped models:

* [EC11E15244G1](https://octopart.com/search?specs=0&full_query=EC11E15244G1)
* [EC11E18244AU](https://octopart.com/search?specs=0&full_query=EC11E18244AU)
* [EC11E09244AQ](https://octopart.com/search?specs=0&full_query=EC11E09244AQ)
* [EC11E15244B2](https://octopart.com/search?specs=0&full_query=EC11E15244B2)
* [EC11E18244A5](https://octopart.com/search?specs=0&full_query=EC11E18244A5)
