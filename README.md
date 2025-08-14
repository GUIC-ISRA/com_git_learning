# Documentation du tuto Github avec Git(Apprentissage)

## Initialisation du dépôt

```bash
git init
git remote add origin SSH_REPO
```

## Rédiger un commit (bonne pratique)

```
Titre du commit

Description de notre commit avec des informations  sur l'évolution du projet
```

## Envoyer un commit sur le dépôt distant

```bash
git add .
git commit -m "Un commentaire"
git push origin main
```

## Création d'une branche

```bash
git checkout -b NOM_BRANCHE
```

Pour les bonnes pratiques, on va intégrer la notion de revue de code. Pour cela, on va créer une branche, faire des modifications, les envoyer sur le dépôt distant, puis créer un pull request pour demander une revue de code.