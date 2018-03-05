# raspberry_pi_zero_w_flask_gpio

> Based on Rui Santos adaptation of the (Getting Started with Raspberry Pi by Matt Richardson)
> Credits: [http://randomnerdtutorials.com]

This is a set of files, creating a complete flask setup, in order to control a raspberry zero w pi's GPIO from a simple web page.

### Contents
* app.py
* templates/main.html
* static/css/main.css

### Description
This is an html/css page, that creates a GPIO schematic view. It includes name and description for each pin as well as, distinctive colors for each pin family.
* Orange - 3V3 Power
* Red - 5V Power
* Blue - GPIO 
* Gray - Ground
* Yellow - IC2 Id Eeprom Pins

Most importantly, it is not just a clean and beautiful schematic representation. The pins are actually clickable buttons that control the state of each GPIO. The buttons have a simple color indication to show the GPIO state.
- Red = Low State
- Green = High State

### Template Example
![GPIO](https://github.com/fzantalis/raspberry_pi_zero_w_flask_gpio/blob/master/gpio.png)
