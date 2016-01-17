# heart_rate_monitor
Heart rate monitor designed in KiCad, using Nordic Semiconductor NRF51822 bluetooth module and TI AFE4400 heart rate module.

The repository contains a KiCad design of a 5x5 cm heart rate monitor breakout board. Some libraries were borrowed from Guan Yang's github projects (https://github.com/guanix/boards). Also, some design aspects of the circuit were inspired by HackManhattan Nordic nrf51822 beakout board (http://dangerousprototypes.com/2013/05/19/hackmanhattans-nordic-nrf51822-breakout-board/)

[Schematics](https://github.com/jkravanja/heart_rate_monitor/blob/master/hr.pdf)

In addition to AFE440 for heart rate measurements and NRF51822 for BLE communications, the circuit also contains a [Freescale MMA8452 3-axis accelerometer](http://www.nxp.com/files/sensors/doc/data_sheet/MMA8452Q.pdf), CAT24M01 1Mb EEPROM and an additional heart rate circuit composed of just a few simple elements (see bottom center of the schematics). The circuit was inspired by [this article](http://www.biofotonika.lu.lv/fileadmin/user_upload/lu_portal/projekti/biofotonika/Publikacijas/A4/SPIE/22.Kviesis-A_photoplethysmography_device_for_multipurpose_blood_circulatory_system_assessment.pdf) and presents a cheaper and simpler option to AFE4400.

![Image of manufactured PCB](https://github.com/jkravanja/heart_rate_monitor/blob/master/img/1.jpg)
![Components were soldered with reflow technique. Some joints had to be manually corrected using soldering iron](https://github.com/jkravanja/heart_rate_monitor/blob/master/img/2.jpeg)
![Added battery holder and connectors](https://github.com/jkravanja/heart_rate_monitor/blob/master/img/3.jpeg)
