[14]: https://github.com/ponandrew100/y_praktikum/blob/master/final_project/final_project.ipynb  


[final_project.ipynb][14]  

Проект об исследовании оттока клиентов оператора связи.  

Цель: Построить модель, которая спрогнозирует категорию клиентов, которые могут покинуть оператора связи, чтобы им вовремя предлагать промокоды и специальные условия.  
Результат: Выполнены предобработка и анализ данных. Построены множество моделей (LogisticRegression, DecisionTreeClassifier, RandomForestClassifier, AdaBoostClassifier, BaggingClassifier) с различными параметрами с использованием пайплайн и гридсерч, а также с учетом борьбы с дисбалансом классов. Лучшая модель выбиралась по метрике AUC_ROC. 

Применялись: pandas, numpy, seaborn, accuracy_score, roc_auc_score, Pipeline, GridSearchCV, LogisticRegression, DecisionTreeClassifier, RandomForestClassifier, AdaBoostClassifier, BaggingClassifier.
