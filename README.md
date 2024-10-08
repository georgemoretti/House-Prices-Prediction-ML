# House-Prices-Prediction-ML

Этот проект посвящен решению задачи регрессии для предсказания цен на дома с использованием библиотеки Scikit-learn, а также XGBoost, CatBoost и LightGBM. Включает обработку данных, построение моделей и оценку их производительности.

## Структура проекта

- **Загрузка и анализ данных**: Используются библиотеки `pandas` и `numpy` для работы с данными, а также `seaborn` и `matplotlib` для визуализации.
- **Предобработка данных**: Заполнение пропусков, кодирование категориальных переменных и масштабирование данных с помощью инструментов из Scikit-learn.
- **Модель**: Модели для регрессии включают такие алгоритмы, как линейная регрессия, случайный лес, градиентный бустинг, а также ансамбли.
- **Оценка**: Оценка производительности моделей производится с использованием метрики `mean_squared_error` и кросс-валидации.
- **Гиперпараметры**: Для настройки моделей используется `GridSearchCV` для поиска оптимальных гиперпараметров.

## Используемые библиотеки

В проекте задействованы следующие библиотеки:

- **Pandas**: Для работы с табличными данными.
- **NumPy**: Для обработки многомерных массивов.
- **Scikit-learn**: Для предобработки данных и создания моделей.
- **Matplotlib и Seaborn**: Для визуализации данных и результатов.
- **XGBoost, CatBoost и LightGBM**: Для использования моделей бустинга.
- **Tqdm**: Для визуализации прогресса выполнения цикла обучения.

## Установка

Для запуска проекта на своей машине выполните следующие шаги:

1. Клонируйте репозиторий или загрузите проект локально.
2. Убедитесь, что у вас установлен Python 3.x.
3. Установите необходимые зависимости. Для этого выполните команду:

   ```bash
   pip install -r requirements.txt
