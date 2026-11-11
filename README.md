# Projet d'Algorithmique et Structures de Données

Réalisé par Kerrian et Ethann ALLAIN

# Description

Le projet est réalisé en Java 1.8, et s'utilise via le répertoire parent au projet.

La compilation du projet s'effectue avec la commande suivante :

```shell
javac -source 1.8 -target 1.8 -d BitmapImageGenerator/bin BitmapImageGenerator/src/*.java
```

Deux modes de lancement du projet sont disponibles :

- Le mode non-intéractif qui nécessite de renseigner les arguments nécessaires dans la commande d'exécution.
- Le mode intéractif qui demande pour commencer l'image à traiter, puis les actions à effectuer sur l'image.

Les modes de compression proposés sont `Lambda` et `Phi`.

Les images générées sont automatiquement sauvegardées dans le répertoire `BitmapImageGenerator/target/`.

## Mode non-intéractif

```shell
java -classpath BitmapImageGenerator/bin Main <imagePath> <compressionMethod> <parameter>
```

## Mode intéractif

```shell
java -classpath BitmapImageGenerator/bin Main
```
