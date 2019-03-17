# Smart-school
Ένα εκσυγχρονισμένο και αυτόνομο σχολικό σύστημα.
<hr>

# Περιγραφή
Η ομάδα του σχολείου μας θέλει να πάρει μέρος στην εξέλιξη της τεχνολογίας και του αυτοματισμού.Πιστεύει ότι μπορεί να προσφέρει πολλά με τα υλικά και τις γνώσεις που έχει διαθέσιμες. Γι' αυτό σκέφτηκε να δημιουργήσει ένα μηχάνημα το οποίο ασχολείται στα πλαίσια της εξοικονόμησης ενέργειας και της αυτόνομης εργασίας. Το Smart school είναι ένα αυτόματο σύστημα που κάνει την καθημερινή σχολική ρουτίνα πιο εύκολη για τους μαθητές και τους καθηγητές.
<hr>

# Στόχοι
Βασικοί στόχοι του έργου μας είναι:
<ol>
  <li>Το σύστημα ασφάλειας να ενεργοποιείται. (?)
  <li>Το ρεύμα του σχολείου καθώς και οι πρίζες να ενεργοποιούνται την ώρα που οι καθηγητές φτάνουν στο σχολείο.
  <li>Οι πόρτες να ανοίγουν μόνες τους όταν φτάσει κάποιος κοντά.
  <li>Ο φωτισμός, το ρεύμα και οι πρίζες της τάξεως να ανάβουν τη στιγμή που κάποιος περάσει για πρώτη φορά από την πόρτα.
  <li>Αν κάποιος μαθητής δεν είναι στην θέση του την ώρα του μαθήματος, να παίρνει αυτόματα απουσία.
  <li>Όταν κάθεται στην θέση του ο μαθητής, ο υπολογιστής να ανοίγει.
  <li>Στο τέλος του μαθήματος, αφού έχουν εξέλθει όλα τα άτομα απο την τάξη οι υπολογιστές να κλείνουν και τα φώτα να σβήνουν.
</ol>
<hr>

# Υλοποίηση Λειτουργιών
<ol>
  <li>Το σύστημα ασφαλείας θα χρησιμοποιεί ένα camera module, το οποίο θα είναι συνδεδεμένο στο Arduino και θα εμφανίζει τις εικόνες που  τραβούνται στην οθόνη του υπολογιστή μας. (?)
  <li>Με βοήθεια διακοπτών relay switches, που συνδέονται στο Arduino, το ρεύμα θα ενεργοποιείται και θα απενεργοποιείται κατά την περίοδο των σχολικών ωρών.
  <li>Για την πόρτα θα χρησιμοποιήσουμε photoresistors και laser modules. Ένας άνθρωπος θα μπορεί να περνά μπροστά από τους αισθητήρες, ώστε να δίνει το Arduino εντολή στην πόρτα για να ανοίξει. 
  <li>Αν κάποιος πρωτομπήκε στην τάξη ενώ ήταν άδεια θα στέλνετε σήμα σε όλες τις λειτουργίες και συσκευές να ξεκινήσουν, και θα κλείνουν όταν κι ο τελευταίος βγει από την τάξη. Οι αισθητήρες της πόρτας θα μπορούν να καταλαβαίνουν πότε κάποιος μπαίνει ή βγαίνει.
  <li>Οι απουσίες θα σημειώνονται μόνες τους όταν όλοι οι μαθητές κάθονται στις θέσεις τους. Κάθε θέση θα έχει έναν αισθητήρα βάρους ο οποίος θα κοιτάει αν κάποιος κάθεται πάνω στην καρέκλα. Αν δεν κάθεται κάποιος στην θέση του όταν έπρεπε, θα παίρνει απουσία.
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
|12 [5V Active Buzzer for Arduino](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/components-and-ic/5v-active-buzzer-for-arduino/)                                                          |0,4        |1               |0,4<br>
|13 [WeMos D1 Mini ESP8266 NodeMcu 4M - WIFI Development Board](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/microcontrollers/esp8266/wemos-d1-mini-esp8266-nodemcu-4m-wifi-development-board/)|6,98       |1               |6,98 <br>
|14 [MB102 Breadboard Power Supply 3.3V/5V For Arduino Breadboard (MB-102)](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/prototyping/breadboard/mb102-breadboard-power-supply-3.3v-5v-for-arduino-breadboard-mb-102/)|2            |1               |2<br>
|15 [65pcs Jumper Wire Cable kit for Solderless Breadboard Connections](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/prototyping/dupont-jumper-wires/65pcs-jumper-wire-cable-kit-for-solderless-breadboard-connections/)|3,5         |1               |3,5<br>
|16 [Micro SD Storage Board Module - SPI For Arduino](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/modules/storage/micro-sd-storage-board-module-spi-for-arduino/)     |2,5          |2               |5<br>
|17 [Small Speaker 8 Ohm 0.5W 40mm for Toys](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/modules/audio/small-speaker-8-ohm-0.5w-30mm-for-toys/)              |1,19         |2               |2,38<br>
|18 Ξυλεία                                                                           |50            |               |50<br>
|ΣΥΝΟΛΟ	                                                                             |             |                | 173,29€   

Τα υλικά είναι ενδεικτικά. Μπορεί να αλλάξει κάτι, να προστεθεί ή να αφαιρεθεί.
