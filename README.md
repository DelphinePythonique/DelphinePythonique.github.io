# Source du portfolio de Delphine Lemire

[Auteur: Delphine Lemire](https://www.linkedin.com/in/delphine-lemire/)

## Objet de ce dépôt

Héberger les sources de mon portefolio accessible via [les pages github](https://delphinepythonique.github.io/)

## Contenu du portfolio

Ce portefolio reprend les différents projets sur lesquels je suis intervenu en tant que concepteur/développeur et/ou animatrice. 

### Menu gauche

- 1 curriculum vitae détaillé
- 1 curriculum vitae sous forme d'un tableau croisé reprenant mes expériences (langage, moteur de base de données, framework...) en fonction des entreprises dans lesquelles, je les ai pratiquées.
- un accès à mes différents projets par catégorie ( formation , expérience )

### Zone centrale

#### Liste de mes projets
Un clic sur un titre de projet, affiche la fiche de ce projet

#### fiche projet
Une fiche projet se compose de différentes paragraphes en fonction du projet: 
- Présentation du projet
- Liste des fonctionnalités du projet
- Compétences évaluées si projet d'une formation
- url des sources du projets

## Outil utilisé

Ces sources utilisent l'outil de création de site statique [Pelican](https://docs.getpelican.com/en/latest/).

## Utilisation

### Actualiser les curriculum vitae

Dans le répertoire **content/images**, envoyer les curriculum vitae en respectant **CV.pdf** pour le curriculum vitae sous forme de tableau et **CV_DETAIL.pdf** pour le curriculum vitae détaillé

### Ajouter un projet

#### Création du fichier

- créer un nouveau fichier avec l'extension **md** dans le répertoire **content**, en s'aidant des autres fichiers contenus dans ce répertoire.
- Le fichier doit contenir au minimum les éléments suivants: 
    - Title: titre du projet
    - Date: date au format : 2022-11-05 17:21 
    - Category: catégorie du projet dans la liste:
      - **Animation**: projet pour lequel mon rôle principal a été son animation.
      - **Experience professionnelle**: projet en lien avec une expérience professionnelle
      - **Certification Développeur Python**: projet réalisé durant ma formation [**Développeur d'application python**](https://openclassrooms.com/fr/paths/518-developpeur-dapplication-python) chez Openclassrooms. 
    - tags: mots clés qualifiants le projet
    - summary: résumé du projet
 
