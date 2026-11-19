# Journal des modifications

## 1.5
- SW + FW = total de l'onglet « Soudure » : le chantier (FW) reprend aussi les joints prévus par la règle automatique mais non retenus dans les spools créés.

## 1.4
- Onglet « Soudure » : total des pouces et joints calculé d'après la liste de matériel avec les règles automatiques (coude 2 joints, té 3 joints…), avec écart signalé si les spools retiennent moins de joints.
- Onglet « Soudure atelier (SW) » : pouces et joints d'après les pièces affectées dans « Créer spools » (joints choisis).
- Onglet « Soudure chantier (FW) » : reste des pièces non affectées à un spool.

## 1.3
- Données qui disparaissaient : synchronisation entre onglets/fenêtres (une fenêtre ancienne n'écrase plus les données récentes), copie de secours dans IndexedDB, stockage persistant demandé au navigateur, ISO et marquages X mémorisés par projet.
- « Créer spools » : la liste de matériel se marque par un X ; toucher un coude, té, vanne, etc. ouvre une fenêtre qui demande le nombre de joints (tube : longueur et extrémités).

## 1.1
- Nouvelle identité : icône violette (tuyau à bride, points de soudure), entête violet avec motif de spool, pour se distinguer des autres applications.

## 1.0
- Première version de l'application Spool, issue de « Poids tuyauterie + scan » v9.9 : ouverture sur « Créer spools », stockage séparé.
