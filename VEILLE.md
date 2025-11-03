# Veille — Notions & Vulgarisation 
**Cours :** Philomathia – Bases mathématiques pour la Data/IA  
**Date :** 03/11/2025  


> Chaque notion est présentée en **définition courte** puis en **image simple** pour un public non spécialiste.

1) **Vecteur**  
**Définition :** Objet mathématique ordonné (une liste de nombres) représentant une direction et/ou des caractéristiques.  
**Image simple :** Une flèche sur un plan ou une fiche produit avec des champs (taille, poids, prix) — la liste de valeurs est le vecteur.

2) **Matrice**  
**Définition :** Tableau rectangulaire de nombres (lignes × colonnes) permettant d’organiser des données ou de décrire des transformations.  
**Image simple :** Un fichier Excel: chaque ligne = individu, chaque colonne = variable.

3) **Probabilité / Loi de probabilité**  
**Définition :** Mesure (entre 0 et 1) de la chance qu’un événement se produise; une loi assigne des probabilités à tous les résultats possibles.  
**Image simple :** Lancer une pièce: pile ou face avec 50% chacun (loi de Bernoulli).

4) **Variables indépendantes**  
**Définition :** Deux variables X et Y sont indépendantes si connaître X ne change pas la probabilité de Y.  
**Image simple :** Lancer deux pièces différentes: le résultat de l’une n’influence pas l’autre.

5) **Espérance, Variance, Écart-type**  
**Définitions :** L’espérance = moyenne théorique; la variance = dispersion moyenne autour de la moyenne; l’écart-type = racine carrée de la variance.  
**Image simple :** Viser une cible: espérance = centre visé; variance/écart-type = serrage ou dispersion des impacts.

6) **Corrélation linéaire**  
**Définition :** Indice (entre -1 et 1) mesurant la force et le sens de l’association linéaire entre deux variables.  
**Image simple :** Plus on révise, plus la note monte (corrélation positive); plus on freine, moins la vitesse est élevée (corrélation négative).

7) **Moyenne, Médiane, Maximum, Minimum**  
**Définitions :** Moyenne = somme/n; médiane = valeur centrale; max/min = plus grande/petite valeur.  
**Image simple :** Dans une classe: la médiane partage la classe en deux groupes égaux; la moyenne est sensible aux notes extrêmes.

8) **Quartiles**  
**Définition :** Valeurs qui découpent les données en 4 parts égales: Q1 (25%), Q2 = médiane (50%), Q3 (75%).  
**Image simple :** Un box de 4 parts de pizza égales: chaque quartile marque une frontière.

9) **Boxplot (boîte à moustaches)**  
**Définition :** Graphique montrant médiane, Q1, Q3, et étendue (avec moustaches et éventuels outliers).  
**Image simple :** Une boîte (Q1–Q3), une ligne au milieu (médiane), des antennes (moustaches) et des points isolés (valeurs atypiques).

10) **Histogramme**  
**Définition :** Graphique qui regroupe les valeurs en classes (buckets) et affiche le nombre d’observations par classe.  
**Image simple :** Ranger des tailles en tranches (150–155 cm, 155–160 cm, …) et compter combien de personnes dans chaque tranche.

11) **Théorème Central Limite (TCL)**  
**Définition :** La moyenne d’un grand nombre d’observations indépendantes issues d’une même loi (de variance finie) suit approximativement une loi normale.  
**Image simple :** Additionner beaucoup de petites influences aléatoires produit une forme en cloche.
**Exemple concret :** moyenne de 30 tirages Uniforme[0,1], répétée 5 000 fois → histogramme en cloche (voir Notebook).


12) **Dérivée**  
**Définition :** Taux de variation instantané d’une fonction (pente de la courbe).  
**Image simple :** Le compteur de vitesse: la dérivée de la position par rapport au temps est la vitesse.
**Exemple concret :** pour f(x)=x^3−2x^2+x−1, la dérivée instantanée est f'(x)=3x^2−4x+1 (vitesse/pente ; voir Notebook).
