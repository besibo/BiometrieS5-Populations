# TP Biométrie S5 — Dynamique des Systèmes Écologiques

Support pédagogique des travaux pratiques de modélisation et de dynamique des populations destinés aux étudiants de Licence 3 Sciences de la Vie (Semestre 5) à La Rochelle Université.

Ces séances s'inscrivent dans l'UE Biométrie en lien direct avec le cours magistral « Introduction à la dynamique des systèmes » (EC *Fonctionnement des Écosystèmes*), dispensé par Florian Orgeret.

---

## Accès au manuel en ligne

Le livre complet est consultable à l'adresse suivante :  
https://besibo.github.io/BiometrieS5-Populations/

---

## Contenu des séances

1. **TP 1 — Structure et démographie des populations** (`01-Structure.qmd`)  
   Modèles de capture-marquage-recapture (CJS avec `marked`) et matrices de projection démographique (`popbio`).

2. **TP 2 — Analyse de cohortes** (`02-Cohortes.qmd`)  
   Décomposition de distributions polymodales (`mixdist`), courbes de croissance, de survie et courbes d'Allen.

3. **TP 3 — Systèmes dynamiques** (`03-DynamicSystems.qmd`)  
   Modèles discrets et continus, croissance logistique, dynamique prédateurs-proies (Lotka-Volterra) et compétition interspécifique.

4. **TP 4 — Chaînes de Markov et successions écologiques** (`04-MarkovChains.qmd`)  
   Matrices de transition écologique, simulations paysagères et calcul de l'état stationnaire.

---

## Compilation

Pour générer le site localement avec Quarto :

```powershell
quarto render --to html