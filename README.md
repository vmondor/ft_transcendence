# 🕹️ ft_transcendence - Projet final du tronc commun 42

Projet de groupe réalisé avec [Malo Lefort](https://github.com/Malolfrt), [Ruddy Risselin](https://github.com/RuddyRisselin) et [Yann Mostowski](https://github.com/ymostows)

![ezgif com-video-to-gif-converter (5)](https://github.com/user-attachments/assets/74b4fcc7-74ac-4edf-acce-44be3f281b41)


## 📌 Description

**ft_transcendence** est le **projet final du tronc commun** de l'école 42. Il consiste à développer une **application web complète**, moderne, interactive et sécurisée, centrée autour d’un jeu de **Pong**, avec de nombreuses fonctionnalités sociales.  
Ce projet mêle **frontend, backend, base de données, temps réel (WebSocket)** et requiert des compétences en **authentification**, **sécurité**, et **design UI/UX**.

---

## 🧠 Objectifs pédagogiques

- Développer une **application full-stack** avec des technologies modernes
- Implémenter un **jeu interactif en temps réel** dans le navigateur
- Gérer **l’authentification (2FA)** et la sécurité web
- Concevoir une **base de données relationnelle** et ses relations
- Assurer la **modularité et la maintenabilité** du code
- Déployer une application en **conteneurs (Docker)**

---

## 🛠️ Stack technique

### 🖥️ Backend
- **Node.js**
- **Passport.js**
- **SQLlite**
- **WebSocket**

### 🌐 Frontend
- **Javascript**
- **TypeScript**
- **WebSocket API**
- **CSS / Tailwind CSS**

### ⚙️ DevOps / Sécurité
- **Docker** et **Docker Compose**
- **.env** pour les variables d’environnement
- Sécurité :
  - Limitation des requêtes
  - Protection CSRF, XSS, injection SQL
  - Authentification 2FA (TOTP)

---

## 🎮 Fonctionnalités principales

- 🔒 Authentification via double authentification (2FA)
- 👤 Système de profils (avatar, statut, niveau…)
- 🎮 Jeu Pong multijoueur (local)
- 🧑‍🤝‍🧑 Liste d’amis & gestion des invitations
- 📊 Classement et historique des parties
- 🌍 **Traduction multilingue** : site disponible en **français**, **anglais** et **espagnol**

---

## 🚀 Lancer le projet

### 1. Cloner le dépôt

```bash
git clone https://github.com/vmondor/ft_transcendence.git
cd ft_transcendence
make init
make
```

Visiter : https://localhost:4430/
