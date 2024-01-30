# Описание проекта
Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. Постройте модель с предельно большим значением F1-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59. Проверьте F1-меру на тестовой выборке самостоятельно. Дополнительно измеряйте AUC-ROC, сравнивайте её значение с F1-мерой.

# Навыки и инструменты.

-sklearn.utils.shuffle

-sklearn.preprocessing.StandardScaler

-sklearn.linear_model.LogisticRegression

-sklearn.metrics.accuracy_score

-sklearn.metrics.f1_score

-sklearn.metrics.roc_curve

-sklearn.metrics.roc_auc_score

-matplotlib

-sklearn.metrics.confusion_matrix

-sklearn.model_selection.train_test_split

-sklearn.tree.DecisionTreeClassifier

-sklearn.ensemble.RandomForestClassifier

-sklearn.dummy.DummyClassifier

# Общие выводы
В рамках этой работы нам необходимо было построить модель,предсказывающую отток клиентов из банка на основании данных о поведении прошлых клиентов, с предельно высоким значением F1 не менее 0,59.
Лучший результат показала модель случайного леса.
