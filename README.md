# Projet d'Industrie 4.0
Ce projet a été réalisé dans le cadre d'un cours sur l'Industrie 4.0. Il a impliqué l'utilisation d'un microcontrolleur ESP8266 pour collecter des données de température et d'humidité à partir d'un capteur. Le code C++ a été utilisé pour récupérer les données et les envoyer via le protocole MQTT.

## Sommaire
- [Membre de l'équipe](#membre-de-léquipe)
- [Internet des objets (IoT)](#internet-des-objets-iot)
- [Programmation](#programmation)
- [MQTT](#mqtt)
- [Node-RED](#node-red)
- [Conclusion](#conclusion)

## Membre de l'équipe
- Alexandre Petit
- Dylan Bussonnais
- Yannis Lebeau 

## Internet des objets (IoT)
L'utilisation d'un microcontrolleur ESP8266 dans ce projet est un exemple de l'Internet des objets (IoT) en action. Le microcontrolleur permet de connecter un capteur de température et d'humidité à un système de communication en réseau, permettant ainsi de collecter et de partager des données en temps réel. Cette connectivité permet également de contrôler à distance le capteur et les données collectées.

## Programmation
Pour collecter les données du capteur, du code C++ a été développé. Cette utilisation de la programmation pour collecter les données est importante pour l'Industrie 4.0 car elle permet de personnaliser les données collectées selon les besoins de l'application.

## MQTT
Les données collectées ont ensuite été envoyées via le protocole MQTT. MQTT est un protocole de communication en temps réel léger qui est largement utilisé dans l'IoT. Il permet de publier et de souscrire à des données sur un réseau en temps réel, ce qui est crucial pour l'Industrie 4.0 qui nécessite une communication en temps réel entre les différents équipements et systèmes.

## Node-RED
Une fois les données reçues par le serveur MQTT, NodeRED a été utilisé pour les formater, les afficher sous forme de gauges et les renvoyer dans le flux MQTT. NodeRED est un outil de traitement de données en temps réel qui permet de créer des flux de données en utilisant un graphique visuel. Il permet de facilement traiter les données reçues et de les utiliser pour des applications de contrôle et de surveillance.

## Conclusion
En résumé, ce projet a mis en œuvre des concepts clés de l'Industrie 4.0 tels que l'IoT, les technologies de communication en temps réel et les technologies de traitement de données en temps réel pour réaliser une application de surveillance de la température et de l'humidité. Ce projet démontre comment ces technologies peuvent être combinées pour créer des systèmes de surveillance efficaces et personnalisables pour une variété d'applications