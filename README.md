1. В состав данного проекта входят python-скрипты, json и csv файлы с датасетами в корневой папке проекта, а также pkl файлы с моделями машинного обучения в папке linear_ML_models
2. Файл drom parser.py содержит код парсера данных об автомобилях с сайта drom.ru. В проекте использовались данные об автомобиле Toyota Prius 30 рестайлинг, продающихся в городах Хабаровск, Владивосток и Благовещенск
3. Данные об автомобилях, а именно цена, пробег, год выпуска и город продажи хранятся в соответствующих json файлах для каждого из трех городов
4. Файл labeler.py содержит код, необходимый для объединения json файлов и разметки данных. С помощью библиотеки pandas данные преобразуются в датафрейм и конвертируются в формат csv
5. Файл linear_regression.py содержит код для создания и обучения моделей линейной регрессии с одним признаком (пробег авто) и с несколькими признаками (пробег авто и город продажи), а также их сохранения в папку linear_ML_models в формате pkl для дальнейшего использования в сторонних проектах
6. Протестировать работу представленных в проекте моделей машинного обучения можно с помощью Telegram бота @Drom_helper_bot
