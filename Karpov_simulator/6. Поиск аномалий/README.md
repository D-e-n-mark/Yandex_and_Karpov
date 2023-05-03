# Поиск аномалий
## Airflow и Telegram бот

## Задание
## Написать систему алертов для нашего приложения

Изучиd поведение метрик мы подобрали наиболее подходящий метод для детектирования аномалий. На практике как правило применяются статистические методы. 
В самом простом случае можно, например, проверять отклонение значения метрики в текущую 15-минутку от значения в такую же 15-минутку день назад. 

В случае обнаружения аномального значения, в чат отправляется алерт - сообщение со следующей информацией: метрика, ее значение, величина отклонения.

Пример работы бота:

![image](https://github.com/D-e-n-mark/Yandex_and_Karpov/blob/main/Karpov_simulator/6.%20%D0%9F%D0%BE%D0%B8%D1%81%D0%BA%20%D0%B0%D0%BD%D0%BE%D0%BC%D0%B0%D0%BB%D0%B8%D0%B9/likes_alert.png)
![image](https://github.com/D-e-n-mark/Yandex_and_Karpov/blob/main/Karpov_simulator/6.%20%D0%9F%D0%BE%D0%B8%D1%81%D0%BA%20%D0%B0%D0%BD%D0%BE%D0%BC%D0%B0%D0%BB%D0%B8%D0%B9/users_feed_alert.png)
![image](https://github.com/D-e-n-mark/Yandex_and_Karpov/blob/main/Karpov_simulator/6.%20%D0%9F%D0%BE%D0%B8%D1%81%D0%BA%20%D0%B0%D0%BD%D0%BE%D0%BC%D0%B0%D0%BB%D0%B8%D0%B9/views_alert.png)
