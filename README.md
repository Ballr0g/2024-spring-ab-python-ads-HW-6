# 2024-spring-ab-python-ads-HW-6 - Sagalov Daniil

Реализовать дэшборд на Streamlit с обучением uplift модели и EDA на датасете X5. Для имитации обновления данных реализовать случайный выбор 80% датасета train. В дэшборде реализовать возможность выбора из подходов Solo Model и Two Model и классификаторов CatBoostClassifier и RandomForestClassifier (аналогично семинару). С помощью DockerOperator реализовать ежедневное дообучение модели в Airflow.

**Критерии**:
1. Реализован дэшборд с необходимым функционалом - +3 балла
1. Реализован Dockerfile для дэшборда - +1 балл
2. Выполнен запуск и конфигурация Airflow в kind (приложить скрины Airflow webserver) - +4 балла
3. Реализован ежедневный запуск с помощью DockerOperator - +2 балла
