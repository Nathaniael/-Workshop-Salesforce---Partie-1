# Workshop-Salesforce - Partie 1

## Inscription
Pour commencer, il vous est nécéssaire de créer un compte sur Salesforce en ce rendant sur le lien suivant, et en cliquant sur le bouton _ESSAI GRATUIT_: https://www.salesforce.com/fr/

## Définitions :
- Compte : Une entreprise
- Contact : Une personne physique qui peut être rattachée à un Compte
- Affaire : Une opportunité de vente rattachée à la fois à un Contact et à un Compte

## Exercices

1. Rajouter un champ Statut à la fois sur Compte et sur Contact qui a 2 valeurs possibles : Prospect et Client.

2. Faire en sorte que lorsqu'une Affaire est gagnée, le Client passe de Prospect à Client.
(workflow et mise à jour de champ).

3. Faire en sorte que lorsque l'on crée un Contact rattaché à un Compte, le Contact prenne le statut du Compte (Prospect ou Client).
(workflow et fonction)

4. Faire en sorte que lorsqu'un Compte passe de Prospect à Client, tous les Contacts rattachés passent également à Client.
