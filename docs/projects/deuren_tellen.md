# Hoe vaak gaan deuren open en dicht?

De [Inspectie Gezondheidszorg en Jeugd](https://www.igj.nl/) controleert scherp op hoe vaak een deur van een operatiekamer open en dicht gaat.

Zo kwam een ziekenhuis in Winterswijk onder toezicht doordat:

> Ook werd de deur van de operatiekamer onnodig vaak open- en dichtgedaan zodat ook daar de kans op besmetting extra groot was.
(bron:[PZC](https://www.pzc.nl/gezond/ernstige-tekortkomingen-ziekenhuis-winterswijk-onder-toezicht~a1d60865/))

## Idee
Met een [HC-SR04 ultrasoon sensor](https://www.leaphy.nl/webshop.html#!/Ultrasoon-sensor/p/313360091/category=84723249) 
is het mogelijk om afstand te meten tot een object. 

Stappen:
* De ultrasoon sensor kan in de buurt van de deur gezet worden.
* Gedurende een periode houden we de waarden van de ultrasoon sensor bij en slaan dit op in een database, bijvoorbeeld SQL of MongoDB.
* we lezen de waardes uit en bepalen wanneer de deur open en dicht was.

## Benodigheden
* board computer (Raspberry Pi of Arduino)
* ultrasoon sensor

## Eerdere code voor dit project
Je bent de eerste!
