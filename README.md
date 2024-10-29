# Activité Pratique N°1 : Architecture Orientée Événements

## Partie 1 : Kafka

Dans cette première partie, nous avons exploré le fonctionnement de Kafka, une plateforme de streaming distribuée, et abordé les étapes nécessaires pour l’installer sous Windows. Nous avons également configuré les fichiers et lancé les services requis.

### Kafka : Présentation

Kafka est une plateforme de streaming distribuée couramment utilisée sur les systèmes Unix, bien qu’elle soit compatible avec Windows. Cette technologie est conçue pour gérer des flux de données en temps réel et à grande échelle, ce qui en fait un composant essentiel pour les architectures basées sur les événements. Elle permet de collecter, stocker, et distribuer des données de manière fiable.

### Installation de Kafka sur Windows et Démarrage

Pour installer Kafka sur un système Windows, nous avons suivi les étapes suivantes :

1. **Vérification de Java** : Kafka nécessite Java pour fonctionner. Nous avons vérifié la présence de Java sur notre système. Si absent, nous avons téléchargé la version la plus récente de Java JDK depuis [le site d'Oracle](https://www.oracle.com/java/technologies/javase-downloads.html).

2. **Configuration de JAVA_HOME** : Une fois Java installé, nous avons configuré la variable d'environnement `JAVA_HOME`. Pour la vérifier, nous avons exécuté :
   ```shell
   echo %JAVA_HOME%

