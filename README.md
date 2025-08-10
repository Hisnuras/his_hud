# 🚀 HUD FiveM — en UI Vue 3

[![Version](https://img.shields.io/badge/version-1.0-blue.svg)](https://github.com/Hisnuras/his_hud)

---

## 🔗 Liens utiles

🌍 **Site web** : [https://hisnuras.github.io/HisnurasWeb/](https://hisnuras.github.io/HisnurasWeb/)  
🛒 **Boutique Tebex** : [https://hisnuras-store.tebex.io](https://hisnuras-store.tebex.io)  
💬 **Discord** : [https://discord.gg/NDwJDgKfhj](https://discord.gg/NDwJDgKfhj)

---

## ✨ Fonctionnalités

- 🥪 **Jauge de Faim** — Mise à jour en temps réel.  
- 💧 **Jauge de Soif** — Synchronisée avec l’état du joueur.  
- 🌐 **Système multilingue** — Géré via un fichier de traduction.  
- 💾 **Sauvegarde en base de données** — Préférences HUD persistantes entre les sessions.  
- 🎨 **Personnalisation** — Couleurs et affichage configurables par joueur.

---

## 🛠 Technologies

- **LUA** — Logique serveur/client FiveM  
- **SQL** — Stockage des paramètres et données joueurs  
- **Vue 3** — UI moderne et réactive

---

## 📦 Installation

1. Allez dans le dossier resource de votre serveur FiveM
2. **Cloner le dépôt** :
    faite click droit "ouvrir dans le terminal" ensuite entrer la commande suivante
    ```bash
    git clone https://github.com/Hisnuras/his_hud.git
    ```
3.  importe le fichier .sql dans ta base de données (fichier .sql fourni)

4.  Ajouter à server.cfg :
    ```bash
    ensure his_hud
    ```