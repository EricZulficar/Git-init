# Travailler avec Git
```bash 
# Initialiser un dépôt Git
git init

# Vérifier l'état du dépôt
git status

# Ajouter un fichier aux suivis
git add fichier.txt

# Enregistrer un commit
git commit -m "Ajout du fichier texte"

# Créer une nouvelle branche
git branch nouvelle-branche
#ou
git checkout -b nouvelle-branche

# Créer une nouvelle branche à partir d'une autre
git checkout -b nouvelle-branche branche-racine

# Basculer vers une branche
git checkout nouvelle-branche

# Fusionner une branche dans la branche principale
git merge nouvelle-branche

```

# Travailler avec github

### Création de son PAT (personnal access token) : 

Dans les paramètres de compte, allez dans "Developer settings" :
![img](/Pasted%20image%2020250129171719.png)


```bash

#Cloner un repo github public 
git clone https://github.com/{profile_ou_org}/{nom_du_projet}.git

#Cloner un repo github privé
git clone https//{PAT}@github.com/{profile_ou_org}/{nom_du_projet}.git

# Envoyer les changements vers un dépôt distant
git push origin "nom-de-la-branche"

# Récupérer les changements du dépôt distant
git pull origin

# Récupérer les changements du dépôt distant (branche uniquement)
git pull origin "nom-de-la-branche"

```
