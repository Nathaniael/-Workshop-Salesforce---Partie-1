# Workshop Salesforce - Partie 1

## Inscription
Pour commencer, il vous est nécéssaire de créer un compte sur Trailhead en ce rendant sur le lien suivant : https://trailhead.salesforce.com/fr/home

Trailhead est un outil gratuit permettant de s'exercer sur Salesforce, grâce à un playground (air de jeu).

Pour commencer l'expérience, vous devez vous rendre sur l'icône de votre profil, en haut à droite de la page -> organisation d'exercice -> Créer un Trailhead Playground. Vous pouvez donner un nom à votre Playground, celui-ci n'aura aucun impact pour la suite.

Après quelques secondes d'attente, vous aurez un nouveau Playground: cliquez sur Lancer pour y accéder. Vous pourrez désormais commencer les exercices.

Rendez-vous dans l'espace Marketing, dans le menu des applications, en haut à gauche de votre écran.

## Mise en situation
Dans ce workshop, vous serez l'admin Salesforce d'une entreprise, qui souhaite se digitaliser.
Vous devrez suivre une suite d'instruction, que vous accomplirez grâce à vos recherches. Pensez à utiliser le vocabulaire donnez, cela permettra de trouver
des réponses plus facilement ;)

## Quelques définitions
Voici quelques définitions qui vous permettront de mieux appréhender les instructions:
Définitions :
- Compte : Une entreprise
- Contact : Une personne physique qui peut être rattachée à un Compte
- Opportunité : Potentielle vente rattachée à la fois à un Contact et à un Compte

PS: après chaque instruction, vous pourrez retrouver une capture d'écran, ainsi qu'une petite description du résultat attendu :)

## Instructions
1. Rajouter l'onglet Comptes dans l'application Marketing, pour se faire suivez le chemin suivant: 
Engrenage en haut à droite de votre écran -> Configuration -> Applications -> Gestionnaire des applications -> dans la liste trouvez Marketing,
puis cliquez sur modifier. Vous pourrez désormais ajouter les Comptes. Vous devriez normalement voir apparaitre la catégorie "Comptes" dans l'application marketing (voir: ![exo1](https://github.com/Nathaniael/salesforcep1/blob/main/exo1.png)

1. Rajouter deux champs _Relation de recherche_ Contact et Compte dans l'objet Opportunité. Cela permet de lié une Opportunité à un Contact, ainsi qu'un compte.

2. Rajouter un champ Statut à la fois sur Compte et sur Contact qui a 2 valeurs possibles : Prospect et Client. Prospect doit être la valeur par défaut.

3. Faire en sorte que lorsqu'une Opportunité est gagnée ("Closed Won"), le Compte et le Contact passe de Prospect à Client.
(workflow et mise à jour de champ).

4. Faire en sorte que lorsque l'on crée un Contact rattaché à un Compte, le Contact prenne le statut du Compte (Prospect ou Client).
(workflow et fonction)

5. Faire en sorte que lorsqu'un Compte passe de Prospect à Client, tous les Contacts rattachés passent également à Client.
