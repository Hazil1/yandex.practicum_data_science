# Классификация клиентов телеком компании

### Статус проекта
Проект завершен

### Цель проекта
Построить модель для решения задачи классификации, которая выберет подходящий тариф.

### Этапы проекта
1. Датасет разбит на обучающую, тестовую и валидационную выборки
2. Обучены модели: LogisticRegression, DecisionTreeClassifier и RandomForestClassifier
3. Проведена проверка модели на адекватность

### Результаты проекта
Наилучшая модель с результатом (accuracy_score = 0.795) для рекомендательной системы - Случайный лес со следующими гипер-параметрами:
max_depth: 9
n_estimators: 70
criterion: 'gini'
max_features: None

### Стек
`pandas` `matplotlib` `seaborn` `scipy` `sklearn`

