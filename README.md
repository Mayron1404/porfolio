# Portfolio Mayron Dyeo — Guide d'installation

## Structure des fichiers

```
portfolio/
├── index.html                  ← Page principale du portfolio
├── config/
│   └── db.php                  ← Connexion à la base de données
├── api/
│   ├── portfolio.php           ← API JSON (données du portfolio)
│   └── contact.php             ← API formulaire de contact
└── portfolio_database.sql      ← Script SQL à importer dans MySQL
```

## Installation étape par étape

### 1. Installer un serveur local
- Windows : XAMPP (https://www.apachefriends.org) ou WampServer

### 2. Importer la base de données
1. Démarre Apache + MySQL dans XAMPP
2. Ouvre phpMyAdmin → http://localhost/phpmyadmin
3. Clique sur "Importer"
4. Sélectionne portfolio_database.sql
5. Clique sur "Exécuter"

### 3. Placer les fichiers
- Copie le dossier dans : C:/xampp/htdocs/portfolio/

### 4. Ouvrir le portfolio
- Navigue vers : http://localhost/portfolio/index.html
