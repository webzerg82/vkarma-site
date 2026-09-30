# vkarma.ru — Календарь АД

Статический сайт приложения «Календарь артериального давления».

## Публикация через GitHub Pages

1. Загрузите все файлы из этой папки в корень репозитория `webzerg82/vkarma-site`.
2. В GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**.
3. Выберите ветку `main` и папку `/ (root)`, затем **Save**.
4. В разделе **Custom domain** укажите `vkarma.ru`.
5. В DNS-зоне NIC.RU добавьте записи GitHub Pages для корневого домена и `www`.
6. После выпуска сертификата включите **Enforce HTTPS**.

Файл `CNAME` уже содержит `vkarma.ru`.
