### Продажа/аренда земельных участков

|  Название           | Параметр в строке запроса | Тип данных   |
|:--------------------|:--------------------------|:------------:|
|Тип объекта | category|   `Number`     |
|Тип недвижимости |realty_type |     `Number`      |
|Тип операции | operation_type|    `Number`       |
|Область | state_id| `Number`|
|Город | city_id| `Number[]`|
|Район | district_id|`Number[]` |
|Площадь примерно от |characteristic[1424][from] - characteristic[1424][to] |`Number[]` |
|Площадь примерно до |characteristic[1465][from] - characteristic[1465][to] | `Number[]`|
|Единица измерения площади участка |characteristic[226] | `Number`|
|В коттеджном городке |characteristic[1604] | `Number`|
|Свет |characteristic[1601] |`Number` |
|Вода |characteristic[1602] | `Number`|
|Газ |characteristic[1600] | `Number`|
|Канализация |characteristic[1603] |`Number` |
|Цена |characteristic[234][from] - characteristic[234][to] |`Number[]` |
|Тип цены|characteristic[251] | `Number`|
|Цена договорная |characteristic[1011] |`Number` |
|Стартовая цена |characteristic[1464] | `Number`|
|Тип валюты |characteristic[242] |`Number` |
|Возможен обмен |characteristic[265] | `Number`|
|Возможен торг |characteristic[273] |`Number` |
|Возможна расстрочка/кредит |characteristic[274] |`Number` |
|Цена/год **Аренда** |characteristic[236][from] - characteristic[236][to] |`Number[]` |
|Предоплата **Аренда** |characteristic[1362][from] - characteristic[1362][to] | `Number[]`|
|Тип предложения |characteristic[1437] |`Number` |
|Только с картой |with_map | `Number`|
|Только с видео | with_video | `Number`|
|Только с фото |with_photo |`Number` |
|Только с фото (более 3 фото)| photos_count_from| `Number`|
|Только ТОП| urgent_only| `Number`|
|Залоговое имущество | banks_only| `Number`|
|Вторичное жилье |secondary | `Number`|
|Первичное жилье | newbuildings| `Number`|
|Не показывать мои объявления | exclude_my| `Number`|
|Не показывать объявления от агентств|exclude_agencies |`Number` |
|Дата подачи |date_from - date_to | `Number`|
|Страница|page |`Number` |
