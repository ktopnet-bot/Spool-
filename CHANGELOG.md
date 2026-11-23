# Journal des modifications

## 3.0
- Import : un tube de plus de 12 m dans un spool est coupé automatiquement en parties de 12 m maximum (spools SP04, SP04-B…), avec un joint FW chantier ajouté.

## 2.9
- « Créer spools » : option « Coller du JSON ou du CSV » : on colle le texte reçu de Claude (même avec du texte autour), résumé puis import.

## 2.8
- Le bouton d'import de « Créer spools » accepte maintenant aussi les PDF (« Importer des spools (PDF ou JSON) ») : un PDF est lu par Claude pour l'ISO choisi (aperçu à valider) ; si Claude est indisponible, un message explique comment obtenir un JSON à importer.

## 2.7
- « Lire l'isométrique avec Claude » (version publiée sur claude.ai) : accepte directement un PDF (choix de la page, dessin rendu en entier et recadré, repères SP lus dans le texte du PDF) ou une image ; Claude repère les X, les repères SP et les cotes ; aperçu avec l'image à valider avant création des spools. Si Claude n'est pas accessible, un message donne la raison et un mode copier/coller est proposé.

## 2.6
- « Créer spools » : bouton « Importer des spools (fichier) » : charge un fichier JSON ou CSV déjà réparti par spool ; résumé (lignes, spools, ISO) puis Importer / Ajouter / Remplacer les ISO existants ; les spools apparaissent créés avec poids, peinture et soudures.

## 2.5
- Tubes : choix du nombre de joints (auto, 0, 1, 2, 3, 4) dans la fenêtre de « Créer spools » et dans les lignes de spool.

## 2.4
- Vannes : nouveau choix « Raccordement » (formulaire Information) : bridée RF/RTJ = 0 joint (par défaut), BW ou SW = toujours 2 joints × diamètre. Le scanner reconnaît BW / SW dans la description.

## 2.3
- Vannes à brides (RF / RTJ) : 0 joint, aucun pouce à souder (montage boulonné), y compris les petites vannes ≤ 2". Seule une vanne BW compte 2 joints.

## 2.2
- « Déplacer vers une autre page » disponible pour toutes les pièces : brides, vannes, coudes, tés, accessoires et pièces libres (la pièce libre ouvre maintenant la fenêtre, sans choix de joints).

## 2.1
- « Créer spools » : dans la fenêtre d'une pièce, « Déplacer vers une autre page » coupe un tube (ou déplace des pièces) vers une autre page du même ISO (ex. de P3 vers P4) pour continuer un spool.

## 2.0
- Onglet « Rapport par spool » renommé « Rapport par page/Spool » (Report per page/Spool).

## 1.9
- Aide : le bouton « ? » en haut (près de l'icône de scan) contient maintenant le principe du programme, le mode d'emploi et les anciennes définitions, en français et en anglais ; l'onglet « Aide » est supprimé.
- Traduction anglaise de l'onglet Soudure et de l'onglet « Créer spools ».

## 1.8
- Nouvel onglet « Aide » : principe du programme et mode d'emploi (scanner, créer les spools, soudures SW/FW, conseils).

## 1.7
- Fenêtre de joints : choix adaptés à la pièce (coude 0-2, té 0-3, vanne 0-2…).
- Quantité ou longueur supérieure à la liste de matériel : la fenêtre vibre et demande de vérifier les quantités.

## 1.6
- « Créer spools » : boulonnerie jamais affichée ; chaque spool a une couleur de fond différente.
- Pouces à souder affichés avec 2 décimales (ex. 2,75).
- Soudure chantier (FW) : repère des spools reliés par chaque soudure (ex. SP3/SP4), modifiable.

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
