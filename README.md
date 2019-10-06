## Общее описание

Этот репозиторий содержит примеры работы с пакетом `prophet` для R, который предназначен для прогнозирования временных рядов. Подробное описание примеров приведено в серии статей блога "[R: Анализ и визуализация данных](https://r-analytics.blogspot.com)":

1. [Введение](https://r-analytics.blogspot.com/2019/08/prophet.html)
2. [Параметры моделей](https://r-analytics.blogspot.com/2019/09/prophet.html)
3. [Эффекты праздников](https://r-analytics.blogspot.com/2019/09/prophet_13.html)
4. [Сезонные компоненты](https://r-analytics.blogspot.com/2019/09/prophet-seasonality.html)
5. [Дополнительные предикторы](https://r-analytics.blogspot.com/2019/10/prophet-predictors.html)


## Структура проекта

Директория `scripts` содержит два скрипта:

* `data_scraping.R`: набор команд, использованных для сбора данных по стоимости
биткоина с сайта CoinMarketCap (эти данные хранятся в виде CSV файла в
директории `data`);
* `models.R`: код для построения нескольких предсказательных моделей
для стоимости биткоина.

В директории `models` хранится объект `models.RData` со всеми моделями,
построенными с помощью скрипта `models.R`.
