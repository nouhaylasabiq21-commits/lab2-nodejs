🌡️ Dashboard météo temps réel
📖 Description

Application web en temps réel permettant d’afficher des données météorologiques (température et pluie) à partir d’un fichier CSV.

Les données sont envoyées progressivement via WebSocket et mises à jour dynamiquement dans un tableau et des graphiques.

🚀 Fonctionnalités
📡 Transmission des données en temps réel (WebSocket)
📊 Graphiques dynamiques (températures et pluie)
📋 Tableau mis à jour automatiquement
⏸️ Bouton Pause / Reprendre
🔄 Bouton Reset
🌙 Interface en dark mode
🛠️ Technologies utilisées
Node.js
WebSocket (ws)
CSV → JSON (csvtojson)
Chart.js
JavaScript / HTML / CSS
▶️ Démo

Une démonstration montre :

l’arrivée des données toutes les 3 secondes
la mise à jour des graphiques
l’utilisation des boutons (Pause / Reset)

https://github.com/user-attachments/assets/d81843d1-75d9-4347-b992-5e9700a22cf8

🎯 Objectif

Ce projet permet de comprendre :

la communication temps réel client / serveur
l’utilisation des WebSockets
la manipulation de données CSV
l’affichage dynamique avec JavaScript
📂 Structure
Serveur WebSocket (Node.js)
Interface web (HTML)
Fichier de données CSV

💡 Projet réalisé dans le cadre d’un TP sur les applications temps réel.
