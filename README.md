# AskSinPP_Examples
Meine Beispiele für papa's AskSinPP library
[AskSinPP Library](https://github.com/pa-pa/AskSinPP)

## Universalsensor (HB-UNI-Sensor1)

- Demonstriert einen HomeMatic/RaspberryMatic/FHEM Universalsensor für Temperatur, Luftdruck, Luftfeuchte, Helligkeit usw.
- modifizierbar für andere Sensoren
- konfigurierbares Sendeintervall über WebUI
- konfigurierbare Höhe (für Berechnung des Luftdrucks auf Meeresniveau/Normaldruck) über WebUI
- Der Status eines digitalen Eingangs kann mit übertragen werden.

<p align="center"><img src="Images/HB-UNI-Sensor1_HW1_small.jpg?raw=true"/></p>

[Projektseite HB-UNI-Sensor1](https://github.com/TomMajor/AskSinPP_Examples/tree/master/HB-UNI-Sensor1)

## Wassermelder (HB-SEC-WDS-2)

- Wassermelder mit Leitfähigkeitsmessung zwischen den Elektroden
- Demonstriert die Verwendung vom 'ThreeStateSensor' device type aus der AskSinPP Bibliothek mit einer anpassbaren Messroutine, in diesem Fall die Leitfähigkeitsmessung mit dem integrierten ADC

<p align="center"><img src="Images/Prototyp_Wassermelder_small.jpg?raw=true"/></p>

[Projektseite HB-SEC-WDS-2](https://github.com/TomMajor/AskSinPP_Examples/tree/master/HB-SEC-WDS-2)

## Schutz vor "Babbling Idiot" (BI)

- Betrachtungen und Lösungen zum Schutz gegen einen "Babbling Idiot" (Dauersender) im HomeMatic Netzwerk bei Selbstbaugeräten

[Projektseite BI Schutz](https://github.com/TomMajor/AskSinPP_Examples/tree/master/Info/Babbling%20Idiot%20Protection)

## SensorTest_Lux

- Messungen und Betrachtungen zu den Helligkeitssensoren TSL2561 und MAX44009

[Projektseite SensorTest_Lux](https://github.com/TomMajor/AskSinPP_Examples/tree/master/Info/SensorTest_Lux)

## Ruhestrom

- Hinweise zur Verringerung des Ruhestromverbrauchs

- Sketch zur Überprüfung von Aktiv- und Power-Down-Strom eines Arduino Pro Mini 328 (3.3V/8MHz) mit angeschlossenem CC1101 (das wäre ein Basis-AskSinPP Gerät ohne angeschlossene Sensoren oder andere Zusatz-HW)

<p align="center"><img src="Images/SensorBreakoutBoards_small.jpg?raw=true"/></p>

[Projektseite Ruhestrom](https://github.com/TomMajor/AskSinPP_Examples/tree/master/Info/Ruhestrom)

## WDT_Frequenz

- Misst die Abweichung der Watchdog-Timer Frequenz bei einen ATmega328 in Bezug zur Quarzfrequenz, wichtig für das Aufwach-Intervall

[Projektseite WDT_Frequenz](https://github.com/TomMajor/AskSinPP_Examples/tree/master/Info/WDT_Frequenz)
