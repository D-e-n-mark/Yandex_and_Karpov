# [Karpov Courses (Симулятор)](https://karpov.courses/simulator)
## Проекты курса симулятора аналитика данных 

### Основные инструменты и навыки, полученные в обучении:
REDASH – Выполнение SQL-запросов и визуализация.
JUPYTERHUB ON K8S – Лучший способ запуска Jupyter-ноутбуков.
SUPERSET –  BI-платформа для создания интерактивных визуализаций и дашбордов.
GITLAB – Система управления git-репозиториями, CI/CD.
AIRFLOW – библиотека, позволяющая очень легко и удобно работать с расписанием и мониторингом выполняемых задач.


| Название и ссылка | Описание задачи | Используемые инструменты и библиотеки |
| ------ | ------ | ------ |
| [Первый дашборд](https://github.com/D-e-n-mark/Yandex_and_Karpov/tree/main/Karpov_simulator/1.%20%D0%9F%D0%B5%D1%80%D0%B2%D1%8B%D0%B9%20%D0%B4%D0%B0%D1%88%D0%B1%D0%BE%D1%80%D0%B4) | Построение нескольких базовых дашбордов, которые покрывают собой ключевые аудиторные метрики и ключевые события нашего продукта. | ``Superset`` ``SQL`` |
| [Анализ продуктовых метрик](https://github.com/D-e-n-mark/Yandex_and_Karpov/tree/main/Karpov_simulator/2.%20%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%BF%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82%D0%BE%D0%B2%D1%8B%D1%85%20%D0%BC%D0%B5%D1%82%D1%80%D0%B8%D0%BA) | Исследование и визуализация различных метрик для решения поставленних задач и ответов на вопросы | ``Superset`` ``SQL`` |
| [АВ тесты](https://github.com/D-e-n-mark/Yandex_and_Karpov/tree/main/Karpov_simulator/3.%20%D0%90%D0%92%20%D1%82%D0%B5%D1%81%D1%82%D1%8B) | Проверка корректности работы системы сплитования. АА тест. Анализ результатов эксперимента. Линеаризация лайков | ``pandas`` ``seaborn`` ``matplotlib`` ``numpy`` ``hashlib`` ``stats`` ``pandahouse`` | 
| [Построение ETL пайплайна](https://github.com/D-e-n-mark/Yandex_and_Karpov/tree/main/Karpov_simulator/4.%20%D0%9F%D0%BE%D1%81%D1%82%D1%80%D0%BE%D0%B5%D0%BD%D0%B8%D0%B5%20ETL%20%D0%BF%D0%B0%D0%B9%D0%BF%D0%BB%D0%B0%D0%B9%D0%BD%D0%B0) | Дополнение новыми данными таблицы каждый день за вчерашний день | ``airflow`` ``pandas`` ``pandahouse`` |
| [Автоматизация отчетности](https://github.com/D-e-n-mark/Yandex_and_Karpov/tree/main/Karpov_simulator/5.%20%D0%90%D0%B2%D1%82%D0%BE%D0%BC%D0%B0%D0%B7%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F%20%D0%BE%D1%82%D1%87%D0%B5%D1%82%D0%BD%D0%BE%D1%81%D1%82%D0%B8) | Автоматизация отправки аналитической сводки (по ленте и приложению) в телеграм каждое утро через телеграм бота. | ``pandas`` ``pandahouse`` ``airflow`` ``telegram`` ``matplotlib`` ``seaborn`` |
| [Поиск аномалий](https://github.com/D-e-n-mark/Yandex_and_Karpov/tree/main/Karpov_simulator/6.%20%D0%9F%D0%BE%D0%B8%D1%81%D0%BA%20%D0%B0%D0%BD%D0%BE%D0%BC%D0%B0%D0%BB%D0%B8%D0%B9) | Написание системы алертов для приложения | ``telegram`` ``pandahouse`` ``airflow`` | 




