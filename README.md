# Dégué Manager — local, avec rôles et impressions

Application React + Vite avec stockage local `localStorage` (pas de base de données).

## Installation
```powershell
npm install
npm run dev
```

## Premier accès administrateur
- Identifiant initial : `admin`
- Mot de passe initial : `admin123`

Aucun compte caissière n’est créé par défaut. Connecte-toi en administrateur, ouvre **Comptes caissières**, puis crée un compte individuel pour chaque caissière. Les identifiants créés sont enregistrés dans le stockage local du navigateur.

## Fonctions
- Rôles administrateur et caissière. Seul l’administrateur peut créer ou supprimer les comptes caissières.
- Produits et suppléments : création, modification et suppression par l'administrateur.
- Ventes, panier et dépenses.
- Impression des reçus depuis la confirmation d'une vente ou l'historique. La boîte d'impression du navigateur permet aussi de choisir une imprimante ou « Enregistrer au format PDF ».
- Export des rapports filtrés en fichier PDF avec ventes, dépenses et résultat.
- Données stockées localement dans le navigateur de l'ordinateur. Elles ne sont pas synchronisées et peuvent être perdues si les données du navigateur sont effacées.

Les comptes sont prévus pour une démonstration locale ; ce système ne constitue pas une sécurité forte face à une personne ayant accès au code du navigateur.
