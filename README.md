<div align="center">

<img src="https://github.com/user-attachments/assets/1325adff-1a3f-431c-b9ed-7d1dd202babd" alt="Eagle Browser" width="128" height="128">

# Eagle Browser

**Un navigateur rapide, moderne et respectueux de votre vie privée.**

Bloqueur de pubs intégré · Empreinte numérique brouillée · DNS chiffré · Mode Tor · 100 % en français

[![Télécharger](https://img.shields.io/github/v/release/ApollonNeo/eagle-browser?label=T%C3%A9l%C3%A9charger&style=for-the-badge&color=2f80ff)](https://github.com/ApollonNeo/eagle-browser/releases/latest)
![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-0078D6?style=for-the-badge&logo=windows)
![Chromium](https://img.shields.io/badge/Chromium-152-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)

</div>

---

## Pourquoi Eagle ?

Eagle est un navigateur basé sur Chromium (le moteur de Chrome) qui vous protège **dès l'installation**, sans extension ni réglage compliqué. Les sites s'affichent comme dans Chrome, mais les pubs, les pisteurs et les tentatives d'identification sont bloqués.

## Résultats aux tests indépendants

| Test | Résultat |
|---|---|
| **Cover Your Tracks** (EFF) | ✅ *Strong protection* · empreinte **aléatoire** (*randomized fingerprint*) |
| **AdBlock Tester** | ✅ **100 / 100** |
| **ipleak.net / dnsleaktest.com** | ✅ Aucune fuite DNS ni WebRTC |
| **SSL Labs** (client) | ✅ TLS 1.3, aucune vulnérabilité |
| **badssl.com** | ✅ Certificats invalides et chiffrements faibles bloqués |
| **Pages de test Google Safe Browsing / AMTSO** | ✅ Bloquées |
| **ECH** (defo.ie) | ✅ Nom du site chiffré |

## Fonctionnalités

### 🛡️ Eagle Shields : protection intégrée
- **Bloqueur de pubs et de pisteurs** (EasyList, EasyPrivacy, uBlock), avec masquage des emplacements publicitaires
- **Blocage des sites dangereux** : plus de 230 000 sites de malware, d'hameçonnage et d'arnaque (URLhaus, Phishing Filter, HaGeZi Threat Intelligence)
- **Téléchargements dangereux bloqués**
- **Cookies tiers bloqués**, nettoyage des liens de pistage (`utm_`, `fbclid`, `gclid`…)
- **Passage automatique en HTTPS**
- Interrupteur par site et compteur de blocages

### 🕵️ Vie privée et anonymat
- **Empreinte numérique brouillée** : canvas, WebGL et audio sont différents sur chaque site, ce qui empêche le pistage d'un site à l'autre
- **Appareil masqué** : modèle de carte graphique, barre des tâches, polices, clavier, type de connexion…
- **DNS chiffré** (Quad9, Mullvad, Cloudflare, AdGuard), sans fuite vers le DNS de l'opérateur
- **WebRTC protégé** : votre adresse IP locale n'est jamais révélée
- **Global Privacy Control** et **Do Not Track**
- API publicitaires de Chrome désactivées (Topics, FLEDGE…)
- **Fenêtre privée** et **fenêtre privée avec Tor** (`Alt+Maj+N`)
- Proxy / VPN personnalisable

### 🎵 Confort
- **Contrôle de la musique et des vidéos** pour tous les onglets (lecture/pause, piste suivante, pochette)
- **Image dans l'image** : bouton sur les vidéos, mode automatique en changeant d'onglet, raccourci `Alt+P`
- **Mise en veille des onglets inactifs** pour économiser la mémoire
- Nouvel onglet personnalisable : fonds animés, horloge, sites favoris, statistiques de protection
- Thème sombre / clair, couleurs d'accent, onglets verticaux
- Favoris, historique, téléchargements, recherche dans la page, capture d'écran

### 🔒 Sécurité et sauvegarde
- **Sauvegarde chiffrée** des réglages, favoris et connexions (AES-256), pratique avant de formater son PC
- **Mises à jour automatiques et silencieuses**, avec les onglets restaurés après chaque mise à jour
- Bac à sable sur toutes les pages, pages internes protégées contre les injections

## Installation

1. Téléchargez `Eagle-Browser-Setup-x.x.x.exe` depuis la **[dernière version](https://github.com/ApollonNeo/eagle-browser/releases/latest)**.
2. Lancez-le et suivez l'assistant.

> **Windows SmartScreen** peut afficher « Windows a protégé votre ordinateur », car l'installateur n'est pas signé numériquement. Cliquez sur **Informations complémentaires**, puis **Exécuter quand même**.

Eagle se met ensuite à jour tout seul.

## Raccourcis utiles

| Action | Raccourci |
|---|---|
| Nouvel onglet / fenêtre privée | `Ctrl+T` / `Ctrl+Maj+N` |
| Fenêtre privée avec Tor | `Alt+Maj+N` |
| Rouvrir l'onglet fermé | `Ctrl+Maj+T` |
| Image dans l'image | `Alt+P` |
| Paramètres | `Ctrl+,` |

## 🚀 Feuille de route

Eagle évolue vite. Voici ce qui arrive :

### Bientôt
- [ ] 🔑 **Gestionnaire de mots de passe chiffré** intégré, avec générateur de mots de passe solides
- [ ] 🚨 **Alerte de fuite de mot de passe** : vérification anonyme si un mot de passe a fuité (sans jamais l'envoyer en clair)
- [ ] 📑 **Groupes d'onglets** colorés et **barre latérale** (WhatsApp, Discord, notes… toujours à portée de main)
- [ ] 📖 **Mode lecture** : un article sans pub ni distraction, avec réglage de la police
- [ ] 🧅 **Tor intégré en un clic**, sans avoir besoin d'installer Tor Browser

### Plus tard
- [ ] 🔄 **Synchronisation chiffrée de bout en bout** des favoris et réglages entre plusieurs PC
- [ ] 🌍 **Traduction des pages en local**, sans envoyer le texte à un service en ligne
- [ ] 🧩 Prise en charge des **extensions du Chrome Web Store**
- [ ] 🤖 **Assistant de résumé de page** fonctionnant en local, pour préserver la vie privée
- [ ] 🎮 **Mode jeu / économie** : moins de mémoire et de processeur utilisés quand vous jouez
- [ ] ✍️ **Installateur signé numériquement** (fin de l'avertissement SmartScreen)
- [ ] 🐧 Versions **Linux** et **macOS**, puis **Android**

Une idée ? Ouvrez une [discussion ou une suggestion](https://github.com/ApollonNeo/eagle-browser/issues) !

## Configuration requise

- Windows 10 ou 11 (64 bits)
- Environ 300 Mo d'espace disque

---

<div align="center">

Fait avec ❤️ par **ApollonNeo**

</div>
