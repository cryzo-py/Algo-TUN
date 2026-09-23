![Téléchargements](https://img.shields.io/github/downloads/cryzo-py/Algo-TUN/total?color=blue&label=T%C3%A9l%C3%A9chargements)
# Algo-TUN 💻🇹🇳

[![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![GUI](https://img.shields.io/badge/GUI-PySide6%20%2F%20Qt6-41CD52?style=flat&logo=qt&logoColor=white)](https://www.qt.io/)
[![Tests](https://img.shields.io/badge/Tests-58%2F58%20Passing-brightgreen?style=flat&logo=pytest&logoColor=white)](tests/)
[![Convention](https://img.shields.io/badge/Convention-Tunisie%202024%2F2025-C8102E?style=flat)](https://www.education.gov.tn/)
[![License](https://img.shields.io/badge/License-Freeware%20Éducatif%20(Propriétaire)-red?style=flat)](LICENSE)

**Algo-TUN** est l'environnement de développement et d'apprentissage algorithmique de référence, **100% conforme aux programmes et directives officielles du Ministère de l'Éducation Tunisienne**.

Conçu spécifiquement pour les **lycéens (sections Sciences de l'Informatique, Mathématiques, Sciences Expérimentales, Économie-Gestion, Technique)** et les **enseignants**, Algo-TUN transforme l'apprentissage de l'algorithmique en une expérience visuelle, interactive, pédagogique et rigoureuse.

---

## ✨ Nouveautés Majeures de la Version 3.0

- 🎬 **Refonte Intégrale du Tournage à la Main** :
  - Fin du découpage vertical écrasé : le **Tableau Historique d'évolution** et la **Mémoire Virtuelle Graphique** disposent chacun de **100% de la hauteur du panneau** via un sélecteur intuitif `[ 📋 Tableau │ 👁️ Visuel ]`.
  - **Barre de transport VCR ultra-compacte** : `[ ⏪ ] [ ⏭ ] [ ▶ ] [ ⏩ ] [ ⏹ ]` avec rendu net sans rognage d'icônes.
  - **Accès direct et raccourcis dédiés** :
    - `▶▏ Tournage (Tableau)` (`F10`) — Icône adaptative sombre/claire.
    - `▶▏ Tournage (Visuel)` (`Shift+F10`) — Icône rouge vif distinctive.
- 🎨 **Ergonomie Sombre & Logo Transparent Haute Définition** :
  - Nouveau logo vectoriel 32-bit RGBA sans arrière-plan blanc parasite.
  - Intégration naturelle dans le thème sombre (`#1E293B`, `#252526`) et le splash screen.
- 🛡️ **Banc d'Épreuve Industriel (58 tests automatisés)** :
  - Couverture complète de l'interpréteur, de la récursivité, des pointeurs/références, de la sémantique et de la GUI.
  - Intégration continue prête pour GitHub Actions.

---

## 🎯 Fonctionnalités Principales

### 1. 🖥️ Éditeur Intelligent & Normalisation Temps Réel
- Coloration syntaxique conforme aux manuels scolaires tunisiens.
- **Auto-indentation intelligente à 3 espaces** lors de la frappe.
- **Normalisation automatique** : conversion à la volée des opérateurs (`<-` vers `←`, `!=` vers `≠`, `<=` vers `≤`, `>=` vers `≥`, `dans` vers `∈`).
- Insertion rapide des squelettes algorithmiques (`Si`, `Pour`, `Tant que`, `Répéter...Jusqu'à`, `Selon`, `Fonction`, `Procédure`).
- Assistant interactif de saisie pour les sélecteurs complexes (`Selon ... Faire`).

### 2. 🛡️ Validateur Sémantique & Directives Pédagogiques
- Analyse en temps réel détectant les erreurs avant l'exécution :
  - Objets non déclarés ou conflits de portée (global vs local vs types).
  - Contrôle strict des déclarations dans le **TDO** (Objets globaux), **TDNT** (Nouveaux Types) et **TDOL** (Objets locaux).
  - Rejet des affectations aux constantes (`Constante = ...`).
  - Vérification des signatures et types de retour des fonctions et procédures.
  - Contrôle des indices de tableaux (1D, 2D) et chaînes.

### 3. ⚙️ Machine Virtuelle & Interpréteur Pédagogique
- Exécution directe avec console d'E/S interactive (`Lire`, `Écrire`, `Écrire_nl`).
- Prise en charge des types scalaires (`Entier`, `Réel`, `Booléen`, `Caractère`, `Chaîne`).
- Support complet des structures composées :
  - **Tableaux et Matrices** : initialisation, parcours, tri.
  - **Enregistrements (Records)** : champs typés et imbriqués.
- Sous-programmes avancés :
  - Passage par valeur et par **référence stricte (`@` / `Var`)**.
  - **Récursivité** avec pile d'appels complète.
- Simulation des fichiers textes (`Ouvrir`, `Lire_ligne`, `Fin_fichier`, etc.).

### 4. 🎬 Tournage à la Main (VCR + Mémoire Graphique)
- **Tableau d'évolution pas-à-pas** : traçage de chaque variable, expression et instruction exécutée avec numéro de ligne.
- **Visualiseur de mémoire virtuelle** : représentation en temps réel des cases mémoires, pointeurs et contextes d'appels.
- Rembobinage avant/arrière (`Step Backward` / `Step Forward`) pour comprendre les erreurs de logique.

### 5. 📚 Bibliothèque d'Algorithmes Types du Baccalauréat
- Accès instantané (`Ctrl+Shift+L`) aux algorithmes classiques du programme tunisien :
  - Tris : Tri à bulles, Tri par sélection, Tri par insertion.
  - Arithmétique : Test de primalité, Crible d'Ératosthène, PGCD (Euclide), PPCM, Diviseurs.
  - Chaînes & Nombres : Palindrome, Anagramme, Conversion binaire/décimale.
  - Matrices : Transposition, Produit matriciel, Recherche de selle.

### 6. 📤 Exportations & Impression Haute Fidélité
- **Export PDF officiel** : Document propre avec en-tête, algorithme, TDO, TDNT et TDOL prêt à être distribué aux élèves ou imprimé.
- **Export Word (`.docx`)** : Document éditable avec styles de tableaux professionnels.
- **Export Texte brut structuré (`.txt`)** : Fichier ASCII clair et portable.

---

## ⌨️ Raccourcis Clavier Essentiels

| Raccourci | Action |
| :--- | :--- |
| `F5` | **Vérifier** la structure et la sémantique de l'algorithme |
| `F6` | **Exécuter** l'algorithme d'un trait |
| `F10` | **Tournage à la main** (Vue Tableau historique) |
| `Shift + F10` | **Tournage à la main** (Vue Mémoire graphique interactive) |
| `F11` | **Tournage en Popup** autonome |
| `Shift + F6` | **Arrêter** l'exécution en cours |
| `Ctrl + L` | **Formater / Normaliser** le code automatiquement |
| `Ctrl + Shift + L`| Ouvrir la **Bibliothèque** d'algorithmes du Bac |
| `Ctrl + T` | Basculer entre **Mode Clair** et **Mode Sombre** |
| `Ctrl + Shift + P`| **Exporter en PDF** |
| `Ctrl + F` | Boîte de recherche et remplacement |

---

## 🚀 Installation & Démarrage

### Installation & Distribution Officielle (Windows 10 / 11)

1. Téléchargez la dernière version officielle de l'installateur depuis la section [Dernière Release (Latest)](https://github.com/cryzo-py/Algo-TUN/releases/latest).
2. Lancez le fichier téléchargé **`Algo-TUN_V3.0_Setup.exe`**.
3. Suivez l'assistant d'installation (raccourcis bureau, menu Démarrer et association automatique des fichiers algorithmiques `.alg`).
4. Lancez **Algo-TUN** directement et commencez à programmer !

> **Note de distribution :** Algo-TUN est distribué exclusivement sous forme d'exécutable et d'installateur binaire officiel signé par l'auteur. Le code source du projet est privé et protégé.

---

## ⚖️ Licence et Droits d'Auteur

**Auteur & Concepteur :** Fares Bel Haj Ali  
Ce logiciel est distribué sous les termes d'un **Contrat de Licence Utilisateur Final (CLUF) Propriétaire et Gratuit (Freeware Éducatif)**.

- ✅ **Gratuit pour l'Éducation** : Utilisation libre et gratuite pour tous les élèves, enseignants, lycées et universités de Tunisie.
- 🔒 **Code Source Fermé & Non Accessible** : Le code source n'est pas public et demeure la propriété exclusive de l'auteur.
- ⛔ **Interdictions formelles** : Ingénierie inverse, décompilation, modification, revente commerciale ou intégration dans des logiciels tiers sans autorisation écrite préalable expresse de l'auteur.

*Consultez le fichier [LICENSE](LICENSE) pour le contrat officiel complet.*

---

## 📞 Contact & Support

Pour toute question pédagogique, suggestion d'amélioration ou signalement d'anomalie :
- 📧 **Email** : `belhadj.fares@gmail.com`
- 📱 **Téléphone** : `+216 22 39 26 46`
- 🌐 **Région** : Tunis, Tunisie

