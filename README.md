# 🌌 Filtre Passe-Bande Actif (Cellule de Rauch) - Étude Analytique

[![Thème](https://img.shields.io/badge/Thème-Astronomic_Violet_Blue-7b2cbf?style=flat-square)](#)
[![Technologies](https://img.shields.io/badge/Stack-HTML5_%7C_MathJax_%7C_Chart.js-4cc9f0?style=flat-square)](#)
[![Déploiement](https://img.shields.io/badge/Deploy-GitHub_Pages-success?style=flat-square)](#)

Ce dépôt contient une page web interactive et monolithique dédiée à l'étude analytique approfondie et à la simulation d'un **filtre actif passe-bande du second ordre (Topologie de Rauch)**. 

Le projet a été conçu pour allier rigueur académique et design UI moderne, avec un thème sombre inspiré de l'esthétique "Astronomic Google Pixel Violet Blue".

## 📑 Sommaire
- [Aperçu du Projet](#aperçu-du-projet)
- [Fonctionnalités Principales](#fonctionnalités-principales)
- [Contexte Académique](#contexte-académique)
- [Instructions de Déploiement](#-instructions-de-déploiement-important)
- [Crédits](#crédits)

## 🚀 Aperçu du Projet

L'objectif de cette page est de fournir une démonstration complète du comportement de la cellule de Rauch (3 résistances, 2 condensateurs), un montage crucial dans le conditionnement de signaux pour les systèmes automatisés. La page inclut le schéma électrique précis, les démonstrations mathématiques de bout en bout rendues au format LaTeX, et une simulation visuelle de sa réponse fréquentielle.

## ✨ Fonctionnalités Principales

* 🎨 **Design Thématique immersif** : Interface "Dark Space" avec des effets de lueur néon (Violet/Bleu) pour une lisibilité optimale.
* 📐 **Schéma Vectoriel (SVG) Intégré** : Représentation précise de la topologie exacte de Rauch ($R_1, R_2, R_3$ et $C_1, C_2$) dessinée entièrement en code pur, sans images externes.
* 🧮 **Démonstrations Analytiques (MathJax)** : Explications pas-à-pas avec un rendu mathématique professionnel incluant :
    * L'interprétation de l'AOP idéal et la masse virtuelle.
    * L'application du théorème de Millman à partir des équations nodales.
    * L'identification de la forme canonique (Fréquence propre, Facteur de qualité, Gain).
    * Les équations finales du Module et de la Phase.
* 📊 **Diagrammes de Bode Séparés** : Tracés interactifs générés via **Chart.js** :
    * Un graphique dédié au Gain (en dB) illustrant les pentes d'atténuation.
    * Un graphique dédié à la Phase (en degrés) illustrant le déphasage caractéristique.

## 🎓 Contexte Académique

Ce projet a été réalisé dans le cadre du module d'**Électronique Analytique / Systèmes Automatisés**. Il vise à démontrer l'application pratique et la modélisation mathématique des filtres actifs utilisés dans l'industrie pour isoler les signaux utiles des bruits parasites.

* **Présenté à :** Dr. Laib

## ⚡ Instructions de Déploiement (Important)

Ce projet est un fichier HTML monolithique (tout-en-un). Pour le déployer correctement et instantanément sur GitHub Pages, suivez ces étapes :

1. Ajoutez le fichier `index.html` à la racine de votre dépôt.
2. **Crucial :** Créez un fichier vide nommé exactement **`.nojekyll`** à la racine de votre dépôt. Cela empêche GitHub d'utiliser son moteur de construction par défaut (qui peut bloquer ou ralentir le déploiement de fichiers HTML purs).
3. Allez dans les **Settings** de votre dépôt > **Pages**.
4. Sélectionnez la branche `main` (ou `master`) et le dossier `/ (root)`, puis sauvegardez.
5. Votre site sera en ligne en quelques secondes !

## 👨‍💻 Crédits

**Créé et développé par :** Dahane Ahmed Lamine
