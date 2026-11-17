# LabTrack TN

*Your Health, One Place, Better Understanding.*

Plateforme web de dossier de santé personnel et de gestion des résultats de laboratoire, réalisée dans le cadre du module projet technologies web 2A (ESPRIT, 2026-2027).

## Description

**LabTrack TN** est une application web qui permet à un patient de centraliser, comprendre et suivre dans le temps ses données de santé en Tunisie.

### Objectif

Offrir un espace numérique sécurisé qui réunit les résultats de laboratoire, les documents médicaux, les ordonnances et les rendez-vous dans un seul compte.

### Problème résolu

Les informations médicales du patient sont dispersées : rapports papier, PDF, portails de laboratoires, ordonnances. Il est difficile de les comparer et de suivre leur évolution.

### Principales fonctionnalités

- Dossier de santé centralisé
- Import de PDF ou saisie manuelle des valeurs de laboratoire (multi-laboratoires)
- Graphiques d'évolution des biomarqueurs et comparaison dans le temps
- Timeline de santé
- Explications pédagogiques des biomarqueurs (sans diagnostic)
- Gestion des médicaments et des rendez-vous
- Rapports PDF pour le médecin
- Back Office d'administration (utilisateurs, référentiel des biomarqueurs, contenu éducatif, statistiques)

## Table des Matières

- [Installation](#installation)
- [Utilisation](#utilisation)
- [Contributions](#contributions)
- [Licence](#licence)

## Installation

1. Clonez le repository :
   ```bash
   git clone https://github.com/bouattourfatma12-debug/readme-guide.git
   cd readme-guide
   ```

2. Si vous utilisez WAMP ou XAMPP :

* Placez le projet dans le dossier www (WAMP) ou htdocs (XAMPP).

* Démarrez Apache et MySQL depuis l'interface de WAMP/XAMPP.

* Accédez au projet via http://localhost/readme-guide.

## Utilisation

### Installation de PHP

Pour utiliser ce projet, vous devez installer PHP. Voici les étapes :

1. Téléchargez PHP à partir du site officiel : [PHP - Téléchargement](https://www.php.net/downloads.php).

2. Installez PHP en suivant les instructions spécifiques à votre système d'exploitation :

   - Pour **Windows**, vous pouvez utiliser [XAMPP](https://www.apachefriends.org/fr/index.html) ou [WampServer](http://www.wampserver.com/).
   - Pour **macOS**, vous pouvez utiliser [Homebrew](https://brew.sh/), puis exécuter la commande suivante dans le terminal :
     ```bash
     brew install php
     ```
   - Pour **Linux**, vous pouvez installer PHP via le gestionnaire de paquets. Par exemple, sur Ubuntu :
     ```bash
     sudo apt update
     sudo apt install php
     ```

3. Vérifiez l'installation de PHP en exécutant la commande suivante dans votre terminal :
   ```bash
   php -v
   ```

## Contributions

Nous remercions tous ceux qui ont contribué à ce projet !

### Contributeurs

Les personnes suivantes ont contribué à ce projet :

- [Étudiant1](https://github.com/utilisateur1) - Module Résultats de laboratoire
- [Étudiant2](https://github.com/utilisateur2) - Module Dossiers médicaux
- [Étudiant3](https://github.com/utilisateur3) - Module Médicaments

Si vous souhaitez contribuer, suivez les étapes ci-dessous pour faire un **fork**, créer une nouvelle branche et soumettre une **pull request**.

### Comment contribuer ?

1. **Fork le projet** : Allez sur la page GitHub du projet et cliquez sur le bouton **Fork** dans le coin supérieur droit pour créer une copie du projet dans votre propre compte GitHub.

2. **Clonez votre fork** : Clonez le fork sur votre machine locale :
   ```bash
   git clone https://github.com/votre-utilisateur/readme-guide.git
   cd readme-guide
   ```

3. **Créez une branche** : `git checkout -b ma-fonctionnalite`

4. **Validez et poussez vos modifications** :
   ```bash
   git add .
   git commit -m "Description de la modification"
   git push origin ma-fonctionnalite
   ```

5. **Ouvrez une pull request** depuis votre fork vers le repository principal.

## Licence

Ce projet est sous la licence **MIT**. Pour plus de détails, consultez le fichier [LICENSE](./LICENSE).

### Détails sur la licence MIT

La licence MIT est une licence de logiciel libre permissive : elle autorise l'utilisation, la modification et la redistribution du code, à condition de conserver la mention de copyright.
