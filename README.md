# YM Track Collector (Console)

A simple console script that collects tracks from **Yandex Music playlists**.

The script works with virtualized lists used on the Yandex Music website.  
Scroll the playlist, capture tracks, and export them to **TXT or CSV**.

Tool by **idaniil24**

---

# 🇬🇧 English

## Features

- Collects tracks from Yandex Music playlists
- Works with virtualized lists
- Export tracks to TXT
- Export tracks to CSV
- Simple console usage (no extensions required)

---

## How to use

1. Open a playlist on **Yandex Music**
2. Open **DevTools**

```
F12 → Console
```

3. Open the file

```
ym-track-collector.js
```

4. Copy the entire script and paste it into the Console
5. Press **Enter**
6. Scroll the playlist (you can scroll fast)
7. When finished scrolling press **Finalize capture**
8. Download the tracks as `.txt` or `.csv`

---

## Output formats

TXT

```
Artist - Title
```

CSV

```
Artist,Title,Duration
```

---

## Notes
Scroll manually: The site only loads visible tracks. Scroll slowly to the bottom.

Auto-scans: Checks the page every 300ms. No duplicates.

Reliable: Uses URLs (/track/...), not CSS classes, to survive site updates.

Done? Click "Finalize capture" at the bottom to download.

---



---

# 🇷🇺 Русская версия

## Описание

Скрипт для сбора треков из **плейлистов Яндекс Музыки** через DevTools Console.

Работает с виртуализированными списками сайта в новом дизайне (на июль 2026) и позволяет экспортировать треки в:

- TXT
- CSV

---

## Как использовать

1. Откройте плейлист в **Яндекс Музыке**
2. Откройте **DevTools**

```
F12 → Console
```

3. Откройте файл

```
ym-track-collector.js
```

4. Скопируйте весь код
5. Вставьте его в **Console**
6. Нажмите **Enter**
7. Пролистайте плейлист вниз (можно быстро)
8. После завершения нажмите **Finalize capture**
9. Скачайте список треков в `.txt` или `.csv`

---

## Форматы

TXT

```
Исполнитель - Название
```

CSV

```
Исполнитель,Название,Длительность
```

---

## Примечание

Крутите вручную: Сайт грузит только видимые треки. Медленно пролистайте список до конца.

Автосканирование: Скрипт сам собирает данные каждые 300 мс. Дубликаты исключены.

Надёжность: Ищет по ссылкам (/track/...), а не по классам, поэтому не сломается при обновлении дизайна.

Как скачать: Когда дойдёте до конца, нажмите «Finalize capture» для получения файла.
