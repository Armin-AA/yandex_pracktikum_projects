

Описание проекта:

Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.

Цель: 
ROC_AUC >= 0.85;

Вывод: 
Обучены модели CatBoostClassifier и LGBMClassifier.
Получены  у модели 
CatBoostClassifier:
ROC_AUC = 0,922, Accuracy = 0,88;

LGBMClassifier:
ROC_AUC = 0,906, Accuracy = 0,83

метрики у модели CatBoostClassifier ROC_AUC и Accuracy больше LGBMClassifier;

Стек технологий: Pandas, Seaborn, Sklearn, Matplotlib, Phik, LightGBM, CatBoost

Статус проекта: Завершен. 


