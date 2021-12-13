# 4x4-keypad-ESPHome

There are 2 versions for this little project. Both uses a D1 mini and a 4x4 matrix keypad, but one uses almost all the GPIO pins of the board, the other uses an I/O Expander (uses I²C). 

## Version 1
### Components list
* [D1 mini](https://s.click.aliexpress.com/e/_98eTUE)
* [4x4 Matrix Keypad](https://s.click.aliexpress.com/e/_9jFvLC)
* Some wires
### Guide
1) [Download](https://github.com/ssieb/custom_components/tree/master/keypad) the keypad custom component. Place the full keypad directory in /config/esphome/custom_components of your Home Assistant instance. 
2) Wire the D1 mini to the keypad as shown on the image: ![keypad_without_expander](https://user-images.githubusercontent.com/80924413/136712899-72927ca9-6afb-4dac-8479-22d9ad7cd70d.jpg)

3) Make a new ESPHome project, the file with extension .yaml need to look like the version2.yaml file. Past it into your newly created project and change your Wi-Fi SSID and all the passwords.
4) Upload the code to the D1 mini by using a micro USB connected to the PC you're working on or the hardware where your Home Assistant and ESPHome is running on.  

## Version 2
### Components list
* [D1 mini](https://s.click.aliexpress.com/e/_98eTUE)
* [4x4 Matrix Keypad](https://s.click.aliexpress.com/e/_9jFvLC)
* [I/O Expander SX1509](https://s.click.aliexpress.com/e/_9IorLu)
* Some wires
### Guide
1) [Download](https://github.com/ssieb/custom_components/tree/master/keypad) the keypad custom component. Place the full keypad directory in /config/esphome/custom_components of your Home Assistant instance. 
2) Wire the D1 mini to the keypad as shown on the image: ![keypad_with_expander](https://user-images.githubusercontent.com/80924413/136712563-da5e8959-ab6d-4f21-8b23-9407ec69e91a.jpg)
3) Make a new ESPHome project, the file with extension .yaml need to look like the version2.yaml file. Past it into your newly created project and change your Wi-Fi SSID and all the passwords.
4) Upload the code to the D1 mini by using a micro USB connected to the PC you're working on or the hardware where your Home Assistant and ESPHome is running on.

## If you really like this guide and want to support me:

<a href="https://www.buymeacoffee.com/rubs" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a> 
