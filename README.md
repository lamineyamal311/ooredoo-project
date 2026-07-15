<img width="1917" height="872" alt="image" src="https://github.com/user-attachments/assets/0f6696af-0dad-420f-a3e5-b9faf85e5408" /><img width="1900" height="867" alt="image" src="https://github.com/user-attachments/assets/365c2f00-9ae8-48a1-bfc3-b55adc7fafdb" /># ooredoo-project
Site de Gestion de Stock pour le Magasin des Spares du Datacenter Ouest de la Société OOREDOO Algerie.


# 📦 Ooredoo Spare Parts Inventory System

## À propos
Système de gestion de stock centralisé pour les pièces de rechange (spares) du **DataCenter Ooredoo Algérie Ouest**.

La plateforme permet un suivi en temps réel des pièces disponibles, des commandes, et optimise la gestion des ressources du datacenter.

---

## ✨ Features

- 📊 **Dashboard centralisé** — Vue d'ensemble du stock en temps réel
- 🔍 **Recherche avancée** — Filtrage par catégorie, référence, disponibilité
- 📋 **Gestion des commandes** — Création, suivi et clôture de commandes
- 📈 **Rapports & Analytics** — Historique des sorties, alertes de stock faible
- 👥 **Gestion des utilisateurs** — Rôles et permissions (Admin, Technicien, Manager)
- 🔐 **Authentification sécurisée** — Accès restreint par profil
- 📤 **Export de données** — Export CSV/Excel pour les rapports

---

## 🛠️ Stack Technique

- **Backend** — C# / ASP.NET Core
- **Frontend** — JavaScript / HTML / CSS
- **Base de données** — SQL Server / MySQL
- **Architecture** — Client-Serveur

---

## 🚀 Installation & Configuration

### Prérequis
- .NET Framework ou .NET Core (version X.X+)
- SQL Server 2019+ ou MySQL 8.0+
- Node.js (si frontend séparé)

### Étapes

1. **Cloner le repo**
```bash
   git clone https://github.com/nsb/ooredoo-project.git
   cd ooredoo-project
```

2. **Configuration de la base de données**
   - Importe le script SQL : `database/setup.sql`
   - Configure la chaîne de connexion dans `appsettings.json`

3. **Lancer le backend**
```bash
   cd Backend
   dotnet restore
   dotnet run
```

4. **Lancer le frontend** (si applicable)
```bash
   cd Frontend
   npm install
   npm start
```

5. **Accéder à l'application**
   - URL : `http://localhost:3000` (ou selon config)
   - Identifiants par défaut : `admin / password123` (à changer en production)

---

## 📸 Screenshots
![Uploading Capture d'écran 2026-07-15 151440.png…]()

<img width="1918" height="875" alt="Capture d&#39;écran 2026-07-15 151818" src="https://github.com/user-attachments/assets/5174665f-e97f-4841-8f8f-41385ea1c18c" />

<img width="1917" height="866" alt="image" src="https://github.com/user-attachments/assets/d978346f-446f-431d-95ea-e55b8983940f" />

<img width="1917" height="866" alt="image" src="https://github.com/user-attachments/assets/1de7a183-0264-4d84-9815-9e8ed7c3d950" />

<img width="1900" height="875" alt="image" src="https://github.com/user-attachments/assets/14f59ce9-4e02-4546-bffc-e503da0639dd" />

<img width="1900" height="871" alt="image" src="https://github.com/user-attachments/assets/7aee99fa-f5de-47eb-a080-40baa98a9a34" />

<img width="1917" height="872" alt="image" src="https://github.com/user-attachments/assets/aed94e4a-6cb1-4d2a-a256-457c97ac02aa" />

## 📊 Utilisation

### Roles utilisateurs
- **Admin** — Gestion complète (utilisateurs, configuration, rapports)
- **Manager** — Suivi des stocks et commandes ( Entré / Sortie )
- **Technicien** — Consultation et demandes de pièces

### Workflow principal
1. Vérifier le stock disponible
2. Créer une commande si besoin
3. Valider la sortie de stock
4. Générer les rapports pour la direction

---

## 🔧 Configuration avancée

### Variables d'environnement
Crée un fichier `.env` :
