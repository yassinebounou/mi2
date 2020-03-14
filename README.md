# Maths de l’ing ́enieur 2

## I. Calcul diff ́erentiel

1. D ́eriv ́ee
* d ́erivabilit ́e locale et propri ́et ́es (unicit ́e, continuit ́e), d ́erivabilit ́e globale
* exemples fondamentaux : applications lin ́eaires, affines, bilin ́eaires, quadratiques
* d ́erivation des fonctions compos ́ees
* applications composantes

2. D ́erivation partielle
* applications et d ́eriv ́ees partielles en un point, matrice jacobienne
* ́equivalence en classe C 1 et contrexemple
* th ́eor`eme de Schwarz
* gradient, hessien, laplacien
* exemple fondamental : forme quadratique

3. Accroissements finis
* th ́eor`eme des accroissements finis (premi`ere et deuxi`eme forme)
* th ́eor`eme des fonctions implicites
* algorithme de Newton

## II. Espaces vectoriels norm ́es
* norme, boules ouvertes et ferm ́ees
* parties ouvertes, ferm ́ees, adh ́erence
* suites, caract ́erisation s ́equentielle des parties ferm ́ees
* continuit ́e, caract ́erisation s ́equentielle, cas des applications lin ́eaires
* suites de Cauchy, parties compl`etes, th ́eor`eme du point fixe
* parties compactes, cas de la dimension finie, image continue d’un
compact

### III. Espaces de Hilbert
1. Produit scalaire
* produit scalaire, théorème de Cauchy-Schwarz, norme associée (Minkowski)
* espace préhilbertien, hilbertien, euclidien
* exemples : $\mathbf{R}^n$, $\mathrm{M}(m,n,\mathbf{R})$, $\mathrm{L}^2(X,\mathscr{B},\mu)$, $\ell^2(\mathbf{N})$

2. Théorème de la projection
* distance d'un point à une partie, projeté, partie convexe
* identité du parallélogramme, théorème de la projection
* caractère $1$-lipschitzien de la projection

3. Orthogonalité
 * orthogonal d'une partie, propriétés de base
 * supplémentaire orthogonal d'un sev fermé
 * double orthogonal
 * base hilbertienne, Parseval

4. Séries de Fourier trigonométriques
* base hilbertienne trigonométrique sur $\mathrm{L}^2_{2\pi}(\mathbf{R})$ (et $\mathrm{L}^2_{2\pi}(\mathrm{C})$)
* résultats de convergence complémentaires, cas $\H^1_{2\pi}$ et $\mathscr{C}^1$ par morceaux (Dirichlet)
* transformée de Fourier discrète, FFT
* extension au cas multidimensionnel

## IV. Formulation faible de pb aux limites
1. Distributions
* motivation : solutions généralisées de $xy'(x)=0$
* ensemble $\mathscr{D}(\Omega)$ (dimension un), exemple canonique de fonction plate
* ensemble $\mathscr{D}'(\Omega)$, notion d'ordre d'une distribution
* exemples : (i) fonctions localement intégrables, (ii) valeur principale, (iii) mesures
* dérivation d'une distribution (motiver par le cas $\mathscr{C}^1$), exemples
(Heaviside, Dirac)
* résolution de $T'=0$
* produit par une fonction $\mathscr{C}^\infty$, règle de Leibniz associée
* résolution de $xT=0$
* convergence (faible) dans $\mathscr{D}'(\Omega)$, continuité de la dérivation

2. Formulation faible en dimension un
* motivation : notion de solution faible pour $-u''+u=f$ sur $]0,1[$, conditions de Neumann
* définition de $\mathrm{H}^1(]0,1[)$ et propriétés (caractère hilbertien, injection $\mathscr{C}^0([0,1])$,
intégration par parties)
* théorème de Riesz (complément du III)
* démarche variationnelle :
    * A. Toute solution forte est solution faible
    * B. Existence et unicité de solution faible
    * C. Régularité de la solution faible
    * D. Retour à une solution forte

## Organisation et intervenants
* 12 séances (1 séance = 1H CM + 2H TD)
* [J.-B. Caillau](mailto:jean-baptiste.caillau@univ-cotedazur.fr)
* [L. Monasse](mailto:laurent.monasse@inria.fr)

## Évaluation
* 2 EX CC (coeff. 1 tous les deux)
* 1 EX terminal (coeff. 2)

## Bibliographie
1. Brézis, H. _Analyse fonctionnelle, théorie \& applications._ Dunod, 2005.
2. Exo7. [_Cours de mathématiques de première année._](http://exo7.emath.fr)
3. Gasquet, C.;  Witomski, P. _Analyse de Fourier et applications._ Dunod, 2000.
4. Liret, F.; Martinais, D.
{\em Analyse~: cours de première année.} Dunod, 2003.
5. Monasse, D. _Cours de Mathématiques pour les classes MP et MP$^*$._ Vuibert, 1997.
6. Schwartz, L. _Méthodes mathématiques pour les sciences physiques._ Hermann, 1966.
7. Zuily, C. _Éléments de distributions et d'équations aux dérivées partielles._ Dunod, 2002.
