
## git log
```
git log
```
Команда git log позволяет просмотреть историю коммитов в репозитории.

По умолчанию (без аргументов) git log перечисляет коммиты, сделанные в репозитории, в обратном к хронологическому порядку — последние коммиты находятся вверху.

Команда git log имеет большое количество опций для поиска коммитов по разным критериям. Вот некоторые из них:

-p или --patch — показывает разницу (выводит патч), внесённую в каждый коммит;

--stat — показывает статистику изменённых файлов для каждого коммита;

--shortstat — отображает только строку с количеством изменений/вставок/удалений для команды --stat;

--name-only — показывает список изменённых файлов после информации о коммите;

--name-status — показывает список файлов, которые добавлены/изменены/удалены.






```mermaid
graph LR;
untracked;
  untracked -- "git add" --> staged;
  staged -- "git commit"    --> tracked/comitted;
  modified -- "git add" --> staged;
```
