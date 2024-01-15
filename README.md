# Documentation du tuto GitHub avec Git : 
# initialisation de dépôt 
''
git init
''
# URL du Repo :
git remote add origin git@github.com:Kawtar-af/com.git_tuto.git

# création de dépôt 
## Rédiger un commit
'''
L'évolution du commit 
Description de notre commit avec des informations sur l 'évolution du projet 
'''
## Envoyer un commit sur le dépôt distant 
'''
bash 
git add.
git commit -m " un  commentaire "
git push origin master 
'''

## création d'une branche 
'''
bash 
git checkout -b NOM_BRANCH 
'''
Pour les bonnes pratique , on va intégrer la notion de revue de code . Pour cela on va créer une branche , faire des modifications , les envoyer au dépôt distant , puis créer une pull request pour demander une revue de code . 
