# cesibadge

**Installation de pip**
```
sudo apt-get install python-pip
```

**Installation de virtualenv pour créer un environnement de développement isolé
```
sudo pip install virtualenv
```

**Création d'un environnement de développement custom**
```
cd cesibadge
virtualenv venv
```

**Activation de l'environnement virtuel**
```
. venv/bin/activate
```

**Installation des dépendances du projet**
```
python setup.py develop
```

**Désactivation de l'environnement virtuel**
```
deactivate

```
