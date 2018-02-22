### Продажа/аренда коммерческой недвижимости

|  Название           | Параметр в строке запроса | Тип данных   |
|:--------------------|:--------------------------|:------------:|
|Тип объекта | category|  `Number`      |
|Тип недвижимости |realty_type |     `Number`      |
|Тип операции | operation_type|   `Number`        |
|Область | state_id|`Number` |
|Город | city_id|`Number[]` |
|Район | district_id| `Number[]`|
|Количество помещений |characteristic[210][from] - characteristic[210][to] |`Number[]` |
|Тип объекта-торговые площади |characteristic[169] | `Number`|
|Общая |characteristic[214][from] - characteristic[214][to] | `Number[]`|
|Полезная |characteristic[217][from] - characteristic[217][to] | `Number[]`|
|Этаж |characteristic[227][from] - characteristic[227][to] |`Number[]` |
|Этажность |characteristic[228][from] - characteristic[228][to] | `Number[]`|
|Участок |characteristic[219][from] - characteristic[219][to] |`Number[]` |
|Единица измерения площади участка |characteristic[226] | `Number`|
|Сфера **Готовый бизнес** |characteristic[199] | `Number`|
|Тип объекта-складские помещени |characteristic[159] | `Number`|
|Тип объекта-производственные помещения |characteristic[162] |`Number` |
|Действующий бизнес |characteristic[1438] | `Number`|
|Цена |characteristic[235][from] - characteristic[235][to] |`Number[]` |
|Цена/месяц **Аренда**|characteristic[235][from] - characteristic[235][to] |`Number[]` |
|Дополнительные платежи **Аренда** |characteristic[254] |`Number` |
|Цена договорная |characteristic[1011] |`Number` |
|Стартовая цена |characteristic[1464] |`Number` |
|Тип валюты |characteristic[242] |`Number` |
|Возможен обмен |characteristic[265] | `Number`|
|Возможен торг |characteristic[273] | `Number`|
|Возможна расстрочка/кредит |characteristic[274] | `Number`|
|Цена за (объект / квадратный метр) |characteristic[247] |`Number` |
|Тип предложения |characteristic[1437] |`Number` |
|Только с картой |with_map | `Number`|
|Только с видео | with_video | `Number`|
|Только с фото |with_photo | `Number`|
|Только с фото (более 3 фото)| photos_count_from| `Number`|
|Только ТОП| urgent_only| `Number`|
|Залоговое имущество | banks_only| `Number`|
|Вторичное жилье |secondary | `Number`|
|Первичное жилье | newbuildings| `Number`|
|Не показывать мои объявления | exclude_my| `Number`|
|Не показывать объявления от агентств|exclude_agencies |`Number` |
|Дата подачи |date_from - date_to | `Number`|
|Страница|page |`Number` |
