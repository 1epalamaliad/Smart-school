# Smart-school
Ένα εκσυγχρονισμένο και αυτόνομο σχολικό σύστημα.
<hr>

# Περιγραφή
Η ομάδα του σχολείου μας θέλει να πάρει μέρος στην εξέλιξη της τεχνολογίας και του αυτοματισμού.  Γι’ αυτό σκέφτηκε να δημιουργήσει μια κατασκευή που θα προσομοιώνει τις λειτουργίες  ενός "έξυπνου σχολείου" το οποίο  έχει στόχο την εξοικονόμηση ενέργειας και την αυτοματοποίηση των λειτουργιών ενός σχολείου. Η ιδέα είναι απλή, τα φώτα στην τάξη και η πόρτα να ανοίγουν και να κλείνουν αυτόματα και τα φώτα στους διαδρόμους θα ανοίγουν εάν υπάρχει συννεφιά ή είναι νύχτα. Το Smart school είναι ένα αυτόματο σύστημα που κάνει την καθημερινή σχολική ρουτίνα πιο εύκολη για τους μαθητές και τους καθηγητές.
<hr>

# Λειτουργίες
Βασικοί στόχοι του έργου μας είναι:
<ol>
  <li>Το φως των κοινόχρηστων χώρων του σχολείου να ενεργοποιείται ανάλογα με το φως της μέρας.
  <li>Οι πόρτες να ανοίγουν αυτόματα όταν ένας μαθητής πλησιάσει την πόρτα
  <li>Ο φωτισμός, το ρεύμα, οι πρίζες και οι υπολογιστές της τάξεως να ανάβουν τη στιγμή που κάποιος περάσει για πρώτη φορά από την πόρτα.
  <li>Στο τέλος του μαθήματος, αφού έχουν εξέλθει όλα τα άτομα από την τάξη οι υπολογιστές να κλείνουν και τα φώτα να σβήνουν.
<hr>

# Υλοποίηση Λειτουργιών
<ol>
  <li>Με βοήθεια των photoresistors, που συνδέονται στο Arduino, θα ενεργοποιείται και θα απενεργοποιείται ο φωτισμός του σχολείου στους κοινόχρηστους χώρους (π.χ διάδρομος) ανάλογα με το φως της μέρας.
  <li>Για την πόρτα θα χρησιμοποιήσουμε photoresistors και laser modules. Όταν πλησιάσει ο μαθητής μπροστά από τους αισθητήρες, θα δίνετε εντολή στα μοτέρ της πόρτας για να ανοίξει.
  <li>Όταν θα μπει ο πρώτος μαθητής στην τάξη η πόρτα θα ανοίξει, θα κλείσει και θα ανάψει το φως, το οποίο θα παραμείνει ανοικτό όσο οι μαθητές βρίσκονται στην αίθουσα. Με αυτόν τον τρόπο μετράμε το πλήθος των μαθητών που βρίσκονται στην τάξη εκείνη την ώρα. Όταν εξέλθει και ο τελευταίος μαθητής τα φώτα και η πόρτα θα κλείσουν.
  <li>Ο γενικός διακόπτης ρεύματος του σχολείου κλείνει μετά την λήξη των μαθημάτων.
</ol>
<hr>
    
# Υλικά

