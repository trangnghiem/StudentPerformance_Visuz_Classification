# StudentPerformance_Visuz_Classification
Ce dataset s’appelle Kalboard 360, collecté en 2016 par le système de management d’étude.

Ce dataset comprend 480 lignes et 16 caractères (features). Les features sont classé en trois grandes catégories :
Caractères démographiques telles que le sexe et la nationalité.
Caractères de formation académique telles que le niveau éducatif, le niveau scolaire et la section
Caractères comportementales, telles que nombre de fois de main levée, visite & discussion des élèves, satisfactions de l’école.
Ces données seront étudiées en 2 étapes : visualisation et model de classification.

1. La partie visualisation nous permet d’avoir une idée de corrélation entre les caractères (features), entre les caractères et les résultats des élève (ici, la ‘‘class’’ des élèves).

+ L (Low-level) (Niveau bas) : notes entre 0-69

+ M (Middle-Leval) (Niveau moyen) : note entre 70-89

+ H (High-Level) (Niveau élevé) : note entre 90-100

2. En deuxième partie, nous allons traiter ces données, c-a-d ‘‘preprocessing data’’, afin d’avoir une bonne entrée pour les modèles de machine learning. Les modèles choisis sont évidemment des ‘‘Classifier’’, comme DecisionTreeClassifier, RandomForestClassifier, LogisticRegression et GradientBoostingClassifier.
