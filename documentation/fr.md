<!-- ELUCENIA technical documentation · indice-de-producao-reticulocitaria · fr · no clinical/professional/rights approval -->

# Réticulocytes corrigés et indice de production réticulocytaire

[conditions, sources et autorisations](https://elucenia.org/fr/outils/indice-de-producao-reticulocitaria)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Réticulocytes

`ret`

% · intervalle: 0–50

### Hématocrite

`ht`

% · intervalle: 5–65

## Édition de la méthode

Hillman 1969 : hématocrite 45 % ; maturation 1/1,5/2/2,5 selon plages locales 40/30/20

## Formule documentée

Réticulocytes corrigés (%) = réticulocytes (%) × hématocrite ÷ 45.

RPI = Réticulocytes corrigés ÷ facteur de maturation, le facteur est la maturation sanguine en jours: 1,0 (hématocrite ≥ 40%); 1,5 (30–39%); 2,0 (20–29%); 2,5 (\< 20%).

## Limites et population

La correction réticulocytaire dépend de la variation du temps de maturation associée à la sévérité de l’anémie. L’étude originale utilisait une anémie induite par phlébotomie chez des personnes saines ; les intervalles locaux simplifiés n’ont pas été confirmés par le résumé. L’indice ne détermine pas seul l’étiologie ou la réserve médullaire dans toute maladie.

## Références

- [Hillman RS. Characteristics of marrow production and reticulocyte maturation in normal man in response to anemia. J Clin Invest, 1969.](https://doi.org/10.1172/JCI106001)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

IPR < 2 : anémie hypoproliférative (production insuffisante)

| Détails du résultat | |
| --- | --- |
| Réticulocytes corrigés par l’hématocrite | 3,3% |
| Facteur de maturation utilisé | 2,0 jour(s) |


### 2

IPR ≥ 3 : réponse médullaire adéquate (hémolyse ou perte aiguë)

| Détails du résultat | |
| --- | --- |
| Réticulocytes corrigés par l’hématocrite | 6,7% |
| Facteur de maturation utilisé | 1,5 jour(s) |


### 3

IPR < 2 : anémie hypoproliférative (production insuffisante)

| Détails du résultat | |
| --- | --- |
| Réticulocytes corrigés par l’hématocrite | 3,0% |
| Facteur de maturation utilisé | 2,0 jour(s) |


### 4

IPR entre 2 et 3 : réponse limite

| Détails du résultat | |
| --- | --- |
| Réticulocytes corrigés par l’hématocrite | 4,0% |
| Facteur de maturation utilisé | 2,0 jour(s) |

