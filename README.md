# Demo d'un projet git

## Présentation :
Ce projet est géré par git.

## Commande git
* Pour intialiser git dans un dossier :
```
git init
```

* Si c'est votre premier git sur ce pc :
```
git config --global user.name "<nom et premon>"
```
```
git config --global user.email "<email>"
```

* Voir les changements depuis la dernière sauvegarde :
```
git status
```

* Ajouter les dernières modifications du fichier `README.md`
```
git add README.md
```

* Sauvegarder un commit :
```
git commit -m "<message du commit>"
```

* Ouvrir l'utilitaire `gitk`
```
gitk
```