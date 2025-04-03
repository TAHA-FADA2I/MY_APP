

markdown
# ShowApp - Application de gestion de médias

Une application Flutter pour gérer vos films, séries et animés, connectée à un backend Node.js.

## Fonctionnalités

✔️ Authentification utilisateur  
✔️ Gestion CRUD des shows (films/séries/animés)  
✔️ Upload d'images  
✔️ Navigation fluide avec Drawer et Bottom Bar  
✔️ Tri par catégories  
✔️ Swipe-to-delete avec confirmation  

## Technologies

- **Frontend** : Flutter 3.x
- **Backend** : Node.js/Express
- **Base de données** : SQLite
- **Gestion d'images** : Multer

## Prérequis

- Flutter SDK 3.0+
- Node.js 16+
- npm/yarn
- Emulateur Android/iOS ou appareil physique

## Installation

### Backend

1. Cloner le dépôt :
bash
cd showapp/backend
```

2. Installer les dépendances :
```bash
npm install
```

3. Démarrer le serveur :
```bash
node server.js
```
*Le serveur tourne sur http://localhost:5000*

### Frontend

1. Se placer dans le dossier frontend :
```bash
cd ../frontend
```

2. Installer les dépendances :
```bash
flutter pub get
```

3. Lancer l'application :
```bash
flutter run
```

## Structure du projet

```
showapp/
├── backend/
│   ├── server.js         # Serveur principal
│   ├── routes/           # Routes API
│   ├── database.js       # Configuration SQLite
│   
└── frontend/
    ├── lib/
    │   ├── screens/      # Toutes les pages
    │   ├── config/       # Modèles de données
    │   └── main.dart     # Point d'entrée
    └── pubspec.yaml      # Dépendances Flutter

## Endpoints API

- POST /auth/login - Authentification
- GET /shows - Liste tous les shows
- POST /shows - Ajoute un nouveau show
- PUT /shows/:id - Met à jour un show
- DELETE /shows/:id - Supprime un show

## Licence

MIT License - voir [LICENSE](LICENSE)

---

Auteur : khalif taha  
Contact : tahakhalif4@gmail.com  
Version : 1.0.0