|Α/Α	Υλικό	                                                                  |  Τιμή (€)|	Ποσότητα (τεμ)|	Σύνολο (€)|
|-----------------------------------------------------------------------------|----------|----------------|-----------|
|1	[Photoresistor - Light Detection Module for Arduino](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/sensors/light/photoresistor-light-detection-module-for-arduino/)                                                                                                                                     |  2	     |   4	          |  8<br> 
|2	[Solderless MB-102 Breadboard 830 Tie Points For Arduino (MB102)](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/prototyping/breadboard/solderless-mb-102-breadboard-830-tie-points-for-arduino-mb102/)                                                                                                               |  4,5    |   1	           |  4,5<br>
|3	[MG90S Micro Metal Gear 9g Servo for Arduino / RC (180 Degrees)](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/motors/servo/mg90s-micro-metal-gear-9g-servo-for-arduino-rc-180-degrees/)	                                                                                                                           |  5	     |   4	          |  20<br>
|4	[5V 1-Channel Relay High/Low Trigger - For Arduino](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/relays/5v-relays/5v-1-channel-relay-high-low-trigger-for-arduino/)	  |  2,39	  |   7	           |  16,73<br>
|5	[50Kg Load Cell Weighing Sensor - Half-Bridge](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/sensors/pressure/50kg-load-cell-weighing-sensor-half-bridge/)	                                                                                                                                       |  5	     |   3	          |  15<br>
|6	[5mW Laser Module for Arduino KY-008](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/outputs/5mw-laser-module-for-arduino/)	                                                                 |  3      |   3            |   9<br>
|7	[Arduino UNO R3 ATmega328P Board with USB Cable (DIP Version)(OEM)](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/microcontrollers/compatible-boards/arduino-uno-r3-atmega328p-board-with-usb-cable-dip-version-oem/)                                                                                                   |  9,8   |   2	          |  19,6 <br>
|8	[10pcs Transparent Led 3mm - Pink](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/components-and-ic/leds/3mm/10pcs-transparent-led-3mm-pink/)		                                       |  0,4    |    1           |  0,4<br>
|9  [10Pcs Super Bright 3MM Blue LEDs](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/components-and-ic/leds/3mm/10pcs-super-bright-3mm-blue-leds/)                                        |0,4      |    1           |0,4<br>
|10 [4-pin Digital Temperature Thermistor Sensor Module for Arduino KY-028 (Oem)](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/sensors/temperature/4-pin-digital-temperature-thermistor-sensor-module-for-arduino/)                                                                                                             |2,41     |    1           |2,41<br>
|11 [OV7670 Camera Module 640X480 for Arduino](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/sensors/camera/ov7670-camera-module-640x480-for-arduino/)            |9,99     |1               |9,99<br>
|12 [5V Active Buzzer for Arduino](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/components-and-ic/5v-active-buzzer-for-arduino/)                                                           |0,4      |1               |0,4<br>
|13 [WeMos D1 Mini ESP8266 NodeMcu 4M - WIFI Development Board](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/microcontrollers/esp8266/wemos-d1-mini-esp8266-nodemcu-4m-wifi-development-board/)|6,98       |1               |6,98 <br>
|14 [MB102 Breadboard Power Supply 3.3V/5V For Arduino Breadboard (MB-102)](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/prototyping/breadboard/mb102-breadboard-power-supply-3.3v-5v-for-arduino-breadboard-mb-102/)|2            |1               |2<br>
|15 [65pcs Jumper Wire Cable kit for Solderless Breadboard Connections](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/prototyping/dupont-jumper-wires/65pcs-jumper-wire-cable-kit-for-solderless-breadboard-connections/)|3,5         |1               |3,5<br>
|16 [Micro SD Storage Board Module - SPI For Arduino](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/modules/storage/micro-sd-storage-board-module-spi-for-arduino/)     |2,5          |2               |5<br>
|17 [Small Speaker 8 Ohm 0.5W 40mm for Toys](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/modules/audio/small-speaker-8-ohm-0.5w-30mm-for-toys/)              |1,19         |2               |2,38<br>
|18 [HX711 A/D 24-BIT CONVERTER - LOAD CELL AMPLIFIER FOR WEIGHING SENSOR FOR ARDUINO](https://www.cableworks.gr/ilektronika/hx711-a-d-24-bit-converter-load-cell-amplifier-for-weighing-sensor-for-arduino/)                                                                                              |2,5          |3               |7,5<br>
|19 Ξυλεία                                                                           |30           |               |30<br>
|ΣΥΝΟΛΟ	                                                                             |             |                | 160,79€   

Τα υλικά είναι ενδεικτικά. Μπορεί να αλλάξει κάτι, να προστεθεί ή να αφαιρεθεί.
