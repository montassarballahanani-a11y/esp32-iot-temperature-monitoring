 # ESP32 IoT — Surveillance de température et d'humidité

## Présentation du projet

Développement d'un système embarqué IoT permettant de surveiller la température et l'humidité à l'aide d'un ESP32 et d'un capteur DHT22.

Le système transmet les mesures via Wi-Fi vers la plateforme cloud ThingSpeak pour leur visualisation sous forme de graphiques.

**Projet personnel réalisé en simulation avec Wokwi.**

## Technologies utilisées

- ESP32 — Microcontrôleur avec Wi-Fi
- C++ / Arduino
- DHT22 — Capteur de température et d'humidité
- LED rouge — Alerte visuelle
- Wi-Fi et protocole HTTP
- ThingSpeak — Plateforme IoT
- Wokwi — Simulation électronique

## Fonctionnalités

- Mesure automatique de température et d'humidité
- Affichage des valeurs dans le Serial Monitor
- Activation de la LED lorsque la température atteint 30 °C
- Message d'alerte lorsque l'humidité atteint 70 %
- Connexion Wi-Fi de l'ESP32
- Envoi des mesures vers ThingSpeak toutes les 20 secondes
- Visualisation des données à travers deux graphiques

## Architecture du système

DHT22 → ESP32 → Wi-Fi → ThingSpeak → Dashboard

## Organisation des fichiers

- `sketch.ino` : programme Arduino/C++
- `diagram.json` : composants et branchements Wokwi
- `README.md` : documentation du projet

## Sécurité

La clé d'écriture ThingSpeak n'est pas incluse dans ce dépôt public. Pour utiliser le programme, remplacer `YOUR_WRITE_API_KEY` par sa propre clé privée dans un environnement non public.

## Compétences développées

Programmation embarquée, acquisition de données, gestion des capteurs, automatisation, communication Wi-Fi, requêtes HTTP et intégration cloud IoT.
