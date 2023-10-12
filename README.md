Uplift.ipynb
# 2Y_ML_22_uplift
учебный проект: сравнение моделей по оптимальности применительно к датасету Criteo Uplift Prediction Dataset (https://ailab.criteo.com/criteo-uplift-prediction-dataset/)

опробованные модели:
базовый S-learner,X-learner показали плохие результаты;

T-learner,R-learner,UpliftTreeClassifier,UpliftRandomForestClassifier  показали плохие результаты;

реализован поиск по сетке для модели causalml.inference.tree.UpliftTreeClassifier, 
сложность в "несовместимости" данной модели с sklearn.model_selection.GridSearchCV
 
