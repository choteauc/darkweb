# Projet Git - Instructions pour les groupes

## Création du projet

Le dépôt Git a été initialisé et la branche `main` a été créée. Chaque groupe doit créer une branche dédiée à sa propre présentation avant d'ajouter des fichiers.

## Étapes pour travailler avec Git

### 1. Cloner le dépôt (si ce n'est pas encore fait)
```bash
git clone URL_DU_DEPOT
cd NOM_DU_DEPOT
```

### 2. Créer une nouvelle branche pour votre groupe
Remplacez `nom-de-la-branche` par un nom pertinent pour votre présentation.
```bash
git checkout -b nom-de-la-branche
```

### 3. Ajouter des documents à votre branche
Ajoutez les fichiers nécessaires au projet.
```bash
git add nom_du_fichier
```
Ou pour ajouter tous les fichiers modifiés :
```bash
git add .
```

### 4. Ajouter un commentaire (commit)
Ajoutez un message clair décrivant les modifications.
```bash
git commit -m "Ajout des fichiers de présentation du groupe X"
```

### 5. Envoyer les modifications sur le dépôt distant
Poussez votre branche vers le dépôt distant.
```bash
git push origin nom-de-la-branche
```

### 6. Faire une Pull Request (PR)
Rendez-vous sur GitLab/GitHub pour créer une demande de fusion (Pull Request) et demander l'intégration de votre branche dans `main`.

