# TP1 Java - Architecture 3 couches

<img width="1914" height="1077" alt="image" src="https://github.com/user-attachments/assets/420d79e1-2639-4395-8b3d-6e41ebb80986" />

## Description
Ce projet illustre une architecture Java en trois couches : DAO, Métier et Présentation. Il permet de séparer la logique métier, l’accès aux données et l’interface utilisateur pour une meilleure maintenabilité.

## Structure du projet
```
TP1/
├── config.txt
├── README.md
├── TP1.iml
└── src/
    ├── dao/
    │   ├── DaoImpl.java
    │   └── IDao.java
    ├── metier/
    │   ├── IMetier.java
    │   └── MetierImpl.java
    └── presentation/
        └── Presentation2.java
```

## Prérequis
- Java JDK 8 ou supérieur
- Un IDE Java (IntelliJ IDEA, Eclipse, NetBeans, etc.)

## Installation et compilation
1. Cloner le projet ou télécharger les fichiers.
2. Ouvrir le dossier dans votre IDE.
3. Compiler le projet :
   - En ligne de commande :
     ```cmd
     javac -d bin src/dao/*.java src/metier/*.java src/presentation/*.java
     ```
   - Ou via l’IDE (Build Project).

## Exécution
- En ligne de commande :
  ```cmd
  java -cp bin presentation.Presentation2
  ```
- Ou via l’IDE (Run Presentation2).

## Exemple d’utilisation
Le programme exécute la classe `Presentation2` qui utilise les couches DAO et Métier pour effectuer des opérations (ex : calcul, gestion de données).

## Auteurs
- Achraf

