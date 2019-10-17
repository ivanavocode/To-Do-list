

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