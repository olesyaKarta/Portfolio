# Исследование объявлений о продаже квартир

**Ход исследования**

В нашем распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.

Перед анализом понадобится обзор данных, удаление пропусков, дубликатов, обработка аномальных значений и выявление параметров, оказывающих влияние на формирование цены.

Таким образом, исследование пройдёт в три этапа:
 1. Обзор данных.
 2. Предобработка данных.
 3. Исследовательский анализ данных.
 
 **Цель исследования** — установить параметры для определения рыночной стоимости объектов недвижимости в Санкт-Петербурге и соседних населённых пунктов, найти интнресные особенности и зависимости, которые существуют на рынке недвижимости. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. 
