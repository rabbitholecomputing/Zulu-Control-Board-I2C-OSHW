# i2c Zulu Control board BOM for partially-assembled PCB kit
## (all surface-mount components mounted)

* SW1 & SW2 - P/N MJTP1230BL Any 6x6mm footprint pushbutton tactile switch/pushbuttons should work.
*  J2 - [0.96" OLED module](https://www.digikey.com/en/products/detail/canaduino/26095/16822116), sourceable via Amazon, AliExpres, eBay, etc.
The 0.96" OLED display modules are commodity items, see https://www.amazon.com/dp/B09T6SJBV5. Any 128x64 SSD1306-based OLED display with the correct pinout (GND, VCC, SCL, SCA, _in that order_) should work.

* D1 - This 5mm activity LED is optional. If you choose to install an LED there, make sure it's intended to operate at ~3-3.3 volts DC.
 
* J2 - Optional two-pin LED activity header on the control board, which must be separately connected to the two-pin activity LED header on the ZuluSCSI, as the Qwiic cable does not carry signals for that. 

* SW4, Rotary encoder: Apls Alpine [EC11E153440D](https://www.mouser.com/en/Compare/SimilarProducts?pIds=ynblqeJvy3E8YXKVWdoBOI%252Bfvq0Lxzf4XI7lGkWAi0aH8Dopjd%252FMHA%253D%253D) or similar Chinese-made "EC11" equivalent.

Please note that **non-pushbutton** rotary encoders **are not supported** by the firmware, so be sure to obtain one that has pushbutton support.

For rotary encoders, there are many alternative manufacturers and part numbers, including [Chinese-made ones which you can purchase from Amazon](https://www.amazon.com/s?k=rotary+encoder+EC11).
