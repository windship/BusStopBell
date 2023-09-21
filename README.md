<img src="https://github.com/windship/BusStopBell/assets/24471913/6cacd215-8c39-4da9-98cf-ded7e3839234" width="40%" height="40%">

# BusStopBell
Making a bus stop bell using Arduino
 * Playing WAV bell sounds from SD card with real button
 * Select various sounds with button switch and OLED screen
 * Use independently with Lithum battery pack / charging module, no power cable needed

# Materials required
 * Bus stop bell button
 * <a href="https://www.coupang.com/vp/products/6997600450?vendorItemId=84321330467&sourceType=MyCoupang_my_orders_list_product_title&isAddedCart=">Arduino Nano or compartible board</a> (as small as possible / better to avoid ESP8266 because of TMRpcm library compartibility issue)
 * <a href="https://www.devicemart.co.kr/goods/view?no=1326951&NaPm=ct%3Dlmsha1be%7Cci%3Dcheckout%7Ctr%3Dppc%7Ctrx%3Dnull%7Chk%3D8a10077bcd45f35bdc5527cbef1a0a51cc2af418">SD card module</a>
 * <a href="https://www.coupang.com/vp/products/7043748454?itemId=17427226428&vendorItemId=86950957754&q=%EC%83%8C%EB%94%94%EC%8A%A4%ED%81%AC+%EB%A7%88%EC%9D%B4%ED%81%AC%EB%A1%9C+SD%EC%B9%B4%EB%93%9C+32&itemsCount=27&searchId=1542c81c34334aa3b313ed4edfb6d221&rank=19&isAddedCart=">SD card</a>
 * <a href="https://www.devicemart.co.kr/goods/view?no=1290797&NaPm=ct%3Dlmsh6ou5%7Cci%3Dcheckout%7Ctr%3Dppc%7Ctrx%3Dnull%7Chk%3De62bdb4b9beaa385938889cec5c4828ada7625f5">Speaker and amp module</a> (over 0.5W 8ohm. Piezo or small buzzer may not work)
 * <a href="https://www.coupang.com/vp/products/6820636140?vendorItemId=83360267255&sourceType=MyCoupang_my_orders_list_product_title&isAddedCart=">OLED screen</a> (SSD1306 or whatever I2C you want)
 * <a href="https://www.eleparts.co.kr/goods/view?no=4276996&NaPm=ct%3Dlmsh7srv%7Cci%3Dcheckout%7Ctr%3Dppc%7Ctrx%3Dnull%7Chk%3D704e418920d833ab0b8ff0a6fed4d36bf3aed6cf">Lithum battery pack</a> and <a href="https://www.eleparts.co.kr/goods/view?no=12830037&NaPm=ct%3Dlmsh7dga%7Cci%3Dcheckout%7Ctr%3Dppc%7Ctrx%3Dnull%7Chk%3D3a0803d26f080d2ef0761477d96ce8f593e60e33">charging module</a> (each of two needed for over 5V power)
 * <a href="https://www.coupang.com/vp/products/6595613547?itemId=14900870846&vendorItemId=82139606000&q=push+tact+switch&itemsCount=27&searchId=5b35913758684e8da4726a725e6f29e9&rank=116&isAddedCart=">Push tact button</a> (for sound select)
 * <a href="https://www.coupang.com/vp/products/1345073550?itemId=2372720357&vendorItemId=71370420721&q=%EC%8A%AC%EB%9D%BC%EC%9D%B4%EB%93%9C+%EC%8A%A4%EC%9C%84%EC%B9%98&itemsCount=27&searchId=88e6f1f6ed21417c978c2e3f523db588&rank=2&isAddedCart=">Slide switch</a> (for power on/off)
 * Perfboard (proper size for your case)
 * <a href="https://www.coupang.com/vp/products/6035895292?itemId=11019946710&vendorItemId=78299605680&pickType=COU_PICK&q=pp+%EC%BC%80%EC%9D%B4%EC%8A%A4&itemsCount=27&searchId=57dce9feb6184222b5aaebcbb31f0b9e&rank=0&isAddedCart=">Plastic case shell</a>

# Schematics
<img src="https://github.com/windship/BusStopBell/assets/24471913/dea7fe14-2ac2-40fa-a665-5ae81d1f3949" width="75%" height="75%">

# Working
https://github.com/windship/BusStopBell/assets/24471913/b95e23af-b435-40b6-a88f-c536465ff846

