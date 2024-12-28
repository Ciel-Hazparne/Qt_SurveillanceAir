# Projet 2023 Surveillance de la qualité de l’air dans une salle de classe
**Alex, développement Qt**

## Mission
Mon travail dans ce projet consiste à lire les données d’entrée de température, d'hygrométrie et de CO2 d’un capteur SCD30 branché sur une carte MKR 1010.
Je dois envoyer ces données dans une API REST afin de les historiser dans la BDD.
Ces mesures doivent également être envoyées sur MQTT.
Je dois lire une consigne seuil CO2 sur MQTT et écrire une commande relais si la mesure de CO2 est supérieure à cette consigne.
