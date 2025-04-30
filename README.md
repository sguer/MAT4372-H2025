# Évaluation d'Options sous Volatilité Stochastique
## Méthodes de Monte-Carlo avec Réduction de Variance

**Note importante : Travail en cours (Work in Progress)**

Ce dépôt présente une implémentation exploratoire des méthodes de Monte Carlo avec réduction de variance pour l'évaluation d'options dans un contexte de volatilité stochastique, avec ambition de suivre les grandes lignes de l'approche développée par Fouque & Tullie (2001).

## Contexte académique

Ce travail a été développé dans le cadre d'un examen oral en mathématiques financières avancées (MAT4372) sous la supervision du Prof. François-Michel Boire. L'objectif est d'illustrer l'application pratique des concepts théoriques de processus stochastiques et de changement de mesure, en progressant des modèles classiques (Black-Scholes-Merton) vers une compréhension plus réaliste des dynamiques de marché.

## État actuel et améliorations requises

### Fondements théoriques à compléter
- Expliciter les équations complètes du modèle et ses hypothèses sous-jacentes
- Détailler rigoureusement le passage de la mesure physique à la mesure risque-neutre
- Clarifier le cadre d'incomplétude de marché et ses implications sur l'unicité de la mesure

### Implémentation numérique à optimiser
- Vérifier la correction de l'implémentation de la dérivée de Radon-Nikodym
- Établir des benchmarks avec des prix théoriques de référence 
- Améliorer la discrétisation numérique
- Analyser systématiquement les erreurs de discrétisation

## Prochaines étapes

*À définir et documenter selon les commentaires de la grille d’évaluation et des notes de révision. Cette section sera mise à jour en conséquence.*


## Évaluation initiale

Les commentaires reçus lors de la présentation initiale ont souligné l'intérêt de la démarche, tout en recommandant:
- Une attention particulière à la précision de la discrétisation numérique
- Un renforcement du volet théorique sur les aspects de changement de mesure
- Une meilleure articulation entre le modèle mathématique et son implémentation

## Avertissement

Les résultats présentés sont exploratoires et ne doivent pas être considérés comme validés pour des applications réelles de tarification d'options. Ce travail représente une démarche pédagogique d'exploration des méthodes numériques avancées en mathématiques financières.


### Références principales
- Fouque, J.-P., & Tullie, T. A. (2002). Variance reduction for Monte Carlo simulation in a stochastic volatility environment. *Quantitative Finance*, 2(1), 24–30.
- Notes de cours et discussions avec Prof. François-Michel Boire (Université d'Ottawa, MAT4372).
