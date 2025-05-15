# CertifSure - Application React-Laravel

## Description
CertifSure est une application web moderne qui combine React pour le front-end et Laravel pour le back-end. L'application est structurée avec trois interfaces distinctes :
- Front-end utilisateur (front_user)
- Front-end administrateur (front_admin)
- Back-end Laravel (back_end)

## Structure du Projet
```
CertifSure/
├── back_end/        # Application Laravel
├── front_admin/     # Interface d'administration React
└── front_user/     # Interface utilisateur React
```

## Prérequis
- Node.js (pour le front-end)
- PHP 8.1+ (pour Laravel)
- Composer (pour les dépendances PHP)
- MySQL/MariaDB (base de données)

## Installation

### 1. Configuration du Back-end
```bash
cd back_end
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
```

### 2. Configuration du Front-end Utilisateur
```bash
cd front_user
npm install
npm run dev
```

### 3. Configuration du Front-end Admin
```bash
cd front_admin
npm install
npm run dev
```

## Technologies Utilisées

### Front-end
- React.js
- React Router
- Axios
- TailWindCSS
- ChartJs

### Back-end
- Laravel
- MySQL
- Endroid

## Fonctionnalités
- Interface utilisateur moderne et réactive
- Interface d'administration sécurisée
- Authentification et autorisation
- Gestion des utilisateurs
- API RESTful

## Contribution
Pour contribuer au projet :
1. Fork le projet
2. Créez votre branche de fonctionnalité (`git checkout -b feature/amazing-feature`)
3. Commit vos changements (`git commit -m 'Ajout d'une fonctionnalité incroyable'`)
4. Push vers la branche (`git push origin feature/amazing-feature`)
5. Ouvrez une Pull Request

## Licence
Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

## Contact
Pour toute question, contactez-nous à [mbonguefeukou@gmail.com](mailto:mbonguefeukou@gmail.com)

---
Dernière mise à jour : 15 mai 2025
