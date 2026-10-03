# РостОк: страница отчёта для родителей

Статическая страница из `report-page/` основного репозитория.

- prod: `https://daniilgrebnev.github.io/rostok-report/?t=<токен>` (корень, `config.js` prod-проекта)
- dev: `https://daniilgrebnev.github.io/rostok-report/dev/?t=<токен>` (`dev/config.js` dev-проекта)

Пока prod-проекта нет, корень тоже смотрит в dev.

`config.js` содержит только адрес проекта Supabase и публичный ключ (publishable): он
предназначен для браузера, данные защищены RLS, отчёт отдаётся только по токену.
