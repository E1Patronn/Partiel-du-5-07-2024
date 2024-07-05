# Partiel-du-5-07-2024

J'ai commencé par créer une machine virtuelle avec le code terraform. La VM a été créer sur gcp. Il y a certaines parties du code terraform qui pourrait être variabilisé pour plus de visibilité dans le code.

Pour la partie ansible on peut diviser le playbook en plusieurs parties : 

- Création d'un utilisateur pour lancer l'API
- On va mettre à jour la machine 
- On va installer python et toutes les dépendances
- Cloner le repo git donner
- Créer un environnement python
- Install les dépendances python
- Lancer l'api avec Uvicorn
- Création d'un fichier pour le lancement automatique au redémarrage de la machine et l'activer
