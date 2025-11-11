![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![License](https://img.shields.io/badge/license-private-red.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)


# 📚 Manhwa Text Extractor

Outil d'extraction de texte pour manhwa avec OCR coréen et anglais.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Status](https://img.shields.io/badge/status-privé-red)

## 🎯 Fonctionnalités

- ✅ **Extraction OCR** : Reconnaissance automatique du texte coréen et anglais
- ✅ **Interface graphique** : Interface moderne et intuitive
- ✅ **Support multi-formats** : Images (.jpg, .png, .jpeg)
- ✅ **Export automatique** : Génération de fichiers .docx structurés
- ✅ **Progression en temps réel** : Barre de progression et status
- ✅ **Prétraitement intelligent** : Amélioration de la qualité OCR

## 🖼️ Aperçu
```
┌──────────────────────────────────┐
│  📚 Manhwa Text Extractor       │
├──────────────────────────────────┤
│  [Sélectionner dossier] 📁      │
│                                  │
│  ☑ 🇰🇷 Coréen  ☐ 🇬🇧 Anglais    │
│                                  │
│  [▶ EXTRAIRE LE TEXTE]          │
│                                  │
│  Progress: ████████░░ 80%       │
└──────────────────────────────────┘
```

## 📥 Installation

### Prérequis
- Python 3.8 ou supérieur
- Windows / macOS / Linux

### Étape 1 : Cloner le repository
```bash
git clone https://github.com/VOTRE-USERNAME/manhwa-text-extractor.git
cd manhwa-text-extractor
```

### Étape 2 : Installer les dépendances
```bash
pip install -r requirements.txt
```

### Étape 3 : Lancer l'application
```bash
python manhwa_gui.py
```

## 🚀 Utilisation

1. **Lancez l'application** : `python manhwa_gui.py`
2. **Cliquez sur "Parcourir..."** et sélectionnez le dossier contenant les images du manhwa
3. **Cochez les langues** à extraire (Coréen et/ou Anglais)
4. **Cliquez sur "▶ EXTRAIRE LE TEXTE"**
5. **Attendez** que l'extraction se termine (progression affichée)
6. **Récupérez** le fichier `.docx` généré dans le dossier source

## 📋 Exemple de résultat

Le document Word généré contient :
```
Page 1
1. 환영한다 티렌~
2. 여기는
3. 이란다
...

Page 2
1. [Textes de la page 2]
...
```

## 🛠️ Technologies utilisées

- **PaddleOCR** : Moteur OCR multilingue
- **OpenCV** : Traitement d'images
- **Python-docx** : Génération de documents Word
- **Tkinter** : Interface graphique
- **NumPy** : Traitement de données

## 📦 Versions compilées (.exe)

Les versions exécutables sont disponibles pour les collaborateurs autorisés.

### Version Simple (150 MB)
- Support images uniquement
- Aucune installation requise
- Double-clic et ça marche

### Version Complète (200 MB) 
- Support images + PDF
- Poppler inclus
- Installation automatique

## 🔧 Développement

### Structure du projet
```
manhwa-text-extractor/
├── manhwa_gui.py           # Interface graphique principale
├── extract_final.py        # Script CLI optimisé
├── requirements.txt        # Dépendances Python
└── README.md              # Documentation
```

### Contribuer

Ce projet est **privé**. Seuls les collaborateurs invités peuvent contribuer.

## 📊 Performance

- **Temps de traitement** : ~40 secondes par page longue (webtoon)
- **Précision OCR** : 90-95% (selon qualité de l'image)
- **Formats supportés** : .jpg, .jpeg, .png

## ❓ FAQ

**Q : Quel est le temps de traitement moyen ?**  
R : Environ 5-10 minutes pour un chapitre de 8 pages.

**Q : Le texte anglais est-il bien détecté ?**  
R : Oui, mais l'OCR coréen est optimisé pour les manhwa coréens.

**Q : Puis-je traiter des PDF ?**  
R : La version CLI supporte les PDF. Pour la GUI, utilisez la version complète avec Poppler.

**Q : Les données sont-elles envoyées en ligne ?**  
R : Non, tout le traitement est 100% local.

## 🔒 Confidentialité

- ✅ **Projet privé** : Réservé aux collaborateurs autorisés
- ✅ **Traitement local** : Aucune donnée envoyée en ligne
- ✅ **Pas de télémétrie** : Aucun tracking

## 👥 Équipe

- **Développeur principal** : [Votre nom]
- **Collaborateur** : [Nom ami]

## 📝 Changelog

### v1.0.0 (2025-01-09)
- ✨ Interface graphique complète
- ✨ Support OCR coréen et anglais
- ✨ Export .docx automatique
- ✨ Barre de progression temps réel
- ✨ Prétraitement d'images optimisé

## 📄 Licence

Ce projet est privé et protégé. Tous droits réservés.

---

**Développé avec ❤️ pour les lecteurs de manhwa**
