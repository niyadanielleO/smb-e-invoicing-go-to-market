# Note de cadrage — Lancer une offre de facturation électronique pour les TPE-PME

**Projet :** De la voix du client au go-to-market
**Auteure :** N. Danielle OUATTARA
**Version :** 1.0 — octobre 2026

---

## 1. Contexte

La réforme de la facturation électronique impose à toutes les entreprises assujetties à la TVA en France de pouvoir **recevoir** des factures électroniques depuis le 1er septembre 2026, et aux PME et micro-entreprises de les **émettre** à partir du 1er septembre 2027.

Des centaines de milliers de très petites entreprises doivent donc choisir une solution en moins d'un an. Pour un éditeur de logiciel, c'est une fenêtre de lancement rare : le besoin est créé par la loi, la date butoir est connue, mais la cible est peu équipée, peu informée et attentive au prix.

## 2. Objectif du projet

Construire, à partir de données réelles, le dispositif de marketing produit d'une offre fictive de facturation électronique, Duo Facture, destinée aux TPE-PME : qui cibler, avec quel message, à quel prix et par quels canaux.

## 3. Questions posées

1. **Marché** : combien d'entreprises sont concernées, et lesquelles sont les moins prêtes ?
2. **Clients** : quels segments se distinguent par leur équipement, leurs freins et leur budget ?
3. **Concurrence** : comment les offres existantes sont-elles positionnées et tarifées ?
4. **Positionnement** : quelle promesse peut différencier une nouvelle offre ?
5. **Lancement** : par quels prescripteurs et quels canaux toucher la cible, avec quels indicateurs ?

## 4. Données

| Source | Contenu | Licence |
|---|---|---|
| Baromètre France Num 2022 (DGE, enquête CREDOC) | 4 671 dirigeants de TPE-PME : équipement numérique, attitudes, freins, budget, prescripteurs. Données individuelles pondérées | Licence Ouverte 2.0 |
| INSEE | Nombre d'entreprises par taille et par secteur, pour dimensionner le marché | Licence Ouverte 2.0 |
| Eurostat, usage des TIC dans les entreprises | Part des entreprises émettant des factures électroniques, par taille et par pays | CC BY 4.0 |
| Pages tarifaires publiques des éditeurs | Offres, prix et fonctionnalités, relevés à date et sources citées | Informations publiques |

Toutes les proportions issues du baromètre sont **pondérées** (variable `POIDS`) pour être représentatives des TPE-PME françaises.

## 5. Premiers constats (baromètre France Num 2022, pondéré)

| Indicateur | Ensemble | 0 salarié | 1 à 9 | 10 à 49 | 50 à 249 |
|---|---|---|---|---|---|
| Équipées d'une solution de facturation | 69,5 % | 67,5 % | 66,3 % | 86,8 % | 91,0 % |
| Prévoient de s'équiper dans les 12 mois | 2,5 % | 4,0 % | 2,1 % | 2,0 % | 1,9 % |
| Budget numérique annuel de 500 € ou moins | 46,2 % | 51,7 % | 49,2 % | 26,1 % | 15,2 % |
| Craignent la perte ou le piratage de données | 44,1 % | 43,8 % | 44,7 % | 44,2 % | 31,0 % |

Parmi les entreprises **non équipées** d'une solution de facturation :
- 57 % ont dépensé 500 € ou moins en numérique l'année précédente, contre 42 % des entreprises équipées ;
- 40 % déclarent n'avoir « pas de réel projet » numérique, contre 28 % ;
- 40 % seulement ont une solution comptable, contre 85 % chez les entreprises équipées.

**Lecture :** environ trois TPE sur dix n'ont pas d'outil de facturation et ne prévoient pas d'en avoir. Elles sont surtout petites, peu dotées en budget et peu engagées dans le numérique. La réforme les oblige pourtant à s'équiper : l'enjeu marketing n'est pas de créer le besoin, mais de lever les freins (prix, complexité, sécurité) et de passer par les bons prescripteurs.

## 6. Livrables

| # | Livrable | Format |
|---|---|---|
| 1 | Dimensionnement du marché (TAM, SAM, SOM) | Notebook + note |
| 2 | Analyse de la voix du client : segments, freins, attentes | Notebook Python |
| 3 | Trois personas fondées sur les données | Document |
| 4 | Paysage concurrentiel et carte de positionnement | Document |
| 5 | Positionnement et messaging house | Document |
| 6 | Battlecard face au principal concurrent | Document |
| 7 | Recommandation de pricing et de packaging | Document |
| 8 | Plan de lancement à 90 jours, canaux et KPI | Document |

## 7. Limites connues

- Le baromètre date de 2022, avant l'entrée en vigueur de la réforme : il décrit le point de départ des entreprises, pas leur situation actuelle.
- La part de factures « électroniques structurées » est déclarative : beaucoup de dirigeants confondent probablement un PDF envoyé par e-mail avec une facture électronique au sens de la réforme. Cette confusion est elle-même un enseignement pour le message.
- L'offre étudiée est fictive. Les données sur les concurrents proviennent de leurs pages publiques, à la date du relevé.
