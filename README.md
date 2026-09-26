# ROSMASTER M3 PRO — документация на русском (неофициальный перевод)

Статический сайт с переводом части документации Yahboom ROSMASTER M3 PRO на русский язык.

Переведённые разделы (приоритет — настройка робота на базе Jetson Orin Nano):

- Настройка и запуск (Configuration and Operation Guide)
- Курс по лидару (Lidar Course)
- Курс по платам управления (Control Board Course — STM32 + micro-ROS)
- Jetson Orin Nano/NX (из Main Control Course)
- Курс по Linux (Linux System Course)
- Базовый курс ROS2 (ROS Basic Course)

Итого 106 уроков. Оригинал (английский, полный курс из 23 разделов):
- Репозиторий: https://github.com/YahboomTechnology/ROSMASTER-M3PRO
- Страница курса: https://www.yahboom.net/study/ROSMASTER-M3PRO

## Публикация на GitHub Pages (бесплатно)

**Вариант А — через веб-интерфейс (без git):**
1. Создайте новый **публичный** репозиторий на github.com/new (например, `rosmaster-m3pro-ru`).
2. На странице репозитория: "Add file" → "Upload files" → перетащите туда все файлы и папки из этого архива (включая `.nojekyll`, он скрытый — если браузер его не показывает, можно пропустить, но лучше включить).
3. Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, папка `/ (root)` → Save.
4. Через 1–2 минуты сайт будет доступен по адресу `https://<ваш-логин>.github.io/<имя-репозитория>/`.

**Вариант Б — через git:**
```
cd путь/к/распакованной/папке
git init
git add -A
git commit -m "Русский перевод документации ROSMASTER M3 PRO"
git branch -M main
git remote add origin https://github.com/<ваш-логин>/<имя-репозитория>.git
git push -u origin main
```
Затем включите Pages так же, как в шаге 3 варианта А.

## Примечание

Перевод выполнен с помощью Claude на основе текста, извлечённого из оригинальных PDF-файлов
репозитория Yahboom. Возможны неточности перевода — при работе с оборудованием сверяйтесь
с оригиналом. Видео и часть материалов (23 из 23 разделов курса, кроме перечисленных выше)
не переводились по объёму работы.
