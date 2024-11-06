# 📽️ CineSwipe

Bienvenue sur **CineSwipe** - l'application de découverte de films la plus immersive et innovante du moment ! Plongez dans un univers où chaque swipe vous rapproche du film parfait, grâce à notre interface intuitive et notre intelligence artificielle de recommandations cinématographiques.

---

## 🎬 Sommaire

- [À propos de CineSwipe](#-à-propos-de-cineswipe)
- [Fonctionnalités principales](#-fonctionnalités-principales)
- [Technologies](#-technologies)
- [Installation](#-installation)
- [Guide d'utilisation](#-guide-dutilisation)
- [Roadmap](#-roadmap)
- [Contribuer](#-contribuer)
- [Licence](#-licence)
- [Contact](#-contact)

---

## ✨ À propos de CineSwipe

**CineSwipe** n'est pas qu'une simple application de films : c'est une nouvelle manière de découvrir le cinéma ! Fini les catalogues ennuyeux et les listes interminables : avec CineSwipe, explorez des films adaptés à vos goûts en swipant, comme sur Tinder ! De plus, une intelligence artificielle puissante apprend de chaque interaction pour vous recommander des films parfaitement alignés avec vos préférences.

Notre objectif est de rendre chaque moment de visionnage unique et de faciliter la découverte de films que vous n'auriez peut-être jamais envisagés.

---

## 💡 Fonctionnalités principales

### 🎞️ **Swipe pour Découvrir**
- Naviguez dans des films via un système de swipe : glissez vers la droite pour ajouter un film à votre liste, ou vers la gauche pour passer.
- Interface inspirée des applications de rencontre pour une expérience interactive et plaisante.

### 🧠 **Recommandations personnalisées grâce à l'IA**
- **CineAI** : notre IA dédiée analyse vos préférences et les films que vous aimez ou rejetez pour vous proposer des recommandations toujours plus précises.
- Suggestions de films adaptées à l'humeur, à la période de la journée, et même à l'énergie de l'utilisateur !

### 🔥 **Sections thématiques et innovantes**
- **Films tendance**, **Collections (Harry Potter, Pirates des Caraïbes)**, et **Pour les plus jeunes**.
- Découverte par **humeur** ou **univers cinématographique** (science-fiction, fantasy, drame, etc.).

### 🌎 **Expérience interactive et immersive**
- Interface en 3D avec des effets visuels captivants pour rendre la navigation unique.
- **Mode Immersion** : une expérience de navigation en réalité virtuelle pour les utilisateurs disposant d'un casque compatible.

### 🎟️ **Défis et badges**
- Complétez des défis cinéphiles, comme "Explorer tous les classiques des années 80", pour débloquer des badges exclusifs.
- Mode "marathon" : recommandations de sagas pour les soirées prolongées.

### 🎉 **Social et partage**
- Visionnage synchronisé avec des amis, avec un chat en direct intégré.
- Listes de films partagées entre utilisateurs.

### 🎥 **Exploration par univers connecté**
- Un graph interactif vous permet de découvrir des films par connexions d’univers : les films Marvel, l’univers Star Wars, et bien plus.
- Fonction "machine à remonter le temps" pour voyager dans les années cinématographiques.

---

## 🛠️ Technologies

- **Langage** : Kotlin (Android)
- **Interface Utilisateur** : Jetpack Compose pour une expérience fluide et responsive.
- **Backend** : Firebase pour les données et l'authentification des utilisateurs.
- **API Films** : The Movie Database (TMDb) API pour les informations détaillées sur les films.
- **Intelligence Artificielle** : Modèles de Machine Learning (TensorFlow Lite) pour les recommandations personnalisées.
- **Réalité Virtuelle** : Intégration avec des bibliothèques VR Android pour le mode Immersion.

---

## 🚀 Installation

1. **Clonez le dépôt**
   ```bash
   git clone https://github.com/votre-nom/CineSwipe.git
   cd CineSwipe
   ```

2. **Configuration des clés API**
   - Inscrivez-vous sur [The Movie Database (TMDb)](https://www.themoviedb.org/) et récupérez une clé API.
   - Configurez Firebase pour l'authentification et la base de données.

3. **Ajoutez les clés dans votre projet**
   - Créez un fichier `local.properties` dans le dossier `app` et ajoutez :
     ```properties
     TMDB_API_KEY=VOTRE_CLE_TMDB
     FIREBASE_API_KEY=VOTRE_CLE_FIREBASE
     ```

4. **Lancez l'application**
   - Importez le projet dans Android Studio et lancez l'application sur un émulateur ou un appareil physique.

---

## 📖 Guide d'utilisation

### 1. **Inscription et Création du Profil**
   - À la première ouverture, l'utilisateur est invité à créer un profil et renseigner ses préférences de films.

### 2. **Découverte par Swipe**
   - Balayez vers la droite si vous aimez le film proposé, ou vers la gauche pour passer.
   - Les films que vous aimez sont automatiquement ajoutés à votre liste de visionnage.

### 3. **Explorer les Catégories et Collections**
   - Parcourez les collections thématiques ou explorez par humeur et ambiance.
   - Découvrez des films basés sur des univers connectés ou des thèmes spécifiques.

### 4. **Accès aux Recommandations IA**
   - CineAI ajuste vos recommandations au fur et à mesure de vos interactions. Plus vous swipez, plus l'IA comprend vos goûts.

### 5. **Mode Immersion**
   - Activez le mode VR pour une expérience immersive. Nécessite un casque compatible.

### 6. **Visionnage Synchro**
   - Regardez un film avec vos amis en temps réel, avec chat intégré pour partager vos réactions en direct.

---

## 🛣️ Roadmap

### Prochaines fonctionnalités
- **Mode Nocturne** pour une expérience visuelle agréable la nuit.
- **Analyses et statistiques de visionnage** pour suivre vos habitudes et découvrir vos acteurs, réalisateurs ou genres préférés.
- **Mise en place d'un système de récompenses évolué** avec des cadeaux pour les cinéphiles les plus engagés.
- **Fonction "Cinéma à l’international"** pour explorer des films de différentes cultures et en différentes langues.

### Fonctionnalités envisagées
- **Mode hors ligne** pour télécharger des listes et explorer sans connexion.
- **Extension vers iOS** pour que CineSwipe soit disponible sur toutes les plateformes.
- **Ajout d’un mode de réalité augmentée (AR)** pour découvrir des anecdotes ou infos cachées sur les affiches de films.

---

## 👥 Contribuer

Les contributions sont les bienvenues pour faire évoluer CineSwipe !

1. Forkez le projet.
2. Créez votre branche pour la fonctionnalité (`git checkout -b feature/NouvelleFonctionnalite`).
3. Faites un commit de vos modifications (`git commit -m 'Ajout d'une nouvelle fonctionnalité'`).
4. Pushez sur la branche (`git push origin feature/NouvelleFonctionnalite`).
5. Ouvrez une Pull Request.

---

## 📄 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

## 📫 Contact

Pour toute question ou suggestion, n'hésitez pas à me contacter :

- **Nom** : [Votre Nom]
- **Email** : [votre.email@example.com]
- **GitHub** : [Votre Profil GitHub](https://github.com/votre-nom)

Merci d'avoir choisi **CineSwipe** pour découvrir vos prochains coups de cœur cinématographiques !
