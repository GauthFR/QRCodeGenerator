# Générateur de QR codes statiques

Application web locale permettant de créer des QR codes permanents pour :

- une URL ;
- un contact vCard ;
- une localisation par coordonnées ou adresse.

## Utilisation

Ouvrez simplement `index.html` dans un navigateur, choisissez un type de contenu, remplissez le formulaire puis cliquez sur **Générer**. Le QR code peut ensuite être téléchargé au format PNG.

## Fonctionnement

L’application tient dans un seul fichier HTML et fonctionne hors ligne. Elle ne nécessite ni compte, ni base de données, et aucune donnée n’est envoyée à un serveur.

Les informations sont directement encodées dans le QR code : celui-ci n’expire pas. Dans le cas d’une URL, le site ciblé doit toutefois rester accessible.
