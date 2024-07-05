# Partiel-du-5-07-2024

J'ai commencé par créer une machine virtuelle avec le code terraform. La VM a été créer sur gcp. Il y a certaines parties du code terraform qui pourrait être variabilisé pour plus de visibilité dans le code.

Pour la partie ansible on peut diviser le playbook en plusieurs parties : 

- on va mettre à jour la machine 
- on va installer python et toutes les dépendances
- cloner le repo git donner
- créer un environnement python
- install les dépendances python
- lancer l'api avec Uvicorn
- création d'un fichier pour le lancement automatique au redémarrage de la machine 
