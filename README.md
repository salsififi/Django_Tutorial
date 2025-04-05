# TUTO COMPLET WAGTAIL
Source : [documentation de Django](https://docs.djangoproject.com/fr/5.2/)
(version stable au 05/04/2025 : 5.2).

Ce dépôt comprend l'intégralité du tutoriel de Django, proposé en 7 parties dans la documentation
de Django.

## Utilisation
Chaque étape importante est enregistrée dans une branche propre, ce qui permet de refaire 
facilement certaines étapes à partir de la bonne base de code. Les branches sont numérotées 
et nommées avec la dernière étape achevée qu'elles contiennent. Par exemple, une branche nommée 
'08_blog_creation' contiendra l'étape de création du blog. Si on veut refaire cette étape, il
faudra donc se positionner sur la branche précédente ('07_...'). La branche 'main' contient 
le tutoriel intégralement complété.

## Liens des différentes étapes du tutorial
- [01_votre_1ere_application](https://docs.djangoproject.com/fr/5.2/intro/tutorial01/)
- [02_votre_1ere_application](https://docs.djangoproject.com/fr/5.2/intro/tutorial02/)
- 

## Infos utiles
- La base de données est volontairement versionnée pour ne pas avoir à recréer les pages 
à chaque fois.
- Vous devez créer votre propre super-utilisateur pour accéder à l'administration, 
avec la commande suivante dans le terminal : `python manage.py createsuperuser`.
