# Hvad er LoRa?

**LoRa** (Long Range) er en trådløs kommunikationsteknologi, der gør det muligt at sende små mængder data over store afstande med lavt strømforbrug. Den er særligt velegnet til IoT-enheder, sensornetværk og batteridrevne løsninger – såsom Meshtastic.

---

## 📡 Teknisk overblik

| Egenskab             | Beskrivelse                                                                 |
|----------------------|------------------------------------------------------------------------------|
| **Modulationstype** | Chirp Spread Spectrum (CSS)                                                  |
| **Datahastighed**   | 0.3 kbps – 50 kbps                                                            |
| **Typisk rækkevidde** | 2–15 km (afhængigt af terræn og antennevalg)                                |
| **Frekvensbånd**    | ISM-bånd: 433 MHz, 868 MHz (EU), 915 MHz (US)                                |
| **Sendeeffekt**     | Op til +20 dBm (afhængigt af landeregler)                                    |
| **Strømforbrug**    | Meget lavt – egnet til lang batterilevetid                                   |
| **Båndbredde**      | Typisk 125 kHz, men kan konfigureres op til 500 kHz                           |

---

## 🧠 Hvordan fungerer LoRa?

LoRa bruger **chirp spread spectrum** i stedet for klassisk digital modulation. Dette gør signalet mere robust og i stand til at nå længere – selv ved lav signalstyrke.

Fordelene ved denne metode inkluderer:

- Kommunikation **under støjgulvet**
- Stor rækkevidde med minimal sendeeffekt
- Høj modstandsdygtighed overfor støj og interferens

---

## ✅ Fordele

- 📶 Lang rækkevidde (op til 15 km under gode forhold)
- 🔋 Lavt strømforbrug – ideel til batteridrevne sensorer og noder
- 🛡 Robust over for interferens
- 🌐 Licensfri brug i ISM-båndet i Europa
- ⚙️ Konfigurerbar spredningsfaktor, båndbredde og sendeeffekt

---

## ❌ Ulemper

- 🐢 Lav datahastighed – ikke egnet til video, billeder eller realtidslyd
- 📦 Begrænset beskedstørrelse (typisk under 250 bytes pr. overførsel)
- ⏱ Duty cycle-begrænsninger (du må kun sende en begrænset procentdel af tiden)
- 💬 Ikke kompatibelt med Wi-Fi/Bluetooth uden gateway

---

## 🎯 Typiske anvendelser

- Landbrug og fjernovervågning
- Smarte byer (smart cities)
- Vand- og el-målere
- Bygningssensorer
- **Meshtastic mesh-kommunikation**
- Dronetracking og GPS-noder
