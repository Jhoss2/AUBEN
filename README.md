# U-AUBEN Supplies Tracker

Application mobile native développée avec **React Native CLI** pour la gestion logistique de l'Université Aube Nouvelle.

## 🚀 Caractéristiques

- **Offline-First** : Utilisation de SQLite pour le stockage local intégral.
- **Gestion Logistique** : Suivi des blocs, salles et matériels.
- **Assistant IA "Aube"** : Assistant contextuel pour interroger l'inventaire.
- **Build-Ready** : Configuration optimisée pour **Codemagic**.
- **Interface Fidèle** : Respect strict du design et de l'expérience utilisateur de la version originale.

## 🛠️ Installation

1. Cloner le dépôt :
   ```bash
   git clone <repository-url>
   cd AubeSuppliesTracker
   ```

2. Installer les dépendances :
   ```bash
   pnpm install
   ```

3. Lancer l'application :
   - **Android** : `npx react-native run-android`
   - **iOS** : `cd ios && pod install && cd .. && npx react-native run-ios`

## 📦 Build avec Codemagic

Le fichier `codemagic.yaml` est inclus à la racine du projet pour automatiser les builds Android et iOS.

## 📄 Licence

Ce projet est la propriété de l'Université Aube Nouvelle.
