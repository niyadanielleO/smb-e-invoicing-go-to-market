# Pricing et packaging — Duo Facture

Ce document fixe les offres et les prix de Duo Facture. Il s'appuie sur trois éléments : les budgets numériques déclarés dans le baromètre France Num 2022, les prix publics des concurrents relevés le 20 octobre 2026 (`docs/paysage_concurrentiel.md`), et le positionnement « simple et accompagné » (`docs/positionnement_messaging.md`).

---

## 1. Les contraintes de prix

**Le prix de référence du marché est zéro.** Indy, Tiime et Abby proposent une offre gratuite qui couvre l'émission, la réception et l'e-reporting. Une offre d'entrée payante serait écartée dès la comparaison.

**Les budgets des segments cibles sont faibles** (baromètre France Num 2022, pondéré) :

| Budget numérique de l'année précédente | Sophie (prête à investir) | Jean-Marc (budget serré) |
|---|---|---|
| Aucun | — | 52 % |
| Moins de 100 € | — | 20 % |
| 100 à 500 € | — | 28 % |
| 500 à 1 000 € | 35 % | — |
| 1 000 à 2 000 € | 28 % | — |
| Plus de 2 000 € | 36 % | — |

Pour l'année suivante, 38 % du segment de Jean-Marc prévoient un budget de 500 € ou moins, et 21 % ne savent pas l'estimer. Une offre payante pour ce segment doit donc rester sous 10 € par mois, soit environ 120 € par an.

**Les prix payants des concurrents se situent entre 9 et 18 € par mois** pour le premier palier : Indy Plus à 9 €, Abby Start à 9 €, Freebe à 12,50 € TTC, Tiime Smart à 17,99 €. L'accompagnement par un expert-comptable commence à 63 € chez Indy.

## 2. La grille proposée

| | **Découverte** | **Essentiel** | **Accompagné** |
|---|---|---|---|
| **Prix HT** | **0 €** | **9 € / mois** en annuel (11 € en mensuel) | **19 € / mois** en annuel (23 € en mensuel) |
| **Pour qui** | Jean-Marc, et tout nouveau client | Jean-Marc qui veut gagner du temps, Sophie | Sophie, et les TPE qui veulent déléguer |
| Émission, réception, e-reporting | Oui | Oui | Oui |
| Devis et factures illimités | Oui | Oui | Oui |
| Séance de mise en route (30 min) | **Oui, une fois** | Oui | Oui |
| Accès gratuit pour le comptable | **Oui** | Oui | Oui |
| Support par une personne | E-mail | E-mail et téléphone | Conseiller attitré |
| Relances automatiques et paiement en ligne | — | Oui | Oui |
| Archivage à valeur probante (10 ans) | — | Oui | Oui |
| Suivi des relances par un conseiller | — | — | Oui |
| Point trimestriel avec un conseiller | — | — | Oui |

**Services ponctuels**
- **Migration depuis un autre outil** (pour Karim) : 49 € HT, offerts pour un engagement annuel sur Essentiel ou Accompagné.
- **Diagnostic de conformité** : gratuit, en ligne, sans inscription. C'est le produit d'appel pour Karim.

**Offre cabinets comptables**
- Tableau de bord multi-clients gratuit.
- Rémunération de 2 € HT par mois et par client payant recommandé par le cabinet, versée tant que le client reste abonné.

## 3. Pourquoi cette grille

1. **L'entrée gratuite inclut ce que les concurrents n'offrent pas** : la séance de mise en route et l'accès du comptable. C'est le pilier « accompagné » de la messaging house, rendu visible dès le premier palier.
2. **Essentiel est aligné sur le prix plancher du marché** (9 €), mais contient l'archivage à valeur probante, que Tiime facture 17,99 €. L'argument de valeur est concret.
3. **Accompagné reste trois fois moins cher** que l'offre avec expert-comptable d'Indy (63 €), tout en apportant un conseiller attitré. Il ne remplace pas le comptable : il s'appuie sur lui.
4. **Le paiement annuel est encouragé** (environ −18 %), car il réduit le risque de départ, enjeu central sur un marché où l'alternative est gratuite.

## 4. Revenu attendu

Hypothèse de répartition des clients à trois ans : **60 % en Découverte, 30 % en Essentiel, 10 % en Accompagné**.

| | Calcul | Résultat |
|---|---|---|
| Revenu moyen par client (ARPU) | 0,30 × 9 € + 0,10 × 19 € | **4,60 € HT par mois** |
| Scénario central | 37 496 clients × 4,60 € × 12 | **≈ 2,1 M€ par an** |
| Scénario prudent | 22 226 clients | ≈ 1,2 M€ par an |
| Scénario ambitieux | 52 766 clients | ≈ 2,9 M€ par an |

Ce revenu est **trois fois inférieur** à l'hypothèse provisoire du dimensionnement du marché (15 € par mois pour tous les clients, soit 6,7 M€). L'écart vient de la gratuité, devenue la norme. Le notebook `02_dimensionnement_marche.ipynb` est mis à jour avec ce calcul.

**Les deux leviers qui comptent le plus :**
- **le taux de conversion vers un palier payant** : passer de 40 % à 50 % de clients payants augmente le revenu d'un quart environ ;
- **le canal des cabinets comptables** : chaque cabinet partenaire peut apporter plusieurs dizaines de clients, à un coût d'acquisition bien inférieur à la publicité.

## 5. Ce qu'il faudra tester

- **Le prix d'Accompagné** : 19 € ou 25 €. Test de sensibilité au prix (méthode Van Westendorp) auprès d'une centaine de dirigeants du segment de Sophie.
- **La conversion de Découverte vers Essentiel** : mesurer le taux de passage à 30 et 90 jours, et vérifier que l'archivage est bien l'élément déclencheur.
- **La rémunération des cabinets** : 2 € par mois et par client suffit-il à motiver un cabinet ? À vérifier lors des entretiens avec cinq cabinets.
