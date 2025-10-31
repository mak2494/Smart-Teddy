# 🧸 Smart Teddy – Medizinischer Begleit-Teddy für Kinder  

## 🌟 Projektbeschreibung  
**Smart Teddy** ist ein interaktiver Begleit-Teddy, der Kindern während medizinischer Untersuchungen hilft, sich zu beruhigen und ihr Wohlbefinden zu kommunizieren.  
Er kombiniert Sensorik, Audioausgabe und visuelle Feedbacksysteme, um Stress zu reduzieren und medizinisches Personal bei der Einschätzung des kindlichen Zustands zu unterstützen.  

## ⚙️ Funktionen  
- ❤️ **Pulsmessung:** Erfassung des Herzschlags über einen optischen Pulssensor (MAX30102).  
- 🌡️ **Temperaturmessung:** Messung der Körpertemperatur über einen Temperatursensor (MLX90614).  
- 🔊 **Audioausgabe:** Eingebauter Lautsprecher spielt beruhigende Musik oder Geräusche ab.  
- 😊 **Schmerzskala:** Mehrere Buttons ermöglichen dem Kind, sein Schmerzempfinden auf einer Skala anzugeben.  
- 💡 **Atemrhythmus-LEDs:** Eine sanft pulsierende LED-Anzeige zeigt den Atemrhythmus und hilft dem Kind, ruhig zu atmen.  Diese kann sich eventuell abhängig von der Pulsmessung verändern um den Kind einen individuellen Atemrhythmus zu zeigen. 

## 🎯 Ziel  
Der Smart Teddy soll Kinder emotional unterstützen, Angst abbauen und Ärzt:innen durch einfache Biofeedback-Signale (Puls, Temperatur, Schmerzskala) bei der Beurteilung des Zustands helfen.  

## 🧠 Technische Umsetzung  
| Komponente | Beschreibung |
|-------------|---------------|
| **Mikrocontroller** | ESP32 |
| **Sensoren** | Pulssensor (MAX30102), Temperatursensor (MLX90614) |
| **Ausgabe** | Lautsprecher, LED-Streifen |
| **Bedienung** | Buttons für Schmerzskala |
| **Programmiersprache** | MicroPython |

## 🚀 Erweiterungsideen  
- 📡 Bluetooth- oder WLAN-Verbindung zur Datenübertragung an medizinisches Personal  
- 📱 App Verbindung für Datenauswertung, Visualisierung und Anpassung der Ausgaben des Teddys
    - 🧾 Logging und Visualisierung der Vitaldaten  
    - 🎵 Anpassbare Atemübungen und Musikprogramme  

## 👩‍⚕️ Nutzen  
Der **Smart Teddy** hilft dabei,  
- die Angst und Nervosität von Kindern während Untersuchungen zu reduzieren,  
- medizinisches Personal mit Echtzeitdaten zu unterstützen,  
- spielerisch die Kommunikation über Schmerzen zu erleichtern.  


