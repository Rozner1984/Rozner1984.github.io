# auto sport

Циферблат для Amazfit Balance 2 (Zepp OS), создан в редакторе AmazFace.

![Часы с циферблатом и QR-кодом для установки](auto_sport-watch-qr.png)

## Превью циферблата

| Дневной · основной | Ночной | AOD |
| :--: | :--: | :--: |
| ![Дневной · основной](auto_sport-watch.png) | ![Ночной](auto_sport-night.png) | ![AOD](auto_sport-aod.png) |

## Зоны нажатия

Номера на циферблате соответствуют списку справа: там указано, что открывается по нажатию.

![Зоны нажатия](auto_sport-tap-zones.png)

- **Версия:** 1.0.0
- **Опубликовано:** 2026-11-23T06:37:00.744Z
- **Установочный пакет:** [auto_sport.zpk](https://raw.githubusercontent.com/Rozner1984/Rozner1984.github.io/main/watchfaces/Balance2/auto_sport/auto_sport.zpk)
- **Ссылка для QR (zpkd1://):** `zpkd1://raw.githubusercontent.com/Rozner1984/Rozner1984.github.io/main/watchfaces/Balance2/auto_sport/auto_sport.zpk`

## Установка

1. Включите режим разработчика в Zepp App: Профиль → Настройки → О программе → семь раз нажмите на значок Zepp.
2. Профиль → ваши часы → «Режим разработчика» → «Сканировать» (часы должны быть подключены).
3. Отсканируйте QR-код циферблата. Ссылка на пакет постоянная: при обновлении циферблата тот же QR ставит актуальную версию (GitHub CDN может отдавать прежнюю версию до 5 минут).

## Файлы

- `auto_sport.zpk` — установочный пакет
- `device.zip` — содержимое для устройства (то же, что внутри пакета)
- `project.zip` — полный проект Zepp OS
- `auto_sport-watch.png` — дневной, основной циферблат в полном качестве
- `auto_sport-night.png` — ночной циферблат в полном качестве
- `auto_sport-aod.png` — превью AOD в полном качестве
- `auto_sport-watch-200.png` — уменьшенный дневной мокап высотой 200 px
- `auto_sport-watch-qr.png` — мокап часов с циферблатом и QR-кодом
- `auto_sport-tap-zones.png` — карта зон нажатия: что открывается по тапу
- `auto_sport.watchface.json` — исходник циферблата для редактора AmazFace («Открыть»)
- `amazface-publish.json` — служебный файл AmazFace: защищает папку от случайной перезаписи другим проектом
