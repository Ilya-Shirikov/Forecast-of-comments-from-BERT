# Классифицикация коментариев с BERT

Логичным этапом развития проекта является его внедрение в бизнес-концепцию. Зачастую это либо публикация в сети или обновление действующего приложения и передача новых возможностей пользователям. Грамотное внедрение позволяет безболезненно и быстро включить новый функционал в бизнес-процессы и получать выгоду с первого дня использования.

В нашем случае интернет-магазин  дает новые возможностей пользователям, происходит запуск новых сервисов. Теперь пользователи могут редактировать и дополнять описания товаров. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. 

## **Цели:**

Построить модель которая умеет классифицировать комментарии на позитивные и негативные. В нашем распоряжении набор данных с разметкой о токсичности правок


## **Метрики:**

Значение метрики качества F1 должно быть не меньше 0.75.

## **Основные шаги**

- Загрузить данные
- Проанализировать данные.
- Обучить разные модели с различными гиперпараметрами.
- Проверить данные на тестовой выборке.
- Сделать общий вывод.


## **Используемые данные:**

Данные находятся в файле /datasets/toxic_comments.csv или https://code.s3.yandex.net/datasets/toxic_comments.csv

Столбец text в нём содержит текст комментария, а toxic — целевой признак.

### **Прогнозирование коментариев имеет широкий спектр областей применения и может быть полезным во многих сценариях.**

Сегодня социальные сети превратились в одну из главных коммуникационных платформ как в онлайне, так и реальной жизни. Свобода выражения разных точек зрения, в том числе токсичных, агрессивных и оскорбительных комментариев может иметь долговременные негативные последствия для мнений людей и социальной сплочённости. Поэтому одной из важнейших задач современного общества является разработка средств автоматического определения токсичной информации в интернете для уменьшения негативных последствий.

Наше решение использует машинное обучение, инструменты обработки естественного языка для предварительной обработки данных и подходы глубокого обучения, которые использовались для обучения модели, которая могла бы определять токсичность комментариев.

Существующие подходы реализуются с использованием простой долгосрочной краткосрочной памяти, логистической регрессии и некоторых моделей на основе Берта.
