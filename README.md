# Tutoriel complet de Django (en cours de réalisation)
Source: [documentation de Django](https://docs.djangoproject.com/fr/5.2/)
(version stable en avril 2025: 5.2).

Ce dépôt comprend l'intégralité du tutoriel officiel, proposé en huit parties dans la documentation
de Django.

## Utilisation
Chaque étape importante est enregistrée dans une branche propre, ce qui permet de refaire 
facilement certaines étapes à partir de la bonne base de code. Les branches sont numérotées 
et nommées avec la dernière étape achevée qu'elles contiennent. Par exemple, une branche nommée 
'08_blog_creation' contiendra l'étape de création du blog. Si on veut refaire cette étape, il
faudra donc se positionner sur la branche précédente ('07_...'). La branche 'main' contient 
le tutoriel intégralement complété.

## Liens et contenu des différentes étapes du tutorial
Les liens suivants reprennent les noms des différentes branches de ce dépôt et 
renvoient vers l'étape associée du tutoriel officiel.
- [01_votre_1ere_application](https://docs.djangoproject.com/fr/5.2/intro/tutorial01/): 
création du projet, de l'application "polls" et d'une première vue.
- [02_votre_1ere_application](/https://docs.djangoproject.com/fr/5.2/intro/tutorial02/): 
configuration de la base de données, création d'un premier modèle, intro au site d'administration.
- [03_votre_1ere_application](https://docs.djangoproject.com/fr/5.2/intro/tutorial03/): 
création de vues.
- [04_votre_1ere_application](https://docs.djangoproject.com/fr/5.2/intro/tutorial04/): 
gestion de formulaires et réduction de code.

## Infos utiles
- La base de données est volontairement versionnée pour ne pas avoir à recréer les pages 
à chaque fois.
- Vous devez créer votre propre super-utilisateur pour accéder à l'administration, 
avec la commande suivante dans le terminal : `python manage.py createsuperuser`.
- Dans les chaînes de caractères dynamiques du tutorial, la partie dynamique est gérée
avec l'ancienne syntaxe %s par souci de compatibilité avec d'anciennes versions de Python
→ remplacée ici dans le code par des f-strings.
