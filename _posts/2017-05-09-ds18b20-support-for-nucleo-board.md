-= [Back to News](https://funlw65.github.io/news.html) -=- [Back to Home](https://funlw65.github.io/) =-
<hr />

# :computer: DS18B20 temperature sensor support for Nucleo board

So, I added the onewire and ds18b20 libraries. No extensive support (no search function), and with 12bit only resolution for now, but with a strong protection against errors. I included two projects as examples. One for a bus with one temperature sensor, and another with two sensors, to cover all the cases.

![ds18b20 breadboard](https://github.com/funlw65/my_nucleo_l152re/raw/master/OW03_DS18B20_temp/img/ds18b20_lcd.png)

#### Note:
>The firmware for the single sensor bus example won't work for the the bus with multiple sensors, showing "Err! Bad Data!" message, as intended.

It was a little bit of trouble, as I was tired and did not observed that my bus is connected to a wrong pin (annoyingly reporting "Err! No sensor!") so, I deleted a full featured DS18B20 library ported from AVR microcontrollers, in favor of another, more compact, ported from the JAL language for PIC microcontrollers, a library I contributed to.

Now I am ready to start working with I2C bus, as I really need it for the light sensor of the SLR project...  

```markdown
 Page done.
```
-= [Back to News](https://funlw65.github.io/news.html) -=- [Back to Home](https://funlw65.github.io/) =-

