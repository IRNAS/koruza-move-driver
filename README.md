![alt tag](https://github.com/IRNAS/koruza-move-driver/blob/master/Pics/koruza-logo-colour-med.png)

# Koruza move driver

The Koruza driver is an additional board to [Koruza CM board][link1_koruza_compute_module_repo]. The Koruza move driver is just a simple board dedicated to only one true real-time task - moving the stepper motors.

The main and only MCU on the board is the one and only ATmega328P, which is Arduino compatible. The MCU tasks are: driving the stepper motors, reading the switches and encoders, and communicating with the main board. For driving motors, there is one high-current Darlington transistor array. On the board back, at the end of the motor shafts two magnetic encoders are positioned. Two encoders are TLV493D from Infineon.

The firmware for the koruza move driver board is in the [firmware repository][link2_fw_repo].

![alt tag](https://github.com/IRNAS/koruza-move-driver/blob/master/Pics/move_driver_pic.jpg)
---

## Licensing

We strive to make KORUZA as usefully open-source as possible.
Hardware including documentation is licensed under [CERN OHL v.1.2. license](http://www.ohwr.org/licenses/cern-ohl/v1.2)

Firmware and software originating from the project is licensed under [GNU GENERAL PUBLIC LICENSE v3](http://www.gnu.org/licenses/gpl-3.0.en.html).

Open data generated by our projects is licensed under [CC0](https://creativecommons.org/publicdomain/zero/1.0/legalcode).

All our websites and additional documentation are licensed under [Creative Commons Attribution-ShareAlike 4 .0 Unported License] (https://creativecommons.org/licenses/by-sa/4.0/legalcode).

What this means is that you can use hardware, firmware, software and documentation without paying a royalty and knowing that you'll be able to use your version forever. You are also free to make changes but if you share these changes then you have to do so on the same conditions that you enjoy.

Koruza, GoodEnoughCNC and IRNAS are all names and marks of Institut IRNAS Race. 
You may use these names and terms only to attribute the appropriate entity as required by the Open Licences referred to above. You may not use them in any other way and in particular you may not use them to imply endorsement or authorization of any hardware that you design, make or sell.

[link1_koruza_compute_module_repo]: https://github.com/IRNAS/koruza-compute-module
[link2_fw_repo]: https://github.com/IRNAS/Koruza-Move-Driver-Firmware