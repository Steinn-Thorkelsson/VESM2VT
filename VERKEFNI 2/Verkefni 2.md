1. [7-Segment Displays: Count Up Timer og Rolling Dice (sl. Temperature display)](http://www.circuitbasics.com/arduino-7-segment-display-tutorial/)
   - Hvort er þitt 7-Segment Display *common anode* eða *common cathode* og hver er munurinn á þessu tvennu?
        * Minn er Common anode
   - 7-Segment Display samanstendur af 8 LED, hvers vegna þarf bara eitt viðnám (en ekki átta)?
   - Breyttu kóðanum í *Count Up Timer* þannig að hann noti ekki ```for``` lykkjuna.
* ```
    void loop(){    
        sevseg.setNumber(1);
        delay(1000);
        sevseg.refreshDisplay();
        sevseg.setNumber(2);
        delay(1000);
        sevseg.refreshDisplay(); 
        sevseg.setNumber(3);
        delay(1000);
        sevseg.refreshDisplay(); 
        sevseg.setNumber(4);
        delay(1000);
        sevseg.refreshDisplay(); 
        sevseg.setNumber(5);
        delay(1000);
        sevseg.refreshDisplay(); 
        sevseg.setNumber(6);
        delay(1000);
        sevseg.refreshDisplay();
        sevseg.setNumber(7);
        delay(1000);
        sevseg.refreshDisplay();
        sevseg.setNumber(8);
        delay(1000);
        sevseg.refreshDisplay();    
        sevseg.setNumber(9);
        delay(1000);
        sevseg.refreshDisplay(); 
        } 
    ```
    

1. [Stýripinni (e. joystick)](../Kodi/styripinni.ino), sjá efst í skjalinu hvernig á að tengja stýripinnan við Arduino
   - Aðeins um [Pull Up Resistor (myndband)](https://www.youtube.com/watch?v=wxjerCHCEMg)
   - Hvaða gildi gefur stýripinninn þegar ýtt er lengst til vinstri?
   - Hvaða gildi gefur stýripinninn þegar ekki er ýtt á hann?

1. [LCD1602 (gæti þurft að lóða)](https://www.arduino.cc/en/Tutorial/HelloWorld)
   - Afhverju er R/W tengt í GND?
   - Afherju eru bara 4 datapinnar notaðir, hvenær notar maður alla 8?
   - Breyttu kóðanum þannig að nafnið þitt birtist í efri línunni á skjánum, einn stafur í einu (skrifar nafnið og endurtekur sig svo). Í neðri línunni á að standa **Tolvubraut**.
   
   ![LCD](../Myndir/lcd_verkefni2.gif)

1. Stýripinni og LCD
   - Notaði stýripinnann til að flytja tákn að eigin vali til á LCD skjánum.
   - Táknið þarf að geta flust milli línanna og svo innan sömu línunnar.
   - Tryggið að táknið fari ekki út fyrir skjáinn.

1. [Shift register](https://learn.adafruit.com/adafruit-arduino-lesson-4-eight-leds/parts)
   - [Integrated Circuits](https://www.instructables.com/lesson/Integrated-Circuits-1/)
   - Setja upp og sýna video fyrir [Shift register](https://learn.adafruit.com/adafruit-arduino-lesson-4-eight-leds/parts)

## Námsmat og skil

Gefið er heilt fyrir fullnægjandi lausn og svör, hálft ef ábótavant eða svör vanta.
Skilaðu á Innu vefslóð á **Github wiki** vefsíðu (private) sem inniheldur:

- Myndbönd af virkni úr verklegum tilraunum.
  - Passaðu að nafnið þitt og dagsetning komi fram (t.d. á miða) í öllum myndböndum.
- Kóði.
- Svör við spurningum.

<!-- 1. [Lesson 13: Stopwatch (4 digit 7-segment display)](https://github.com/GunnarThorunnarson/VESM2VT05BU/tree/master/PowerSupplyLearningKitforUNO/Lesson%2013%20Stopwatch) 

1. [IR fjarstýringu með ir receiver](http://www.circuitbasics.com/arduino-ir-remote-receiver-tutorial/) -->

<!-- 4. [Stýripinni og ljósadíóður (nota eigin kóða)](https://github.com/GunnarThorunnarson/VESM2VT05BU/blob/master/verkefni/ljosadiodur.md) sjá [kóðalausn](https://create.arduino.cc/editor/gestskoli/f9733890-89c5-4498-a981-88bbdec3165b/preview) -->

<!-- 5. [Lesson 10: Thermistor (Power Supply sett) (notar LCD skjá)](https://github.com/GunnarThorunnarson/VESM2VT05BU/tree/master/PowerSupplyLearningKitforUNO/Lesson%2010%20Thermistor) -->

<!--
1. Rökrásir
   - [Grunnhliðin (youtube, 3 mín, ísl)](https://youtu.be/Q_TSHgi_SgE)
   - [Fleiri hlið](https://en.wikipedia.org/wiki/Logic_gate)
   - [Integrated Circuits](https://www.instructables.com/lesson/Integrated-Circuits-1/)
   - [Half Adder](https://www.circuitstoday.com/half-adder)
   - Settu upp *Half Adder* rás á breadboard ásamt tökkum og ljósum til að sýna virknina. Þú færð hliðin hjá kennaranum.
-->

<!--

- Settu upp í TinkerCad 
1. TinkerCad tengla á lausnir (muna að hafa public).
2. [Skjámyndbandsupptöku](https://screencast-o-matic.com) af virkni í TinkerCad.

-->
