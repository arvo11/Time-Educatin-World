# Университетский агрегатор (онлайн, статический)
Готовый статический сайт (index.html + data.json). Деплой за 2–3 минуты.

## GitHub Pages (бесплатно)
1. Создай репозиторий `univ-site` (Public) на github.com.
2. Залей туда **index.html** и **data.json** (из этого архива).
3. В репозитории: **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
4. Branch: `main`, Folder: `/root` → Save.
5. Через минуту сайт будет доступен по адресу `https://ВАШЕ_ИМЯ.github.io/univ-site/`.

## Netlify (быстрый способ)
1. Перейди на https://app.netlify.com/drop
2. Перетащи файлы **index.html** и **data.json**.
3. Получи ссылку мгновенно.

## Обновление данных
- Меняй содержимое **data.json** — сайт подхватит свежие данные при обновлении страницы.
- Для автообновления (API/парсинг) нужен отдельный серверный скрипт и CRON — можно добавить позже.

## Поля data.json
- name — название университета
- country — Germany | Italy | Poland
- city — город
- focus — Technical | Medical
- type — Public | Private
- link — официальный сайт
- note — примечание
