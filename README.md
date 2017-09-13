![alt tag](https://github.com/IRNAS/koruza-move-driver/blob/master/Pics/koruza-logo-colour-med.png)

# Koruza move driver

The Koruza driver is an additional board to [Koruza CM board][link1_koruza_compute_module_repo]. The Koruza move driver is just a simple board dedicated to only one true real-time task - moving the stepper motors.

The main and only MCU on the board is the one and only ATmega328P, which is Arduino compatible. The MCU tasks are: driving the stepper motors, reading the switches and encoders, and communicating with the main board. For driving motors, there is one high-current Darlington transistor array. On the board back, at the end of the motor shafts two magnetic encoders are positioned. Two encoders are TLV493D from Infineon.

For more information about the design of the koruza move driver please see the [Schematics and PCB design files in PDF format][link3_pdf].
The firmware for the koruza move driver board is in the [firmware repository][link2_fw_repo].

![alt tag](https://github.com/IRNAS/koruza-move-driver/blob/master/Pics/move_driver_pic.jpg)
---

## Licensing

KORUZA Pro Hardware with documentation, including Koruza move driver, is licensed under [CERN OHL v.1.2. license](https://www.ohwr.org/licenses/cern-ohl/license_versions/v1.2).

What this means is that you can use this hardware and documentation without paying a royalty and knowing that you'll be able to use your version forever. You are also free to make changes but if you share these changes then you have to do so on the same conditions that you enjoy.

KORUZA, KORUZA Pro and IRNAS are all names and marks of Institute IRNAS Rače. You may use these names and terms only to attribute the appropriate entity as required by the Open Licence referred to above. You may not use them in any other way and in particular you may not use them to imply endorsement or authorization of any hardware that you design, make or sell.


[link1_koruza_compute_module_repo]: https://github.com/IRNAS/koruza-compute-module
[link2_fw_repo]: https://github.com/IRNAS/Koruza-Move-Driver-Firmware
[link3_pdf]: https://github.com/IRNAS/koruza-move-driver/blob/master/Koruza%20move%20driver/Project%20Outputs%20for%20PCB_Project_KoruzaMoveDriver/koruza-move-driver-PCB.pdf
