# Подсказки

Создайте переменную-счетчик для подсчёта количества загруженных скриптов.

Чтобы один скрипт не учитывался два раза (например, `onreadystatechange` запустился при `loaded` и `complete`), учитывайте его состояние в объекте `loaded`. Свойство `loaded[i] = true`  означает что `i`-й скрипт уже учтён.

# Решение
