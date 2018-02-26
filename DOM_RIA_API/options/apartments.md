### Продажа квартир/комнат
<!--table-->
|  Название           | Параметр в строке запроса | Тип данных   |
|:--------------------|:--------------------------|:------------:|
|Тип объекта | category|   `Number`      |
|Тип недвижимости |realty_type |    `Number`        |
|Тип операции | operation_type|     `Number`       |
|Область | state_id| `Number` |
|Город | city_id| `Number[]` |
|Район | district_id|`Number[]`  |
|Тип стен| characteristic[118] |`Number[]`  |
|Количество комнат |characteristic[209][from] - characteristic[209][to] | `Number[]` |
|Общая площадь |characteristic[214][from] - characteristic[214][to] |`Number[]`  |
|Жилая площадь |characteristic[216][from] - characteristic[216][to] |`Number[]`  |
|Кухня |characteristic[218][from] - characteristic[218][to] |`Number[]`  |
|Этаж |characteristic[227][from] - characteristic[227][to] | `Number[]` |
|Этажность |characteristic[228][from] - characteristic[228][to] | `Number[]` |
|Кухня студия |characteristic[1501] | `Number` |
|Пентхаус |characteristic[1504] |`Number` |
|Многоуровневая|characteristic[1502] |`Number` |
|С мансардой |characteristic[1503] |`Number` |
|Год постройки |characteristic[443] |`Number` |
|Коммунальные платежи в зимний период |characteristic[1607][from] - characteristic[1607][to] |`Number[]` |
|Коммунальные платежи в летний период |characteristic[1608][from] - characteristic[1608][to] | `Number[]`|
|Цена |characteristic[234][from] - characteristic[234][to] | `Number[]`|
|Цена за (объект / квадратный метр) |characteristic[247] |`Number` |
|Цена договорная |characteristic[1011] |`Number` |
|Стартовая цена |characteristic[1464] |`Number` |
|Тип валюты |characteristic[246] |`Number` |
|Возможен обмен |characteristic[265] | `Number`|
|Возможен торг |characteristic[273] | `Number`|
|Тип предложения |characteristic[1437] |`Number` |
|Возможна расстрочка/кредит |characteristic[274] | `Number`|
|Только с картой |with_map |`Number` |
|Только с видео | with_video |`Number` |
|Только с фото |with_photo |`Number` |
|Только с фото (более 3 фото)| photos_count_from| `Number`|
|Только ТОП| urgent_only|`Number` |
|Залоговое имущество | banks_only|`Number` |
|Вторичное жилье |secondary |`Number` |
|Первичное жилье | newbuildings| `Number`|
|Не показывать мои объявления | exclude_my| `Number`|
|Не показывать объявления от агентств|exclude_agencies |`Number` |
|Дата подачи |date_from - date_to |`Number` |
|Страница|page | |
<!--endtable-->
### Аренда квартир/комнат

|  Название           | Параметр в строке запроса | Тип данных   |
|:--------------------|:--------------------------|:------------:|
|Тип объекта | category|    `Number`    |
|Тип недвижимости |realty_type |    `Number`       |
|Тип операции | operation_type|    `Number`       |
|Область | state_id|`Number` |
|Город | city_id|`Number[]` |
|Район | district_id|`Number[]` |
|Тип стен| characteristic[118] | `Number[]`|
|Количество комнат |characteristic[209][from] - characteristic[209][to] |`Number[]` |
|Общая площадь |characteristic[214][from] - characteristic[214][to] |`Number[]` |
|Жилая площадь |characteristic[216][from] - characteristic[216][to] |`Number[]` |
|Кухня |characteristic[218][from] - characteristic[218][to] |`Number[]` |
|Этаж |characteristic[227][from] - characteristic[227][to] | `Number[]`|
|Этажность |characteristic[228][from] - characteristic[228][to] |`Number[]` |
|С джакузи| characteristic[1481]|`Number` |
|С отоплением| characteristic[1478]|`Number` |
|С мебелью |characteristic[1480] |`Number` |
|С ремонтом |characteristic[1479] | `Number`|
|Дополнительные платежи |characteristic[254] |`Number` |
|С подсилением |characteristic[1500] |`Number` |
|Совместная аренда |characteristic[1596] |`Number` |
|Коммунальные платежи в зимний период |characteristic[1609][from] - characteristic[1609][to] | `Number[]`|
|Коммунальные платежи в летний период |characteristic[1610][from] - characteristic[1610][to] | `Number[]`|
|Цена/месяц |characteristic[235][from] - characteristic[235][to] | `Number[]`|
|Цена договорная |characteristic[1011] | `Number`|
|Детализация **(Аренда посуточно)** |characteristic[1399] |`Number` |
|Кухня студия **(Аренда посуточно)**|characteristic[1501] |`Number` |
|На выходные **(Аренда посуточно)** |characteristic[1477] | `Number`|
|На празники **(Аренда посуточно)** |characteristic[1498] | `Number`|
|На новый год **(Аренда посуточно)** |characteristic[1499] |`Number` |
|Цена/сутки  **(Аренда посуточно)** |characteristic[237][from] - characteristic[237][to] | `Number[]`|
|Цена/час  **(Аренда посуточно)** |characteristic[238][from] - characteristic[238][to] |`Number[]` |
|Цена/неделю |characteristic[279][from] - characteristic[279][to] |`Number[]` |
|Тип валюты |characteristic[246] | `Number`|
|Тип предложения |characteristic[1437] | `Number`|
|Только с картой |with_map |`Number` |
|Только с видео | with_video | `Number`|
|Только с фото |with_photo | `Number`|
|Только с фото (более 3 фото)| photos_count_from|`Number` |
|Только ТОП| urgent_only|`Number` |
|Залоговое имущество | banks_only| `Number`|
|Вторичное жилье |secondary | `Number`|
|Первичное жилье | newbuildings| `Number`|
|Не показывать мои объявления | exclude_my| `Number`|
|Не показывать объявления от агентств|exclude_agencies |`Number` |
|Дата подачи |date_from - date_to |`Number` |
|Страница|page |`Number` |
