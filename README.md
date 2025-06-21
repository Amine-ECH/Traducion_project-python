# 🧠 Traducteur DAI – Application de Traduction Multilingue avec Voix

Ce projet est une application de bureau Python créée avec **Tkinter**, qui permet de traduire du texte entre plusieurs langues, d’écouter la traduction via **gTTS**, et de sauvegarder l’historique des traductions.

---

## 🛠 Fonctionnalités

- 🌍 Traduction automatique entre :
  - Français
  - Anglais
  - Espagnol
  - Arabe
  - Allemand
- 🗣 Lecture vocale de la traduction (gTTS + Pygame)
- 💾 Sauvegarde automatique de l’historique (fichier `history.json`)
- 📋 Copier le texte traduit en un clic
- ♻ Interface conviviale avec bouton d'initialisation
- ⏳ Page de chargement (Splash Screen)

---

## 🧩 Bibliothèques utilisées

- `tkinter` – Interface graphique
- `deep_translator` – Traduction via Google Translate
- `gTTS` – Text-to-speech Google
- `pygame` – Lecture de l’audio
- `json` – Stockage de l’historique
- `os`, `time`, `datetime`, `io` – Utilitaires

---

## ▶️ Lancement du projet

Assurez-vous d’avoir installé toutes les dépendances :

```bash
pip install deep-translator gtts pygame
```

Ensuite, exécutez le fichier :

```bash
python Trad_project.py
```


---

## 📁 Fichiers importants

- `Trad_project.py` – Code source principal
- `history.json` – Fichier généré automatiquement pour l’historique
- `traduction-pic.ico` – Icône de la fenêtre (à ajouter dans le dossier du projet)

---

## 👨‍💻 Auteur

Projet réalisé par **AMINE ECH-Chiguer**   
2025
