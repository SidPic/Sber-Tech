# Sber-Tech
calendar optimization

Извиняюсь, UI не успел сделать.
  - Файл загружается в коде (блок "Подготовка XML") (data = ET.parse("проверочное задание.xml"))
  - Параметры оптимизации задаются как параметры функции optimize (блок "Main")
    -- по умолчанию, автоматически, происходит оптимизация по длительности
    -- max_employees отвечает за ориентировочное ограничение по количеству используемых ресурсов (по умолчанию - не ограничено)
    -- max_cost отвечает за ориентировочное ограничение максимально стоимости (по умолчанию - не ограничена)
    -- можно указать и max_employees и max_cost, тогда будут учитываться оба ограничения
  - Файл записывается там же в блоке "Main" (data.write(...))
