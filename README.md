# MovieNote Web

Закладочная страница для просмотра библиотеки MovieNote в браузере.
Загружается с GitHub Pages, но работает целиком в браузере пользователя:
вход через Google, чтение `movienote-library.json` с Google Drive (scope `drive.readonly`).

## Настройка (один раз)
1. Google Cloud Console → APIs & Services → Credentials → **Create OAuth client ID → Web application**.
2. Authorized JavaScript origins: `https://aldrd.github.io` (и `http://localhost:8000` для локальных тестов).
3. Откройте страницу — она попросит Client ID, сохранит его в localStorage браузера.
4. В OAuth consent screen добавьте свой аккаунт в Test users (режим Testing).

Синхронизация файла: приложение на телефоне (кнопка «Синхр.») — Google Drive — эта страница («Обновить»).
