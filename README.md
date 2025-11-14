# Projet_Data_GR3

Groupe : Brendan ROBIN, Noémie PETAT, Antoine GEZE, Augustin OWCA

Todo : ajouter github et intro projet

Introduction au projet Data

Sujet : prédiction de la réussite des étudiants

# Installation en local

Cliquer sur Code puis download Zip

Extraire le dossier où vous voulez (Documents)

Ouvrir VSCode puis File -> Open Folder -> sélectrionner le dossier téléchargé

Une fois ouvert : se connecter à github sur vscode

Installez git bash

Ouvrez le terminal, puis cliquer sur le petit plus et choisir git bash, puis : 

```bash
git config --global user.email monemailgithub@gmail.com
```

```bash
git config --global user.name usernamegithub
```


# Gestion de git : partage de code

1. 
```bash
git pull https://github.com/AugustinO28/Projet_Data_GR3.git

```
2. Créer une nouvelle branche et la nommer en lien avec les changements à effectuer :
```bash
git checkout -b nom-de-la-branche
```
On voit le nom de la branche dans le terminal

3. Faire des changements, ctrl S pour sauvegarder

4. tester que le code fonctionne bien avec les changements

5. Dans Source Control (menu à gauche vscode), vous voyez les changements.

cliquez sur le petit + pour les ajouter (add), puis écrire un message de Commit (expliquer les changements), puis Commit

Enfin, Syncchanges et cela va publier les changements sur le github

6. Merge de branche : une fois le travail du changement global terminé, aller sur github pour merge la branche de l'évolution sur main.