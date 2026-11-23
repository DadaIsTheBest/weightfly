# Weight Fly ✈️☁️

> Partagez vos kilos de bagage en avion.

Weight Fly est une application mobile (iOS et Android) qui met en relation deux types de personnes :

- un **voyageur** qui a de la place et des kilos libres dans sa valise ;
- une personne qui veut **envoyer un colis** vers la destination du voyageur.

Le voyageur transporte des colis pour d'autres selon le **poids** et la **place** disponibles.

---

## Structure du dépôt

```
weight-fly/
├── backend/    # API : comptes, voyages, demandes de colis, messagerie, avis, signalements
├── frontend/   # Application mobile iOS / Android
└── README.md
```

---

## Fonctionnalités

### Deux modes dans la même application

L'utilisateur peut **basculer** entre les deux modes.

| Mode passager (voyageur) | Mode demandeur (envoi de colis) |
|---|---|
| Indique son vol, sa date et ses kilos libres | Cherche un voyageur selon la destination et la date |
| Reçoit les demandes de colis | Décrit son colis (poids, taille, contenu) |
| **Accepte ou refuse** chaque demande | Envoie sa demande et attend la réponse |

### Communication entre utilisateurs

Une fois le colis accepté :

- **messagerie intégrée** ;
- **appel** de la personne qui a accepté le colis ;
- **notifications** à chaque nouvelle demande ou nouveau message.

### Sécurité et prévention

- **Avertissement de risques** (contrebande, objets interdits) pour les deux parties.
- **Signalement** d'un utilisateur suspect depuis l'application.
- **Avis et profils vérifiés** : note, nombre d'avis, identité vérifiée.
- **Message de prévention automatique** envoyé dès qu'une demande est acceptée : tout objet dangereux ou interdit engage la responsabilité du voyageur et du client.
- Case **« Contenu vérifié ensemble »** à cocher avant la remise du colis.

> ⚠️ Le transport de colis pour des tiers est encadré par les règles des compagnies aériennes et des douanes. Les conditions d'utilisation doivent être relues par un juriste avant le lancement.

---

## Identité visuelle

- **Couleurs** : bleu clair et blanc
- **Logo** : un avion dans les nuages, avec le nom Weight Fly
- **Style** : simple, rassurant, lisible

---

## Écrans de la première version (MVP)

| N° | Écran | Rôle |
|---|---|---|
| 1 | Démarrage (splash) | Logo sur fond bleu clair |
| 3 | Inscription / connexion | Création du compte (e-mail ou téléphone) |
| 4 | Vérification d'identité | Pièce d'identité, profil vérifié |
| 5 | Choix du mode | Basculer passager / demandeur |
| 6 | Accueil passager | Mes vols, mes demandes reçues |
| 7 | Ajouter un voyage | Destination, date, kilos libres |
| 8 | Demandes de colis | Liste ; boutons Accepter / Refuser |
| 9 | Accueil demandeur | Recherche d'un voyageur (destination, date) |
| 10 | Résultats de recherche | Voyageurs disponibles, note, avis |
| 11 | Profil d'un voyageur | Note, nombre d'avis, identité vérifiée |
| 12 | Créer une demande de colis | Poids, taille, description du contenu |
| 13 | Message de prévention | Envoyé automatiquement après acceptation |
| 14 | Messagerie | Discussion entre les deux personnes |
| 16 | Vérification avant remise | Case « Contenu vérifié ensemble » |
| 18 | Avis | Noter et commenter après la livraison |
| 19 | Signaler un utilisateur | Formulaire de signalement |
| 20 | Mon profil et réglages | Infos, notifications, aide, déconnexion |

**Plus tard (utile)** : 2 – Présentation · 15 – Appel · 17 – Suivi du colis (accepté, remis, livré)

---

## Stack technique

| Partie | Technologie |
|---|---|
| Backend | _À définir_ |
| Frontend (mobile) | _À définir_ |
| Base de données | _À définir_ |

---

## Démarrage

```bash
git clone https://github.com/<utilisateur>/weight-fly.git
cd weight-fly
```

- Backend : voir `backend/` _(à compléter)_
- Frontend : voir `frontend/` _(à compléter)_

---

## Feuille de route

| Quand | Action |
|---|---|
| Semaine 1 | Valider la liste des écrans ; les dessiner sur papier |
| Semaines 2 à 3 | Logo et maquette (bleu clair et blanc) ; retours de 5 à 10 personnes |
| Semaines 4 à 5 | Choisir la méthode de fabrication |
| Mois 2 à 3 | Construire le MVP : écrans essentiels + sécurité |
| Mois 3 à 4 | Tester avec un petit groupe ; faire relire les CGU |
| Lancement | Publier sur l'App Store et Google Play ; marketing sur un corridor précis |

---

🚧 **Statut** : projet en cours d'initialisation.
