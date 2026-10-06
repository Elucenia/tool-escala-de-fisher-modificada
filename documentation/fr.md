<!-- ELUCENIA technical documentation · escala-de-fisher-modificada · fr · no clinical/professional/rights approval -->

# Échelle de Fisher modifiée

[conditions, sources et autorisations](https://elucenia.org/fr/outils/escala-de-fisher-modificada)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Résultat de la tomodensitométrie à l’admission

`grau`

- `0` — 0 – Aucune HSA ni hémorragie intraventriculaire
- `1` — 1 – HSA fine (focale ou diffuse), sans hémorragie intraventriculaire
- `2` — 2 – Hémorragie intraventriculaire avec absence d’HSA ou HSA fine (focale ou diffuse)
- `3` — 3 – HSA épaisse (focale ou diffuse), sans hémorragie intraventriculaire
- `4` — 4 – HSA épaisse avec hémorragie intraventriculaire

## Édition de la méthode

Fisher modifiée — Frontera et al., 2006, tableau 1 : HSA absente, fine ou épaisse et hémorragie intraventriculaire ; grades 0–4

## Formule documentée

Classe la TDM à l’admission selon la présence et l’épaisseur du sang sous-arachnoïdien (HSA) et la présence d’une hémorragie intraventriculaire (HIV). Grade 0 : absence d’HSA et d’HIV ; grade 1 : HSA fine sans HIV ; grade 2 : HIV avec HSA absente ou fine ; grade 3 : HSA épaisse sans HIV ; grade 4 : HSA épaisse avec HIV. Dans Frontera et al. (2006), les investigateurs locaux ont classé le sang comme fin ou épais selon leur impression globale, sans critères explicites d’épaisseur. L’outil enregistre le grade choisi par l’examinateur ; il n’interprète pas les images.

## Limites et population

Classification tomodensitométrique étudiée pour prédire le vasospasme symptomatique après une hémorragie sous-arachnoïdienne. L’étude consultée a réuni des patients des bras placebo de quatre essais. Elle ne fournit pas, seule, un diagnostic de vasospasme, une prédiction de tous les résultats ou une indication de traitement.

## Références

- [Frontera JA et al. Prediction of symptomatic vasospasm after subarachnoid hemorrhage: the modified Fisher scale. Neurosurgery, 2006.](https://doi.org/10.1227/01.NEU.0000218821.34014.1B)

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

Grade 0 : pas de sang sous-arachnoïdien ou intraventriculaire


### 2

Grade 2 : vasospasme symptomatique dans 33%


### 3

Grade 4 : vasospasme symptomatique dans 40%

