# Beescale
🐝 BeeScale : pèse-ruche connecté basé sur ESP32, ESPHome et Home Assistant. Suivi du poids, de la répartition sur 4 pesons et de la météo du rucher, avec deep sleep pour économiser la batterie.

✨ Fonctionnalités

⚖️ Pesée précise grâce à 4 pesons (un par coin de la ruche)

📊 Répartition du poids pour détecter une ruche qui penche ou un peson défaillant

🌡️ Mesures extérieures : température, humidité, pression atmosphérique

🔋 Deep sleep : grande autonomie sur batterie, durées d'éveil et de sommeil réglables

📶 Wi-Fi flexible : plusieurs réseaux préenregistrés et portail captif de secours

🛡️ Calibration sécurisée : confirmation avant la mise à zéro des pesons

🏠 Plug and play : détection automatique dans Home Assistant, package et dashboard prêts à l'emploi

🧰 Matériel
Élément	Remarque
ESP32	Le deep sleep et le Wi-Fi sont gérés par ESPHome
4 pesons (cellules de charge)	Un par coin de la ruche
Module(s) HX711	Convertisseur pour les pesons
Capteur BME280 (ou équivalent)	Température, humidité, pression
Batterie + panneau solaire (optionnel)	Pour un rucher sans alimentation
Boîtier étanche	Protection contre la pluie


Blueprint automatisation: 
[![Importer le blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2DrGently%2Fbeescale%2Fblob%2Fmain%2Fhomeassistant%2Fblueprints%2Fautomation%2Fbeescale_settings.yaml)
