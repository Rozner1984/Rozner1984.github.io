# hyk pusher

Циферблат для Amazfit Balance 2 (Zepp OS), создан в редакторе AmazFace.

![Часы с циферблатом и QR-кодом для установки](hyk_pusher-watch-qr.png)

## Превью циферблата

| Дневной · основной | AOD |
| :--: | :--: |
| ![Дневной · основной](hyk_pusher-watch.png) | ![AOD](hyk_pusher-aod.png) |

## Зоны нажатия

Номера на циферблате соответствуют списку справа: там указано, что открывается по нажатию.

![Зоны нажатия](hyk_pusher-tap-zones.png)

- **Версия:** 1.0.0
- **Опубликовано:** 2026-11-19T23:39:05.114Z
- **Установочный пакет:** [hyk_pusher.zpk](https://raw.githubusercontent.com/Rozner1984/Rozner1984.github.io/main/watchfaces/Balance2/hyk_pusher/hyk_pusher.zpk)
- **Ссылка для QR (zpkd1://):** `zpkd1://raw.githubusercontent.com/Rozner1984/Rozner1984.github.io/main/watchfaces/Balance2/hyk_pusher/hyk_pusher.zpk`

## Установка

1. Включите режим разработчика в Zepp App: Профиль → Настройки → О программе → семь раз нажмите на значок Zepp.
2. Профиль → ваши часы → «Режим разработчика» → «Сканировать» (часы должны быть подключены).
3. Отсканируйте QR-код циферблата. Ссылка на пакет постоянная: при обновлении циферблата тот же QR ставит актуальную версию (GitHub CDN может отдавать прежнюю версию до 5 минут).

## Файлы

- `hyk_pusher.zpk` — установочный пакет
- `device.zip` — содержимое для устройства (то же, что внутри пакета)
- `project.zip` — полный проект Zepp OS
- `hyk_pusher-watch.png` — дневной, основной циферблат в полном качестве
- `hyk_pusher-aod.png` — превью AOD в полном качестве
- `hyk_pusher-watch-200.png` — уменьшенный дневной мокап высотой 200 px
- `hyk_pusher-watch-qr.png` — мокап часов с циферблатом и QR-кодом
- `hyk_pusher-tap-zones.png` — карта зон нажатия: что открывается по тапу
- `hyk_pusher.watchface.json` — исходник циферблата для редактора AmazFace («Открыть»)
- `amazface-publish.json` — служебный файл AmazFace: защищает папку от случайной перезаписи другим проектом
