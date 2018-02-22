### Продажа домов

|  Название           | Параметр в строке запроса | Тип данных   |
|:--------------------|:--------------------------|:------------:|
|Тип объекта | category|     `Number`   |
|Тип недвижимости |realty_type |    `Number`       |
|Тип операции | operation_type|    `Number`       |
|Область | state_id| `Number`|
|Город | city_id|`Number[]` |
|Район | district_id| `Number[]`|
|Тип стен | characteristic[149]|`Number` |
|Количество комнат |characteristic[209][from] - characteristic[209][to] | `Number[]`|
|Общая площадь |characteristic[215][from] - characteristic[215][to] |`Number[]` |
|Жилая площадь |characteristic[216][from] - characteristic[216][to] |`Number[]` |
|Кухня |characteristic[218][from] - characteristic[218][to] | `Number[]`|
|Участок |characteristic[219][from] - characteristic[219][to] | `Number[]`|
|Единица измерения площади участка |characteristic[226] | `Number[]`|
|C беседкой   |characteristic[1492] |`Number` |
|С верандой   |characteristic[1491] |`Number` |
|С подвалом  |characteristic[1490] | `Number`|
|С балконом |characteristic[1489] |`Number` |
|С камином |characteristic[1488] |`Number` |
|С садом  |characteristic[1487] | `Number`|
|С баней/сауной |characteristic[1486] |`Number` |
|С террасой |characteristic[1485] |`Number` |
|С гаражом  |characteristic[1484] | `Number`|
|С участком  |characteristic[1505] |`Number` |
|С мансардою   |characteristic[1482] |`Number` |
|С мебелью |characteristic[1480] | `Number`|
|С ремонтом |characteristic[1479] |`Number` |
|С отоплением   |characteristic[1478] | `Number`|
|Мансардный этаж |characteristic[230] | `Number`|
|Подвальный / цокольный этаж |characteristic[231] | `Number`|
|У озера **Дача** |characteristic[1494] |`Number` |
|У реки **Дача** |characteristic[1493] | `Number`|
|Жилых этажей |characteristic[229][from] - characteristic[229][to] | `Number[]`|
|Год постройки |characteristic[443] | `Number`|
|Цена |characteristic[234][from] -characteristic[234][to] |`Number[]` |
|Цена договорная |characteristic[1011]|`Number` |
|Стартовая цена |characteristic[1464] |`Number` |
|Тип валюты |characteristic[242] | `Number`|
|Возможен обмен |characteristic[265] | `Number`|
|Возможен торг | characteristic[273]| `Number`|
|Тип предложения |characteristic[1437] | `Number`|
|Возможна расстрочка/кредит |characteristic[274] |`Number` |
|Только с картой |with_map |`Number` |
|Только с видео | with_video | `Number`|
|Только с фото |with_photo |`Number` |
|Только с фото (более 3 фото)| photos_count_from|`Number` |
|Только ТОП| urgent_only| `Number`|
|Залоговое имущество | banks_only|`Number` |
|Вторичное жилье |secondary | `Number`|
|Первичное жилье | newbuildings| `Number`|
|Не показывать мои объявления | exclude_my|`Number` |
|Не показывать объявления от агентств|exclude_agencies |`Number` |
|Дата подачи |date_from - date_to |`Number` |
|Страница|page |`Number` |


### Аренда домов

|  Название           | Параметр в строке запроса | Тип данных   |
|:--------------------|:--------------------------|:------------:|
|Тип объекта | category|      `Number`  |
|Тип недвижимости |realty_type |    `Number`       |
|Тип операции | operation_type|  `Number`         |
|Область | state_id| `Number`|
|Город | city_id| `Number[]`|
|Район | district_id|`Number[]` |
|Тип стен | characteristic[149]| `Number`|
|Количество комнат |characteristic[209][from] - characteristic[209][to] |`Number[]` |
|Общая площадь |characteristic[215][from] - characteristic[215][to] |`Number[]` |
|Жилая площадь |characteristic[216][from] - characteristic[216][to] |`Number[]` |
|С балконом |characteristic[1489] |`Number` |
|С камином |characteristic[1488] | `Number`|
|С бассейном  |characteristic[1483] | `Number`|
|С баней/сауной |characteristic[1486] |`Number` |
|С гаражом  |characteristic[1484] |`Number` |
|С мебелью |characteristic[1480] | `Number`|
|С ремонтом |characteristic[1479] | `Number`|
|Мансардный этаж |characteristic[230] | `Number`|
|Подвальный / цокольный этаж |characteristic[231] | `Number`|
|Цена/месяц |characteristic[235][from] - characteristic[235][to] |`Number[]` |
|Цена договорная |characteristic[1011] |`Number` |
|Дополнительные платежи |characteristic[254] | `Number`|
|Детализация **(Аренда посуточно)** |characteristic[1399] |`Number` |
|Спальных мест от **(Аренда посуточно)** |characteristic[212][from] - characteristic[212][to] |`Number[]` |
|На день рождения **(Аренда посуточно)** |characteristic[1595] | `Number`|
|Цена/сутки  **(Аренда посуточно)** |characteristic[237][from] - characteristic[237][to] |`Number[]` |
|Цена/час  **(Аренда посуточно)** |characteristic[238][from] - characteristic[238][to] |`Number[]` |
|Цена/неделю |characteristic[279][from] - characteristic[279][to] |`Number[]` |
|Тип валюты |characteristic[246] | `Number`|
|Тип предложения |characteristic[1437] | `Number`|
|Только с картой |with_map |`Number` |
|Только с видео | with_video | `Number`|
|Только с фото |with_photo | `Number`|
|Только с фото (более 3 фото)| photos_count_from|`Number` |
|Только ТОП| urgent_only| `Number`|
|Залоговое имущество | banks_only|`Number` |
|Вторичное жилье |secondary | `Number`|
|Первичное жилье | newbuildings| `Number`|
|Не показывать мои объявления | exclude_my| `Number`|
|Не показывать объявления от агентств|exclude_agencies |`Number` |
|Дата подачи |date_from - date_to |`Number` |
|Страница|page |`Number` |
