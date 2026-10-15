# Audit global du projet PCE

Date : 15 octobre 2026. Périmètre : prototype, pitch, business plan, BMC, charte, mise en ligne. La présentation n'a pas été retravaillée (hors périmètre demandé).

## 1. Compatibilité du prototype

| Contrôle | Résultat |
|---|---|
| Erreurs JavaScript, 12 pages × 7 largeurs (360 à 1920 px) | Aucune |
| Débordement horizontal | Aucun (corrigé sur l'espace pro en 360 px) |
| Parcours complet (dépôt, charte signée, certification, vérification, espace pro, export CSV) | OK |
| Navigation clavier, focus visible | OK |
| Images sans texte alternatif, liens internes cassés | Aucun |
| Fonctionnement hors ligne (fichier unique) et sur Vercel | OK |
| Safari : flou de l'en-tête | Préfixe `-webkit-` ajouté |

Limites : tests faits dans Chromium (moteur de Chrome et Edge). Firefox et Safari n'ont pas pu être testés ici. Les données restent dans le navigateur de chaque visiteur.

## 2. Cohérence entre livrables : écarts trouvés et corrections

| Écart | Correction |
|---|---|
| Le sceau affichait « Certifié par COFRAC » alors que l'accréditation est prévue en année 2 | Sceau refait en SVG à l'identique, avec « Commission PCE » en bas, sur le site, le pitch et le BMC |
| Abonnement à prix fixe (9 €/mois) | Abonnement sur mesure à partir de 9 € HT/mois, selon le nombre de créations, la taille de la structure, l'ampleur du processus et l'étude du dossier. Estimateur sur le site, calcul au dépôt, grille dans le BP |
| Le BMC disait « engagement anti-IA générative » | Remplacé par « IA maîtrisée par l'humain », comme dans les tests J3 et la charte |
| Le BMC listait licences, volume institutions et sponsoring en revenus | Revenus alignés : abonnement sur mesure et certification à l'unité |
| Le BMC ne mentionnait ni la charte, ni l'AFNOR, ni le COFRAC, ni le seuil de 10 % | Ajoutés |
| Le BP n'avait aucun coût pour la feuille de route AFNOR et COFRAC | Ajoutés en sous-traitance : 5 000 € (année 1), 15 000 € (année 2), 8 000 € (année 3) |
| « 100 premiers freelances » (oral) contre 500 clients en année 1 (BP) | Précisé dans l'onglet Hypothèses : 100 pilotes, puis 500 clients payants en fin d'année 1 |
| Le pitch parlait de « créatifs indépendants » seulement | Ajout des studios et agences, cohérent avec l'abonnement sur mesure |
| La charte n'apparaissait pas dans le pitch | Mentionnée dans la solution et la démonstration |
| Le BP n'expliquait pas ses chiffres | Onglet Hypothèses ajouté |

## 3. Business plan après correction

| | Année 1 | Année 2 | Année 3 |
|---|---|---|---|
| Clients | 500 | 1 575 | 3 308 |
| Chiffre d'affaires HT | 68 500 € | 215 775 € | 453 128 € |
| Charges d'exploitation | 89 700 € | 171 850 € | 330 425 € |
| EBE | -21 200 € | 43 925 € | 122 703 € |
| Trésorerie finale | 19 800 € | 49 725 € | 158 428 € |

## 4. Points restant à votre charge

- **Hypothèses non sourcées** : marché de 250 000 créatifs, grille d'abonnement, coûts AFNOR et COFRAC, subvention de 15 000 €. À vérifier ou à présenter comme hypothèses.
- **Présentation** : non mise à jour. Elle contient l'ancien prix fixe, les anciens chiffres du BP et l'ancienne charte graphique.
- **Charte** : document fourni tel quel. Il contient des tirets longs (« Article 1 – … ») et dit « Label Officiel ».
- **Revenu moyen de 137 € par client** : prudent pour des studios et agences. Peut être relevé si le jury le questionne.
