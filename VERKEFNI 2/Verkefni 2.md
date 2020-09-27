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
      * X = 518 Y = 0 Takki = 1

   - Hvaða gildi gefur stýripinninn þegar ekki er ýtt á hann?
      * X = 518 Y = 524 Takki = 1

1. [LCD1602 (gæti þurft að lóða)](https://www.arduino.cc/en/Tutorial/HelloWorld)
   - Afhverju er R/W tengt í GND?
         * Ef að R/W er tengt í GND þá er skjárinn í Write mode, þannig að þú getur sent texa í hann.
   - Afherju eru bara 4 datapinnar notaðir, hvenær notar maður alla 8?
        * 8 bit er hraðara en það tekur upp 8 pinna á brettinu, 4 bit er 2x hægara en tekur bara 4 pinna á brettinu. 4 bit er til dæmis notað þegar að maður þarf að nota aðra pinna fyrir aðra hluti.
      
   - Breyttu kóðanum þannig að nafnið þitt birtist í efri línunni á skjánum, einn stafur í einu (skrifar nafnið og endurtekur sig svo). Í neðri línunni á að standa **Tolvubraut**.
      * [Youtube Hlekkur]()

```
   void loop() {
  String texti = "Steinn Thorkelsson";
  lcd.setCursor(0, 0);
  for (int i = 0; i < texti.length(); i++) {
    lcd.print(texti[i]);
    delay(150);
  }
  lcd.setCursor(0, 0);
  lcd.print("                ");
  lcd.setCursor(0 ,1);
  lcd.print("Tolvubraut 2020");

} 
```
   
   ![LCD](../Myndir/lcd_verkefni2.gif)

1. Stýripinni og LCD
      * [Youtube Hlekkur](https://youtu.be/BIvHw8ZJ0m0)


1. [Shift register](https://learn.adafruit.com/adafruit-arduino-lesson-4-eight-leds/parts)
   - [Integrated Circuits](https://www.instructables.com/lesson/Integrated-Circuits-1/)
   - Setja upp og sýna video fyrir [Shift register](https://learn.adafruit.com/adafruit-arduino-lesson-4-eight-leds/parts)



