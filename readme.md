# Git Jafewoul 🚀

Une collection de commande Git très utile, pas souvent connus.

[![Made-In-Senegal](https://github.com/GalsenDev221/made.in.senegal/blob/master/assets/badge.svg)](https://github.com/GalsenDev221/made.in.senegal)

## Contribuer ?

Vous voulez aussi ajouter une commande que tu trouve utile ?  
N'hésite pas à **[fork](https://github.com/daoodaba975/git.jafewoul/fork)** le projet pour ajouter ta contribution et faire un PR.

## Créer et basculer une branch (une seule ligne)

```properties
git checkout -b nom_de_ma_branch_nouvelle
```

## Supprimer une branch présente sur le repo distant

```properties
git push origin --delete
# ensuite
nom_de_ma_branch_distante
```

## Mettre à jour le dépôt local d'une branch spécifique

```properties
git pull origin ma_branch
```

## Cloner une branch spécifique

```properties
git clone -b nom_de_ma_branch_distante  url_projet_git
```

## Modifier le message du dernier commit

```properties
git commit --amend
```

## Ajouter des fichiers (oubliés) au dernier commit

```properties
git add mon_fichier
# ensuite
git commit --amend
```

## Afficher tous les informations sur les commits (hash, messages, dates, auteur)

```properties
git log
```

## Afficher les informations sur un nombre de commit spécifique

```properties
# remplacez N par le nombre de commit que vous voulez afficher
git log -N
```

## Affiche un ensemble de commits selon une tranche de date

```properties
# date au format JJ/MM/AAAA
git log --since=date --until=date
```

## Affiche chaque commit par auteur (utile sur les projets à plusieurs)

```properties
git shortlog
```

## Annuler le dernier commit

```properties
# Seul le commit est retiré de Git, vos fichiers restent modifiés.
git reset HEAD^
```

## Annuler avant dernier commit

```properties
# Seul le commit est retiré de Git, vos fichiers restent modifiés.
git reset HEAD^^
```

## Annuler les commits et perdre tous les changements

```properties
# Cela annulera sans confirmation tout votre travail
git reset --hard HEAD^
```
