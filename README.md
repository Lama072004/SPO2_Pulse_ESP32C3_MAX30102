# 🩺 Mobiles Pulsoxymeter mit GY-MAX30102

## 📌 Projektbeschreibung

Im Rahmen des Moduls **Embedded Systems** wurde ein Pulsoxymeter entwickelt, das auf dem **GY-MAX30102-Sensor** und einem **ESP32-C3-Mini Mikrocontroller** basiert. Ziel war die Messung der **Herzfrequenz** sowie der **arteriellen Sauerstoffsättigung (SpO₂)** mittels optischer Verfahren, wie sie in der medizinischen Diagnostik verwendet werden.

Die Datenverarbeitung erfolgt direkt auf dem Mikrocontroller mithilfe von Embedded-C-Treibern sowie geeigneter **Signalverarbeitungsalgorithmen** zur Filterung und Auswertung der Rohdaten.

> 🔌 Aktuell erfolgt die Ausgabe über die **serielle Schnittstelle** an einen PC.

---

## 🎯 Projektziele

- Messung der **SpO₂** und **Pulsfrequenz**  
- Echtzeit-Signalverarbeitung auf dem ESP32-C3  
- Drahtlose Datenübertragung via **Bluetooth Low Energy (BLE)** *(nicht umgesetzt)*  
- Visualisierung der Messwerte auf dem Smartphone *(nicht umgesetzt)*  
- Energieeffizienter, mobiler Einsatz *(nicht umgesetzt)*

---

## 🚧 Nicht umgesetzte (optionale) Erweiterungen

- 📲 **Bluetooth-Übertragung** an ein Smartphone  
- 📊 **Visualisierung** per Flutter-App  
- 🔋 **Mobiler Akkubetrieb** mit kompaktem Gehäuse  
- 🩻 **Vergleichsmessung** mit professionellem Pulsoxymeter (z. B. Corpuls-System)  
- ❤️‍🔥 **Erkennung von Anomalien** (z. B. Arrhythmien, Tachykardie, Bradykardie) mit Benachrichtigungen

---

## 🧱 Verwendete Komponenten

| Komponente           | Beschreibung                                          | Preis         |
|----------------------|-------------------------------------------------------|---------------|
| **ESP32-C3-Mini**    | Mikrocontroller mit BLE zur Signalverarbeitung        | ca. **5,00 €** |
| **GY-MAX30102**      | Pulsoxymetrie-Sensor mit LEDs & Photodioden           | ca. **3,96 €** |
| **Steckbrett & Kabel** | Für Prototyping und Tests                            | ca. **1,00 €** |

**Gesamtkosten:** ca. **9,96 €**

---

## 📷 Vorschau

*(Hier könntest du ein Bild deines Aufbaus oder ein kurzes GIF einfügen.)*

---

## 🛠 Technologien

- **Embedded C**
- **ESP-IDF / Arduino Core**
- **UART Kommunikation**
- **Signalverarbeitung: Filter & Peaks**
