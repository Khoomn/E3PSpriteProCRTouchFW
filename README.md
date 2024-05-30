I have since sold this printer and will not continue to release updates. Use this as a base if newer, better firmwares come out.

IMPORTANT: PUT "thermistor_1.h" under Marlin\src\module\thermistor

This firmware is for the Ender 3 Pro with mainboard v4.2.7. I upgraded my hotend to the Creality Sprite Pro with a CR Touch but the BL touch works the exact same (I think).

7x7 grid with 1 probe as I feel thats all that is necessary as my M48 accuracy test had a 0.00125 standard deviation which should be good enough.

I increased the Hotend to be able to print 290c as no one else I could find do so. I couldn't get it to reach 300c as there needs to be overhead for thermal runaway protection but 290 will do.

I'm printing with PA6-CF from Polymaker so thats why I wanted to max out the temps.

I have finally printed with this config at 290c for my PA6-CF and it worked flawlessly. 0 issues.

Please PID tune your bed and hotend on your own as these are my settings and can varry.

Please also change the X/Y offset, steps/mm and feedrate as needed for YOUR printer.
