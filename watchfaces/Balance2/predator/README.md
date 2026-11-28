# predator

Циферблат для Amazfit Balance 2 (Zepp OS), создан в редакторе AmazFace.

![Анимация циферблата](predator-watch.gif)

![Часы с циферблатом и QR-кодом для установки](predator-watch-qr.png)

## Превью циферблата

| Дневной · основной | AOD |
| :--: | :--: |
| ![Дневной · основной](predator-watch.png) | ![AOD](predator-aod.png) |

## Зоны нажатия

Номера на циферблате соответствуют списку справа: там указано, что открывается по нажатию.

![Зоны нажатия](predator-tap-zones.png)

- **Версия:** 1.0.0
- **Опубликовано:** 2026-11-28T17:36:23.440Z
- **Установочный пакет:** [predator.zpk](https://raw.githubusercontent.com/Rozner1984/Rozner1984.github.io/main/watchfaces/Balance2/predator/predator.zpk)
- **Ссылка для QR (zpkd1://):** `zpkd1://raw.githubusercontent.com/Rozner1984/Rozner1984.github.io/main/watchfaces/Balance2/predator/predator.zpk`

## Установка

1. Включите режим разработчика в Zepp App: Профиль → Настройки → О программе → семь раз нажмите на значок Zepp.
2. Профиль → ваши часы → «Режим разработчика» → «Сканировать» (часы должны быть подключены).
3. Отсканируйте QR-код циферблата. Ссылка на пакет постоянная: при обновлении циферблата тот же QR ставит актуальную версию (GitHub CDN может отдавать прежнюю версию до 5 минут).

## Файлы

- `predator.zpk` — установочный пакет
- `device.zip` — содержимое для устройства (то же, что внутри пакета)
- `project.zip` — полный проект Zepp OS
- `predator-watch.png` — дневной, основной циферблат в полном качестве
- `predator-aod.png` — превью AOD в полном качестве
- `predator-watch-200.png` — уменьшенный дневной мокап высотой 200 px
- `predator-watch-qr.png` — мокап часов с циферблатом и QR-кодом
- `predator-tap-zones.png` — карта зон нажатия: что открывается по тапу
- `predator-watch.gif` — анимированное превью циферблата (GIF)
- `predator.watchface.json` — исходник циферблата для редактора AmazFace («Открыть»)
- `amazface-publish.json` — служебный файл AmazFace: защищает папку от случайной перезаписи другим проектом
