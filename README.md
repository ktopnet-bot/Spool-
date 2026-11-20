# Spool

Application web pour créer les spools d'un isométrique : on choisit l'ISO (et la page), une pièce de sa liste de matériel, la quantité (ou la longueur d'un tube) et le numéro du spool. Elle fonctionne dans le navigateur, sans serveur ; les données restent sur l'appareil.

**Créé par Kamel Nasralli** · Version 2.2 · Licence MIT

## Fonctionnalités

- **Créer spools** (onglet d'ouverture) : description en liste déroulante, quantité, n° de spool ; tubes répartis sur plusieurs spools (longueur découpée) avec leurs deux extrémités et la longueur de coupe ; joints à souder réglables par pièce (auto, 0 à 4) ; affectation de plusieurs pièces à la fois ; récapitulatif par spool (pièces, joints, pouces, kg).
- **Assemblage, Information, Rapport par spool** : liste de matériel, poids, surface de peinture, totaux par ISO et par spool.
- **Soudure, Soudure atelier (SW) et chantier (FW)** : joints et pouces à souder calculés sur la liste de matériel, une soudure par joint, filtre ISO + page.
- **Scanner d'isométriques** : lecture de la liste de matériel et repères de soudure (déplaçables).
- Export CSV / Excel / .json.

Les données de cette application sont séparées de celles de « Poids tuyauterie + scan » : on peut utiliser les deux sur le même site. Pour passer un projet de l'une à l'autre, utiliser la sauvegarde .json.

## Installation

Déposer tout le contenu du dossier à la racine du dépôt GitHub Pages (index.html, manifest.webmanifest, sw.js, icônes).
