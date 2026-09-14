# TP de Biométrie — Populations

Ouvrage autonome issu de `BiometrieS5`. Le livre original est conservé.

## Contenu

- `index.qmd`
- `04-Structure.qmd`
- `05-Cohortes.qmd`
- `06-DynamicSystems.qmd`
- `07-MarkovChains.qmd`
- `references.qmd`

## Personnalisation et publication

- `index.qmd` est une copie intégrale de l'introduction actuelle du livre original, y compris ses blocs R. Adapter les objectifs, l'organisation, les intervenants, les dates, la progression et l'évaluation à ce livre.
- L'auteur dans `_quarto.yml` est conservé tel quel et reste à personnaliser.
- Le titre et la liste des chapitres sont adaptés. Les chapitres seront numérotés automatiquement au sein de chaque nouveau livre ; leurs noms de fichiers sont conservés.
- L'ancien `repo-url` a été retiré : renseigner l'adresse du nouveau dépôt lorsqu'il sera publié.
- Le thème, les extensions et les bibliographies sont copiés. Les ressources locales référencées sont incluses.
- Aucun rendu ni cache du livre original n'est copié. Aucune compilation n'a été exécutée.

## Renvois à adapter après la séparation

Les renvois suivants ciblent des sections absentes de cet ouvrage. Ils sont conservés dans les sources pour permettre leur adaptation lors de la personnalisation de l'introduction. Aucune adresse de publication n'est inventée.

| Fichier | Ligne | Renvoi |
|---|---:|---|
| `index.qmd` | 230 | `@sec-moy1` |
| `index.qmd` | 230 | `@sec-exo1` |
| `index.qmd` | 232 | `@sec-moy2` |
| `index.qmd` | 232 | `@sec-moy3` |

## Point préexistant à vérifier avant compilation

Dans `05-Cohortes.qmd`, ligne 81, le chemin est écrit `Data/Nassarius.csv`, alors que le dossier s'appelle `data`. Ce point est conservé pour garder les chapitres identiques à l'original ; il faudra harmoniser la casse avant une compilation sur un système sensible à la casse.
