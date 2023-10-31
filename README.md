# MERCHEX : Toutes premières expérimentations sur Django


## Description du projet

Ce site correspond à ma toute première utilisation de Django. Le projet n'est pas abouti, et m'a simplement servi d'exemple pour suivre le cours Django Débutant d'OpenClassrooms.  
Les fonctionnalités consistent en l'implémentation d'opérations CRUD (Create, Read, Update, Delete) sur un ou deux modèles. Le but était de découvrir les bases du fonctionnement de Django.  
Pour un projet plus abouti réalisé avec Django, consultez plutôt <>.  

## Mise en place et exécution en local de l'application

1. Téléchargez le projet depuis Github. Soit directement (format zip), soit en clonant le projet en utilisant la commande suivante dans Git Bash :  
```
git clone https://github.com/TheoSntt/merchex
```
2. Créez un environnement virtuel Python en exécutant la commande suivantes dans le Terminal de votre choix :
```
python -m venv env (env étant le nom de l'environnement, vous pouvez le changer)
```
Puis, toujours dans le terminal, activez votre environnement avec la commande suivante si vous êtes sous Linux :
```
source env/bin/activate
```
Ou bien celle-ci si vous êtes sous Windows
```
env/Scripts/activate.bat
```
3. Dans vorte environnement virtuel, téléchargez les packages Python nécessaires à la bonne exécution de l'application à l'aide de la commande suivante :
```
pip install -r requirements.txt
```
NB : Puisque la BDD contenant du contenu visant à démontrer la fonctionnalité de l'application est incluse dans le répo. Il n'est pas nécessaire de procéder aux migrations. Si vous souhaitez recréer la BDD de zéro, supprimer le fichier db.sqlite3 et procédez aux migrations, à l'aide de la commande suivante :
```		
python manage.py migrate
```
4. Vous pouvez maintenant exécuter l'application en local. Il vous suffit de lancer le serveur local, à l'aide de la commande suivante :
```		
python manage.py runserver
```
5. L'application est prête à être utilisée.
