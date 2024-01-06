# whisper_test

## Github

Pour chaque nouveau projet créer un répertoire directement depuis le GitHub

### Les commandes à connaitre

Pour cloner un répertoire existant depuis github :

```
git clone <url>
```

Pour afficher la liste des fichiers/dossiers modifiés :

```
git status
 ```

Pour ajouter des fichiers/dossiers non inclus :

```
git add <fichier/dossier>
git add .
```

Pour créer un commit :

```
git commit -m “description du commit”
```

Pour uploader les modifications sur github (sur la branche master) :

```
git push origin master
```

Pour extraire mettre à jour le dossier depuis githup :

```
git fetch origin
```

Pour fusionner depuis github :

```
git pull
```

Pour lister les commits (taper q pour quitter) :

```
git log
```

## Environnement virtuel

Installer le package d’environnement virtuel :

```pip3 install virtualenv```

Creer l’environnement virtuel :

```python -m venv <virtual-environnement-name>```

Activer l’environnement virtuel :
Linux/Mac :

```source <virtual-environnement-name>/bin/activate```


## Transformers
```
pip3 install --upgrade git+https://github.com/huggingface/transformers.git

pip3 install transformers datasets

pip3 install torch

```

Documentation : 
https://huggingface.co/docs/transformers/index

