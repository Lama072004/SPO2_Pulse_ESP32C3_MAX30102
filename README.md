Projekt: Mobiles Pulsoxymeter mit GY-MAX30102
Projektbeschreibung:
Im Rahmen des Moduls Embedded Systems wurde ein Pulsoxymeter auf Basis des GY-MAX30102-Sensors und eines ESP32-C3-Mini Mikrocontrollers entwickelt. Ziel des Projekts war die Messung der Herzfrequenz und der arteriellen Sauerstoffsättigung (SpO₂) durch optische Verfahren, wie sie in der medizinischen Diagnostik verwendet werden. Die Verarbeitung der Sensorsignale erfolgt direkt auf dem Mikrocontroller mithilfe von Embedded-C-Treibern und geeigneten Algorithmen zur Signalfilterung und -auswertung.
Das System sollte ursprünglich batteriebetrieben und mobil einsetzbar sein, mit einer drahtlosen Übertragung der Messwerte via Bluetooth Low Energy (BLE) an ein Smartphone. Außerdem war die Entwicklung einer Visualisierungs-App in Flutter geplant. Aufgrund zeitlicher Einschränkungen wurden diese Funktionen jedoch nicht umgesetzt. Stattdessen erfolgt die Datenausgabe aktuell direkt über die serielle Schnittstelle an einen PC.
Ein Vergleich mit einem professionellen SpO₂- oder Pulsmessgerät (z. B. Corpuls-System) zur Validierung der Messergebnisse war vorgesehen, wurde jedoch ebenfalls nicht durchgeführt.
Optional geplante Erweiterungen (nicht umgesetzt):
•	Bluetooth-Übertragung an ein Smartphone
•	Visualisierung der Daten über eine Flutter-App
•	Mobiler Akkubetrieb mit kompaktem Gehäuse
•	Vergleichsmessung mit professionellem Pulsoxymeter
•	Erkennung von Pulsarrhythmien, Tachykardie und Bradykardie mit Benachrichtigungsfunktion bei Anomalien (Push/Toast bei aktiver BLE-Verbindung)
Benötigte Bauteile:
Komponente	Beschreibung	Preis
ESP32-C3-Mini	Mikrocontroller mit BLE-Funktion, zur Signalverarbeitung	ca. 5,00 €
GY-MAX30102	Pulsoxymetrie-Sensor mit integrierten LEDs/Photodioden	ca. 3,96 €
Steckbrett & Kabel	Für die Verdrahtung und Tests	ca. 1,00 €
Gesamtkosten: ca. 9,96 €

