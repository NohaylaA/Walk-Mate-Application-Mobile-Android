# Walk Mate - Application Mobile Android

**Walk Mate** est une application mobile Android conçue pour capturer et suivre l'activité physique de l'utilisateur en temps réel.

![Capture d'écran](https://github.com/user-attachments/assets/860824c2-8cab-4bce-9961-6a350bf09b0f)

## Fonctionnalités principales

1. **Enregistrement de l'utilisateur**  
   L'application permet à un utilisateur de créer un compte en fournissant son email et mot de passe. Une fois enregistré, l'utilisateur peut se connecter à tout moment.

   ![Enregistrement](https://github.com/user-attachments/assets/d699167a-600e-4c75-b41c-39ddaaf7b72b)
   ![Enregistrement suite](https://github.com/user-attachments/assets/a9041f4d-3f55-4a64-8245-e0b7bc58fa52)
   ![Connexion](https://github.com/user-attachments/assets/19fb242b-acf5-4d6e-8efd-ebc5de5fefd0)

2. **Gestion du profil**  
   Chaque utilisateur peut compléter son profil avec des informations personnelles telles que le nom, le numéro de téléphone, le sexe, et la filière d'inscription à l'université. Le profil est modifiable via la section "paramètres" de l'application.

   ![Gestion du profil](https://github.com/user-attachments/assets/e526eefa-ff8c-412c-830b-c8be26149c86)

3. **Suivi des activités physiques**  
   Grâce à l'intégration de l'API Google Activity Recognition, l'application détecte automatiquement les activités de l'utilisateur (marcher, courir, etc.). L'activité prédominante est affichée avec un niveau de confiance allant de 0 à 100, indiquant la probabilité d'exactitude.

   ![Suivi des activités](https://github.com/user-attachments/assets/bbcf37e7-48c9-4398-b6e6-c1e1873159cb)

4. **Historique des activités**  
   L'utilisateur peut consulter l'historique de ses activités, incluant la date, l'heure de début et de fin, ainsi que le type d'activité détectée.

   ![Historique des activités](https://github.com/user-attachments/assets/07a06df2-52b1-42a9-88cc-7b7cc9a91111)

5. **Affichage sur Google Maps**  
   Les activités de l'utilisateur sont également géolocalisées et affichées sur une carte Google Maps pour une meilleure visualisation de son parcours.

   ![Google Maps](https://github.com/user-attachments/assets/23d6c538-e9f6-4d95-9769-a963a9aab5c0)

## Technologies utilisées

- **Langage** : Java
- **Framework** : Android SDK
- **API utilisée** : Google Activity Recognition API
- **Base de données** : SQLite pour la gestion des comptes et des historiques d'activités.
- **Google Maps** : Intégration pour la géolocalisation des activités.

## Dépôt

Le code source du projet est disponible dans ce [dépôt GitHub](https://github.com/NohaylaA/projet_mobile).
