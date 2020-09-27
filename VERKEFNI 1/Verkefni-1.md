# Verkefni 1 - VESM2VT - Steinn Þorkelsson
**Hardware**

1. [Ladyada´s lesson 0: Vélbúnaður](https://learn.adafruit.com/ladyadas-learn-arduino-lesson-number-0) 

   Svaraðu eftirfarandi spurningum:

    1. Að hvaða leyti er gagnapinni 13 sérstakur í Arduino Uno?
        * Gagnapinni 13 er líka tengdur við L led á Arduino brettinu
    1. Hver er munurinn á digtial og analog input pinnum?
        * Digital input pinnar taka bara á móti low  og high signals bits(0 og 5 volt). Analog Pinnar taka inn hvaða spennu þannig að þú getur t.d. stjórnað birtu á led á miklu nákvæmari
    1. Hjá sumum digital pinnum er tilda merki (~) fyrir PWM. Hvað er e. Pulse Width Modulation (PWM) og fyrir hvað er það notað?
        * PWM er notað til þess að lækka spennuna frá digital pinna með því senda signal bara ákveðið oft á sekúndi. Ef þú vilt t.d. lækka spennuna niður í 2.5V þá myndi PWM senda 5V(High signal) í hálfa sekúndu og 0V (low signal) í hálfa sekúndu.

**Halló heimur kóði**

2. [Ladyada´s lesson 1: Blikkandi ljós, Halló heimur ](https://learn.adafruit.com/ladyadas-learn-arduino-lesson-number-1)
    * [Youtube Hlekkur](https://youtu.be/d7cDstm9IKY)

  
**LEDs**

3. [All About LEDs (KVL og Ohm's lögmál, að lesa datasheets)](https://learn.adafruit.com/all-about-leds/overview))
 
   Svaraðu eftirfarandi spurningum:

     1. Hvaða gagnlegar upplýsingar veitir Forward Voltage okkur í Datasheet fyrir LEDs?
        * Forward voltage segir þér hversu mikla spennu þú þarft til þess að kveikja á LED perunni.
     1. Útskýrðu KVL lögmálið með dæmi.
        * KVL lögmalið segir að fyrir lokaða hringrás þá þarf summa allra hluta í hringrásinni að vera 0 Volt. Ef þú ert t.d. með 9V rafhlöðu og led ljós sem þarf bara 2.5V, spennan sem þá vera eftir í hringrásinni myndi á vera 6.5V. Til þess að jafna út spennuna með viðnámi eða öðrum hlut sem lækkar spennuna frá 6.5V niður í 0V.
     1. Útskýrðu Ohms lögmálið með dæmi.
        * Ohms Lögmálið segir að Rafstraumurinn, mælt í Ampere, í hringrás er tengdur hltufallslega við spennuna í hringrásinni.
     
4. [Ladyada´s lesson 2: LEDs (viðnám, leds og brauðbretti)](https://learn.adafruit.com/adafruit-arduino-lesson-2-leds/overview)
    * [Youtube Hlekkur](https://youtu.be/2MB1VgDIOVc)
5. [Ladyada´s lesson 3: RGB LEDs, PWM, RGB og HEX](https://learn.adafruit.com/adafruit-arduino-lesson-3-rgb-leds)
    * [Youtube Hlekkur](https://youtu.be/pyD_-J5WN70)

---

**TinkerCad Projects**
- Skráðu þig eða stofnaðu TinkerCad reikning og smelltu á https://www.tinkercad.com/learn/circuits/projects  
- Skrollaðu aðeins niður og smelltu á **Show all Arduino** hnappinn til að sjá öll Arduino Projects 
- Fylgið eftirfarandi tutorials en verklega í höndunum (ekki í TinkerCad):

<br>

6. Pushbutton (Digital Input) 
   1. _Breyttu kóðanum þannig að með að ýta á takkann þá er slökkt á LED ljósi sem myndi annars lýsa stöðugt._
    * [Youtube hlekkur]()

    *   if (buttonState == HIGH) {
    digitalWrite(13, HIGH);
  } else {
    digitalWrite(13, LOW); 
    
7. Potentiometer (Analog Input) 
   1. _Instead of using the sensorValue to affect timing, can you figure out a way to make it affect the LED's brightness instead?_
   
   [Youtube hlekkur](https://youtu.be/wjQ9c0m9jIo)
8. Using the Serial Monitor
   1. _Hvað þýðir 9600 baud í Serial.begin(9600) og hvað gerist ef þú breytir gildinu?_
        * 9600baud þýðir að þú getur sent 9600 bits á sekúndu frá og til arduino. Ef þú hækkar eða lækkar það þá einfaldlega verður hraðinn hægari eða hraðari.
   
9. PIR Motion Sensor (Digital Input) - _skólinn á nokkra PIR skynjara sem þú getur notað_
   * Er að gera þetta heima, ég á ekki PIR motion sensor :( 
   
10. Photoresistor (Analog Input)
    * [Youtube Hlekkur](https://youtu.be/hNwnzz3Wg34)
11. Ultrasonic Distance Sensor 
    1. _Make a proximity alarm by adding a piezo buzzer that turns on when all three LEDs are lit up (closest distance)._
        * [Youtube Hlekkur](https://youtu.be/qPatTmRcen8)

