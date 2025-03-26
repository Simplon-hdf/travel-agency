#  Règles de Gestion (Règles Métier)

---

## 1. Utilisateurs

- **RG1** : Un utilisateur peut rechercher un vol.  
- **RG2** : Un utilisateur peut filtrer les résultats de la recherche.  
- **RG3** : Un utilisateur peut sélectionner un vol.  
- **RG4** : Un utilisateur peut consulter les détails d’un vol.  
- **RG5** : Un utilisateur doit renseigner les informations obligatoires à l’inscription :
  - Email  
  - Mot de passe  
  - Téléphone  
  - Nom & Prénom  
  - Adresse  
  - Date de naissance  
  - Nationalité  
  - Genre  
- **RG6** : Un utilisateur doit se connecter avec son email et mot de passe.  
- **RG7** : Un utilisateur peut changer l’état ou les informations de sa réservation.  
- **RG8** : Un utilisateur peut préciser son moyen de paiement préféré.  
- **RG9** : Un utilisateur n’est pas forcément un passager.

---

## 2. Vol

- **RG10** : Un vol appartient forcément à une compagnie aérienne.  
- **RG11** : Un vol doit avoir une date et une heure de départ/arrivée, un aéroport de départ et un aéroport d’arrivée.  
- **RG12** : Une compagnie peut mettre à jour les informations d’un vol (ex : état/status).  
- **RG13** : Un vol a un nombre maximal de places.  
- **RG14** : Un vol peut être lié à plusieurs réservations.  
- **RG15** : Un vol peut comporter plusieurs passagers.

---

## 3. Réservation

- **RG16** : Il faut obligatoirement avoir un compte utilisateur pour réserver un vol.  
- **RG17** : Une réservation peut contenir un ou plusieurs vols.  
- **RG18** : Une réservation appartient forcément à un seul utilisateur.  
- **RG19** : Une réservation possède un identifiant unique.  
- **RG20** : Une réservation peut changer d’état (ex : en attente, confirmée, annulée…).  
- **RG21** : Tant que le paiement n’est pas effectué, la réservation n’est pas confirmée.  
- **RG22** : Une réservation contient un ou plusieurs numéros de siège.

---

## 4. Compagnie Aérienne

- **RG23** : Une compagnie aérienne fournit à l’agence toutes les informations liées à ses vols :
  - Ajouter un vol  
  - Modifier un vol  
  - Annuler un vol  
- **RG24** : Une compagnie est responsable de l’état de ses propres vols.

---

## 5. Passagers

- **RG25** : Un passager doit renseigner ses informations lors de la réservation :
  - Nom & Prénom  
  - Nationalité  
  - Date de naissance  
  - Adresse  
- **RG26** : Un passager est toujours lié à un vol.  
- **RG27** : Chaque passager a un numéro de siège et est lié à un numéro de vol.

---

## 6. Aéroport

- **RG28** : Un aéroport doit posséder un nom.  
- **RG29** : Un aéroport a un statut particulier lors de la réservation (ex : actif, indisponible…).

---

## 7. Notifications

- **RG30** : Après le paiement d'une réservation, un email de confirmation est envoyé.  
- **RG31** : Lorsqu’un vol ou une réservation est modifié(e), un email est envoyé.

---

## 8. RGPD

- **RG32** : Seules les données nécessaires au bon fonctionnement de l’application sont collectées.  
- **RG33** : L’utilisateur doit donner son consentement à la collecte de ses données.

---

## 9. Ergonomie & Accessibilité

- **RG34** : L'application doit respecter les normes **WCAG** :
  - Le contenu doit être **perceptible**.  
  - Le contenu doit être **utilisable**.  
  - Le contenu doit être **compréhensible**.  
  - Le site doit fonctionner avec plusieurs outils (**navigateurs, lecteurs d’écran**, etc.).