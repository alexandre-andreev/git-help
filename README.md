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

HEAD -- это голова.
Коммит -- это всему голова.
Статусы файлов:

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "???"     --> tracked/comitted;
```

<ul type = "circle">
<li>Пункт 1</li>
<li>Пункт 2</li>
<li>Пункт 3</li>
</ul>

