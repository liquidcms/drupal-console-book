# create:vocabularies
Создание фиктивных словарей для Drupal 8.

**Использование:**
```
drupal create:vocabularies [options]
crv
```

## Доступные параметры
Команда | Детали
-------|-------------
--limit | Сколько словарей вы хотите создать
--name-words | Максимальное количество слов в именах словарей

## Примеры
* Предоставляет количество словарей, которые будут созданы с максимальным количеством слов в именах
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
