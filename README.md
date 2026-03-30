# 🚗 Alya RP - Système de Gestion de Concessionnaire

Site de gestion ultra-complet pour votre concessionnaire sur Alya RP.

## 🚀 Installation

```bash
npm install
npm run dev
```

## 🔐 Connexion par défaut

- **Identifiant:** `leonmorozov`
- **Mot de passe:** `rouuuben`
- **Rôle:** Patron (accès complet)

## ✨ Fonctionnalités

### 🏠 Page publique (avant connexion)
- **Formulaire de candidature** personnalisable
- Affichage des **véhicules à reprendre**
- **Vendeurs en service** en temps réel
- Informations sur le concessionnaire

### 📊 Dashboard
- Vue d'ensemble de l'activité
- Statistiques en temps réel
- Top vendeurs
- Activité récente

### ⏰ Services
- **Prise de service** en un clic
- Chronomètre en temps réel
- Vue de tous les employés en service
- Historique des sessions par jour

### 💰 Ventes & Reprises
- Formulaires séparés vente/reprise
- Modification et suppression des ventes
- **Ajustement de l'argent et des heures**
- Classement par jour
- Recherche et filtres avancés

### 👥 Employés
- Liste complète avec recherche
- Détails et statistiques par employé
- Historique des ventes
- Gestion des avertissements
- Reset heures/argent

### 🎯 Quotas
- Configuration par grade ou employé
- Objectifs: argent, ventes, heures
- Alertes automatiques

### 🏖️ Absences
- Demandes avec validation
- Statuts visuels

### 🚗 Véhicules à reprendre
- Liste publique avant connexion
- Ajout/gestion par hauts gradés
- Conversion automatique en reprise

### 🚨 Alertes
- Dashboard centralisé
- Filtres par type
- Code couleur

### 🔗 Webhooks Discord
- Configuration par événement
- Messages personnalisables

### 🛡️ Grades
- **Création de grades personnalisés**
- Configuration complète des **permissions**
- 20+ permissions disponibles

### 👤 Utilisateurs
- **Création de comptes**
- Attribution des grades
- Gestion complète

### 📋 Logs
- Historique complet
- Traçabilité

## 🎨 Design

- Gradient noir/bleu foncé
- Animations fluides
- Interface moderne et professionnelle
- Design qui donne vraiment envie

## 🔒 Permissions

Chaque grade peut avoir accès à :
- Voir le dashboard
- Prendre son service
- Gérer les ventes (créer, modifier, supprimer)
- Voir/gérer les employés
- Voir/gérer les quotas
- Voir/gérer les absences
- Voir/gérer les véhicules
- Voir les alertes
- Voir/gérer les webhooks
- Voir les logs
- Gérer les grades
- Gérer les utilisateurs
- Gérer les candidatures

## 📱 Deployment

Pour déployer sur Netlify :

1. Build le projet :
```bash
npm run build
```

2. Déployez le dossier `dist/` sur Netlify

3. Configuration Netlify :
   - Build command: `npm run build`
   - Publish directory: `dist`
   - Add redirect rule: `/*  /index.html  200`

## 💾 Stockage

Les données sont stockées en local (localStorage). Aucune donnée d'exemple/test n'est pré-remplie, tout est vide au démarrage.

## ⚡ Nouveautés

✅ Page publique avant connexion  
✅ Système de service avec chronomètre  
✅ Gestion des permissions par grade  
✅ Création d'utilisateurs  
✅ Modification des ventes  
✅ Historique classé par jour  
✅ Design ultra-moderne  
✅ Aucune donnée de test  

---

Développé pour Alya RP 🎮
