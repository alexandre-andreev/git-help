# Справочная информация по работе с git-help

Перечень команд

Команды | Действия
-------------:|---------------------
git init | Создание пустого локального репозитория
git clone | Создание локальной копии репозитория (init не нужна)
git remote | Связывание локально и  удаленного репозиториев
git add | Добавление в индекс
git commit | Добавление изменений
git push| Отправка изменений в GitHub

```mermaid
sequenceDiagram
    participant dotcom
    participant iframe
    participant viewscreen
    dotcom->>iframe: loads html w/ iframe url
    iframe->>viewscreen: request template
    viewscreen->>iframe: html & javascript
    iframe->>dotcom: iframe ready
    dotcom->>iframe: set mermaid data on iframe
    iframe->>iframe: render mermaid
```
