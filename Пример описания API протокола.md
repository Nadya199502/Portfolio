## Пример описания API протокола
**Описание**
Ресурс: https://cataas.com
В описании документа использованы открытые  API.
**Формат**
GET /api/cats?tags

**Параметры запроса**
Filter fields: сute, gray, fluffy, british shorthai,big-eyes

- cute – фильтр по названию тега, в результате поиска  по тегу будут показаны картинки с меткой cute
- gray – фильтр по названию тега, в результате поиска  по тегу будут показаны картинки с меткой gray 
- fluffy – фильтр по названию тега, в результате поиска  по тегу будут показаны картинки с меткой fluffy 
- british shorthai – фильтр по названию тега, в результате поиска  по тегу будут показаны картинки с меткой british shorthai 
- big-eyes – фильтр по названию тега, в результате поиска  по тегу будут показаны картинки с меткой big-eyes 

**Описание полей**

| ID | Type | Description |
| ------ | ------ | ------ |
| id| String | Идентификатор поискового результата
| created_at | String |Адрес создания картинки
| tags| String |Ключевые слова, по которым осуществляется поиск по картинкам 

**Пример запроса**
GET /api/cats?tags=gray

**Пример ответа**
{3 entries
    id: "5a788a9330d75654d09430d1",
    created_at: "2018-02-05T16:47:15.411Z",
    tags: [3 elements
    "cut",
"gray",
"eyes"
]
},
{3 entries
    id: "5bd84fd1cfff09000f685f4a",
    created_at: "2018-10-30T12:34:25.122Z",
    tags: [3 elements
"fluffy",
"cute",
"gray"
]
},
{3 entries
    id: "5d122ab6a306d80012cc4051",
    created_at: "2019-06-25T14:07:50.533Z",
    tags: [4 elements
"young",
"resting",
"sleeping",
"gray"
]
},
{3 entries
    id: "5de95dd1be069d00117c2cb2",
    created_at: "2019-12-05T19:43:12.940Z",
    tags: [
"jellybean toes toe beans grey gray mauve"
]
