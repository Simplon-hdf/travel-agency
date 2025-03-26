# Règles de Gestion (Règles Métier)

---

## 1. Utilisateurs

- **RG1** : Un utilisateur peut rechercher un vol.
- **RG2** : Un utilisateur peut filtrer les résultats de la recherche.
- **RG3** : Un utilisateur peut consulter les détails d’un vol.
- **RG4** : Un utilisateur peut sélectionner un vol à réserver.
- **RG5** : L'inscription nécessite de fournir les informations suivantes :
  - Email
  - Mot de passe
  - Numéro de téléphone
  - Genre
  - Nom
  - Prénom
  - Adresse
  - Code postal
  - Ville
  - Date de naissance
  - Nationalité
- **RG6** : Un utilisateur doit se connecter avec son email et son mot de passe.
- **RG7** : Un utilisateur peut supprimer son compte.
- **RG8** : Un utilisateur peut ajouter ou retirer un ou plusieurs passagers à une réservation.
- **RG9** : Un utilisateur peut modifier ou annuler une réservation.
- **RG10** : Un utilisateur peut indiquer un moyen de paiement préféré.
- **RG11** : Un utilisateur peut consulter l’historique de ses réservations.
- **RG12** : Un utilisateur n’est pas forcément un passager.

---

## 2. Vols

- **RG13** : Un vol appartient obligatoirement à une compagnie aérienne.
- **RG14** : Un vol possède un aéroport de départ et un aéroport d’arrivée.
- **RG15** : Un vol a une date et une heure de départ, ainsi qu’une date et une heure d’arrivée.
- **RG16** : Un vol peut comporter une ou plusieurs escales, chacune ayant une heure d’arrivée et une heure de départ.
- **RG17** : Un vol a une capacité maximale (nombre de sièges).
- **RG18** : Un vol peut être lié à plusieurs réservations.
- **RG19** : Un vol peut être mis en "ouvert" ou "fermé" à la réservation par la compagnie.
- **RG20** : Un vol peut être annulé par la compagnie.
- **RG21** : Une compagnie peut modifier les informations d’un vol (ex : horaires, statut).

---

## 3. Réservations

- **RG22** : Un utilisateur doit posséder un compte pour effectuer une réservation.
- **RG23** : Une réservation peut concerner un ou plusieurs vols.
- **RG24** : Une réservation est liée à un seul utilisateur.
- **RG25** : Une réservation possède un identifiant unique.
- **RG26** : Une réservation peut être modifiée, confirmée ou annulée.
- **RG27** : Une réservation n’est confirmée qu’après validation du paiement.
- **RG28** : Une réservation contient un ou plusieurs passagers, chacun avec un numéro de siège attribué.
- **RG29** : Une réservation ne peut être créée que si le vol est encore ouvert à la réservation.
- **RG30** : Une réservation peut expirer si le paiement n'est pas effectué dans un délai imparti (ex : 15 minutes).

---

## 4. Passagers

- **RG31** : Lors de la réservation, les informations suivantes doivent être renseignées pour chaque passager :
  - Nom & Prénom
  - Date de naissance
  - Adresse
  - Code postal
  - Ville
  - Nationalité
- **RG32** : Un passager est lié à un vol et à un numéro de siège.
- **RG33** : Un passager peut choisir un siège préféré (sous réserve de disponibilité).

---

## 5. Compagnies Aériennes

- **RG34** : Une compagnie aérienne peut :
  - Ajouter un vol
  - Modifier un vol
  - Annuler un vol
  - Ouvrir ou fermer un vol à la réservation
- **RG35** : Une compagnie est responsable des informations relatives à ses vols.
- **RG36** : Une compagnie ne peut modifier ou annuler un vol qu’avant son départ.

---

## 6. Aéroports

- **RG37** : Un aéroport doit avoir un nom unique.
- **RG38** : Un aéroport peut desservir une ou plusieurs villes.
- **RG39** : Chaque aéroport peut être défini comme aéroport de départ, d’arrivée ou d’escale.

---

## 7. Notifications

- **RG40** : Un email de confirmation est envoyé après le paiement d’une réservation.
- **RG41** : Un email est envoyé lorsqu’un vol ou une réservation est modifié(e) ou annulé(e).
- **RG42** : Un email de rappel peut être envoyé à l’utilisateur 24h avant le vol.

---

## 8. RGPD

- **RG43** : Seules les données nécessaires au bon fonctionnement de la plateforme sont collectées.
- **RG44** : L'utilisateur doit donner son consentement explicite à la collecte de ses données.
- **RG45** : Un utilisateur peut demander la suppression de ses données à tout moment.

---

## 9. Ergonomie & Accessibilité

- **RG46** : L'application doit respecter les normes WCAG :
  - Le contenu doit être perceptible
  - Le contenu doit être utilisable
  - Le contenu doit être compréhensible
  - L’interface doit être compatible avec différents outils (navigateurs, lecteurs d’écran, etc.)

---

## 10. Sécurité

- **RG47** : Toutes les informations sensibles doivent être chiffrées.
- **RG48** : Toutes les transactions doivent être cryptées.
- **RG49** : Le mot de passe utilisateur doit respecter une politique de sécurité (ex : longueur minimale, majuscule, chiffre, symbole).
- **RG50** : Un utilisateur est automatiquement déconnecté après X minutes d’inactivité.

---

## 11. Gestion des erreurs

- **RG51** : Si le mot de passe est incorrect, un message d’erreur clair doit être affiché.
- **RG52** : Si une réservation échoue (vol complet, vol fermé, etc.), un message explicite doit informer l'utilisateur.