# Termostat Digital cu 80C51, DS18B20 și LCD

Acest proiect reprezintă un sistem de control al temperaturii (termostat) dezvoltat în limbajul **C** pentru microcontrolerul **80C51**. Simularea completă a circuitului hardware este realizată în **Proteus**, iar dezvoltarea și compilarea codului software în **Keil uVision**.

Sistemul menține temperatura într-un interval dorit (configurabil între 5°C și 40°C), acționând un releu pentru pornirea/oprirea unui element de încălzire și semnalizând starea prin LED-uri.

---

## 🛠️ Componente Utilizate

* **Microcontroler:** Intel 80C51 / AT89C51
* **Senzor de temperatură:** DS18B20 (Protocol One-Wire)
* **Afișaj:** LCD LM016L (2x16 caractere, interfață pe 8 biți)
* **Actuator:** Releu de 5V (comandat printr-un tranzistor NPN 2N2222 și diodă de protecție 1N4148)
* **Semnalizare:** 1x LED Roșu (Încălzire activă), 1x LED Albastru (Sistem în așteptare / Temperatură OK)
* **Interfață utilizator:** Tastatură simplă cu 2 sw (`UP`, `DOWN`)
