# **Simulation des Équations de Navier-Stokes 2D** 
## **Introduction** 
Ce projet vise à simuler des écoulements fluides en résolvant les équations de Navier-Stokes en deux dimensions (2D) pour un fluide incompressible. Cette première étape du projet constitue le fondement de la résolution numérique et l'implémentation des outils nécessaires pour modéliser les phénomènes dynamiques des fluides. 

Les résultats finaux viseront à étudier : 

1. L'instabilité de Kelvin-Helmholtz dans une couche de mélange. 
1. Le mouvement d'un dipôle de vorticité. 

Cette première partie est un point de départ. Elle inclut la mise en œuvre des algorithmes fondamentaux et la configuration des conditions initiales et des limites. Les étapes suivantes se concentreront sur l'optimisation, l'intégration des scénarios physiques spécifiques et l'analyse approfondie des résultats. 
## **Structure du Code (1ere Partie)** 
### **Étapes implémentées dans cette partie** 
1. **Méthode de Projection :** 
- Calcul d'un champ de vitesse non-solénoïdal (étape de prédiction). 
- Projection pour obtenir un champ de vitesse solénoïdal. 
2. **Gestion des Conditions Initiales :** 
- Implémentation des champs dynamiques initiaux pour les cas simulés. 
3. **Résolution Numérique :** 
- Mise en place des matrices discrétisées et des solveurs FFT. 
4. **Visualisation préliminaire :** 
- Suivi de la vorticité et des scalaires passifs 
