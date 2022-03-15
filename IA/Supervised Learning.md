Source : [[MACHINE LEARNING]]
Date : 202106292355
---

## Supervised Learning

### Définition 

1. Donner un algorithme au système pour réaliser une tâche afin de produire un Output
2. Indiquer la bonne réponse au système 
3. Il va mesurer l’erreur entre la bonne réponse et son Output
4. Il va modifier ensuite son algorithme dans le but de **minimiser son erreur** en **améliorant sa performance** (minimiser la _fonction coût_)

### Composantes

1. **Un dataset** : m x n
	1. **Targets** -> Prix 
	2. **Features** -> Surface, Qualité, Adresse...


2. ** Un modèle** : 
	1. $f(x) = ax^2 + bx + c$
	2. $a$, $b$, $c$ -> paramètres 


3. **Fonction coût** :
	1. L'ensemble des éloignement des prédictions à la target donnent cette fonction
	2. **Mean Squared Error** (Erreur quadratique moyenne) : 
		1. $J(a,b)= \frac {1}{2m} * \sum_{i=1}^m [(F(x^i) - y^i)²]$	


4. Algorithme d'apprentissage pour minimiser la **MSE** -> **Gradient Descent**


### 2 types de problèmes

[[Regression]]

[[Classification]]
