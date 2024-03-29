 ## Прогнозирование оттока клиентов сети фитнес-центров


**Задача**   


На основе данных о посетителях сети фитнес-центров за предыдущий до проверки факта оттока месяц и информации журнала посещений и покупок спрогнозировать вероятность оттока, сформировать портреты пользователей и подготовить план действий по удержанию клиентов.


**Описание проекта**


В проекте использовано машинное обучение. Определена модель для предсказания оттока (модель логистической регрессии). 
Сформированы типичные портреты лояльных клиентов и склонных к оттоку:

-Потенциально уходящие в отток: короткий период контракта - и не возвращаются (1 месяц), крайне низкая частота посещения (максимум раз в неделю), самый молодой возраст (18-26 лет), минимально низкие затраты на дополнительные услуги фитнес-центра.

-Лояльные клиенты: Высокая частота и длительный срок посещений (абонент на длительный срок, продление на следующий период), пришедшие от компаний партнеров, средний возраст 30 лет.


Рекомендации: 1. Критическим периодом для принятия решения является окончание срока действия первого абонемента сроком на 1 месяц. Для удержания этой категории клиентов рекомендована организация акций со скидкой при продлении месячного абонемента, особенно на долгосрочной основе, а также абонементы без ограничения количества посещений в неделю (помним про высокую частоту посещений в лояльных группах). 2. Организация привлечения клиентов из числа партнеров финтес-центра, которые также дают хорошее удержание (длительный срок контракта).


**Навыки и инструменты**  


Python, Pandas, Matplotlib, Seaborn, Plotly, Datetime, Math, Scikit-learn (train_test_split, LogisticRegression, RandomForestClassifier, StandardScaler, KMeans), SciPy (dendrogram)


 Машинное обучение, классификация, матрица корреляции, матрица расстояний, кластеризация, визуализация данных


**Статус проекта:** завершен