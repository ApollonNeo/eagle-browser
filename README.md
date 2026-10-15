<div align="center">

<img src="https://github.com/user-attachments/assets/1325adff-1a3f-431c-b9ed-7d1dd202babd" alt="Eagle Browser" width="120">

# Eagle Browser

**Un navigateur rapide, moderne et respectueux de votre vie privée.**

Bloqueur de pubs intégré · Empreinte brouillée · DNS chiffré · Tor en un clic · Mots de passe chiffrés · Pensé pour les joueurs · 100 % en français

[![Télécharger](https://img.shields.io/github/v/release/ApollonNeo/eagle-browser?label=T%C3%A9l%C3%A9charger&style=for-the-badge&color=2f80ff)](https://github.com/ApollonNeo/eagle-browser/releases/latest)
![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-0078D6?style=for-the-badge&logo=windows)
![Chromium](https://img.shields.io/badge/Chromium-152-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)

</div>

---

## Pourquoi Eagle ?

Eagle est un navigateur basé sur Chromium (le moteur de Chrome) qui vous protège **dès l'installation**, sans extension ni réglage compliqué. Les sites s'affichent comme dans Chrome, mais les pubs, les pisteurs et les tentatives d'identification sont bloqués.

Il intègre en plus ce qu'on va d'habitude chercher dans des extensions : téléchargeur de vidéos, traduction, gestionnaire de mots de passe, blocage des sponsors YouTube, mode lecture… et des outils pour les joueurs et les streamers.

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
- Cookies tiers bloqués, **nettoyage des liens** de pistage (utm_, fbclid, gclid…)
- Passage automatique en **HTTPS**
- Interrupteur par site et compteur de blocages
- **Rapport de confidentialité** : pubs et pisteurs bloqués jour par jour, sites qui vous pistent le plus, entreprises derrière (Google, Meta, Criteo…), données et temps économisés. Tout reste sur votre ordinateur

### 🕵️ Vie privée et anonymat
- **Empreinte numérique brouillée** : canvas, WebGL et audio sont différents sur chaque site, ce qui empêche le pistage d'un site à l'autre
- **Appareil masqué** : modèle de carte graphique, barre des tâches, polices, clavier, type de connexion…
- **DNS chiffré** (Quad9, Mullvad, Cloudflare, AdGuard), sans fuite vers le DNS de l'opérateur
- **WebRTC protégé** : votre adresse IP locale n'est jamais révélée
- Global Privacy Control et Do Not Track
- API publicitaires de Chrome désactivées (Topics, FLEDGE…)
- **Effacement automatique des cookies** : ceux d'un site sont effacés quand vous fermez son dernier onglet, sauf pour les sites que vous gardez
- Fenêtre privée, proxy / VPN personnalisable

### 🧅 Tor intégré en un clic
- Fenêtre privée avec Tor (Alt+Maj+N), **sans installer Tor Browser** : Eagle télécharge le Tor officiel, vérifie sa signature numérique et l'installe une seule fois

### 🔑 Gestionnaire de mots de passe
- Enregistrement proposé après chaque connexion, **chiffré avec votre session Windows** (illisible sur un autre PC ou un autre compte)
- Vos comptes proposés dans les formulaires : rien n'est rempli sans votre clic, et seulement sur le bon site
- Générateur de **mots de passe forts** à l'inscription
- **Alerte de fuite** : vérification anonyme avec Have I Been Pwned (le mot de passe n'est jamais envoyé), repérage des mots de passe faibles ou réutilisés
- Import depuis Chrome, Edge, Brave ou Firefox (fichier CSV)

### 🧩 Extensions intégrées
Toutes s'activent ou se désactivent dans **Paramètres › Extensions**.
- 🎬 **Téléchargeur de vidéos** : YouTube, TikTok, Instagram, X, Facebook, Vimeo, Twitch et plus de 1 000 sites, en **MP4 jusqu'à la 4K** ou en **MP3** / M4A, avec la progression en pourcentage
- ⏭️ **Sponsors YouTube** : les passages sponsorisés sont sautés automatiquement (SponsorBlock), avec un bouton « Annuler ». Le serveur ne sait pas quelle vidéo vous regardez
- 🌍 **Traduction de pages** en un clic (Google Traduction), en gardant les liens et les boutons de la page. « Toujours traduire » une langue, au choix
- 📖 **Mode lecture** (F9) : un article sans pub ni distraction, avec police, taille, largeur et thème au choix (clair, sépia, sombre)
- 🎵 **Contrôle de la musique et des vidéos** pour tous les onglets (lecture/pause, piste suivante, pochette)
- 🖼️ **Image dans l'image** : bouton sur les vidéos, mode automatique en changeant d'onglet, raccourci Alt+P

### 🎮 Pour les joueurs et les streamers
- **Mode jeu / économie** : dès qu'un jeu est lancé (League of Legends, VALORANT, Fortnite, CS2, Minecraft, GTA V… et les jeux Unreal Engine) ou sur batterie, Eagle met ses onglets en veille, baisse sa priorité et suspend ses tâches de fond. La musique continue
- **Superposition en jeu** (Alt+Maj+E) : une petite fenêtre Eagle par-dessus votre jeu pour un guide, une vidéo, un stream ou Discord. Transparence réglable et raccourcis personnalisables
- **Mode stream** : quand OBS ou Streamlabs est lancé, Eagle masque les adresses complètes, l'historique, les favoris, vos e-mails et identifiants, et bloque les notifications des sites. Un badge **LIVE** l'indique

### ✨ Confort
- Mise en veille des onglets inactifs pour économiser la mémoire
- Nouvel onglet personnalisable : fonds animés, horloge, sites favoris, statistiques de protection
- Thème sombre / clair, couleurs d'accent, onglets verticaux
- Clic droit dans la barre d'adresse : couper, copier, coller, « Coller l'URL et y accéder »
- Favoris, historique, téléchargements, recherche dans la page, capture d'écran
- Paramètres clairs : une page par rubrique

### 🔒 Sécurité et sauvegarde
- **Sauvegarde chiffrée** des réglages, favoris et connexions (AES-256), pratique avant de formater son PC
- **Mises à jour automatiques** et silencieuses, avec les onglets restaurés après chaque mise à jour
- Bac à sable sur toutes les pages, pages internes protégées contre les injections

## Installation

1. Téléchargez **`Eagle-Browser-Setup-x.x.x.exe`** depuis la [dernière version](https://github.com/ApollonNeo/eagle-browser/releases/latest).
2. Lancez-le et suivez l'assistant.

> **Windows SmartScreen** peut afficher « Windows a protégé votre ordinateur », car l'installateur n'est pas signé numériquement. Cliquez sur **Informations complémentaires**, puis **Exécuter quand même**.

Eagle se met ensuite à jour tout seul.

## Raccourcis utiles

| Action | Raccourci |
|---|---|
| Nouvel onglet / fenêtre privée | `Ctrl+T` / `Ctrl+Maj+N` |
| Fenêtre privée avec Tor | `Alt+Maj+N` |
| Rouvrir l'onglet fermé | `Ctrl+Maj+T` |
| Mode lecture | `F9` |
| Image dans l'image | `Alt+P` |
| Superposition en jeu (partout dans Windows) | `Alt+Maj+E` |
| Paramètres | `Ctrl+,` |

## 🚀 Feuille de route

Eagle évolue vite. Voici ce qui arrive :

**Bientôt**
- 📑 Groupes d'onglets colorés et barre latérale (WhatsApp, Discord, notes… toujours à portée de main)
- 📸 Capture d'écran de page entière, avec surlignage et floutage avant d'enregistrer
- 🎧 Téléchargement d'une playlist YouTube entière en MP3
- 🔎 Recherche dans les onglets ouverts et l'historique depuis la barre d'adresse

**Plus tard**
- 🔄 Synchronisation chiffrée de bout en bout des favoris, réglages et mots de passe entre plusieurs PC
- 🌍 Traduction des pages en local, sans envoyer le texte à un service en ligne
- 🧩 Prise en charge des extensions du Chrome Web Store
- 🤖 Assistant de résumé de page fonctionnant en local, pour préserver la vie privée
- ✍️ Installateur signé numériquement (fin de l'avertissement SmartScreen)
- 🐧 Versions Linux et macOS, puis Android

Une idée ? Ouvrez une [discussion ou une suggestion](https://github.com/ApollonNeo/eagle-browser/issues) !

## Configuration requise

- Windows 10 ou 11 (64 bits)
- Environ 300 Mo d'espace disque

---

<div align="center">

Fait avec ❤️ par **ApollonNeo**

</div>
