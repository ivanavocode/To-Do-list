

TODO LIST
================

Установка
----------
Установить зависимости из package.json(..\project\package.json) cmd --> npm i

```sh
Комманды  npm run...
    start, --запуск проекта
    build, -- сборка
```

  - __components__
    - __app__
      - [app.js]
    - __app-header__
      - [app-header.js]
    - __item-add-from__
      - [item-add-form.js]
    - __item-status-filter__
      - [item-status-filter.js]
    - __search-panel__
      - [search-panel.js]
    - __todo-list__
      - [todo-list.js]
    - __todo-list-item__
      - [todo-list-item.js]
  - [index.js]


├── src
|  ├── components                   #
|  |  ├── app
|  |  |  ├── app.js                 # основной компонент, содержит основную логику приложения
|  |  ├── app-header
|  |  |  ├── app-header.js          # отображает заголовок и статус дел(активно,закончено)
|  |  ├── item-add-from
|  |  |  └── item-add-form.js       # компонент содержит форму для создания новой задачи
|  |  ├── item-status-filter
|  |  |  └── item-status-filter.js  # производит сортировку по выбранному критерию(all, active, done)
|  |  ├── search-panel
|  |  |  └── search-panel.js        # панель поиска задачи
|  |  ├── todo-list
|  |  |  └── todo-list.js           # отображает список дел
|  |  └── todo-list-item
|  |     └── todo-list-item.js      # child component todo-list создает  элемент списка
|  └── index.js

