# Yandex.Tanker
Это небольшая bash утилита которая поможет вам легко и просто создавать и запускать нагрузочное тестирование с нагрузкой до 500 000 RPS.

Yandex.Tank: overload.yandex.net
___
## Требования
- docker
___
## Использование
- Дайте права на запуск `chmod +x yaTanker`
- Запустите `./yaTanker run` и следуйте инструкциям.

Для изменения настроек тестируемого проекта вы можете:
- А) Настроить файл **load.yaml** в ./Tank (ее создаст скрипт)

или

- Б) Пересоздать все выполнив `./yaTanker clear` и `./yaTanker run`
