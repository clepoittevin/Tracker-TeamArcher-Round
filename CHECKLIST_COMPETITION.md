# Checklist compétition

À faire avant une rencontre officielle.

## Sécurité

- Vérifier que les règles Firestore publiées limitent l'écriture aux emails coach autorisés.
- Vérifier que chaque coach peut se connecter depuis l'application.
- Supprimer ou désactiver les comptes coach inutilisés dans Firebase Authentication.

## Équipes

- Ouvrir le site sans paramètre et vérifier que le sélecteur affiche toutes les équipes attendues.
- Pour chaque équipe, ouvrir la feuille une première fois avec un compte coach afin de créer le document Firebase si besoin.
- Utiliser **Copier le lien** dans le sélecteur pour préparer les liens ou QR codes à partager.

## Test terrain

- Tester une saisie depuis un téléphone coach.
- Vérifier sur un second appareil spectateur que la mise à jour arrive en temps réel.
- Tester le passage hors réseau puis le retour réseau si la salle ou le terrain capte mal.
- Vérifier que le bouton **Changer d'équipe** renvoie bien au sélecteur.

## Sauvegarde

- Exporter le JSON de chaque équipe avant le début de la rencontre.
- Exporter de nouveau après la rencontre pour archivage.
- Garder une copie des liens d'équipe dans un endroit accessible hors ligne.
