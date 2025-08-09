# Шаблон сайта для App Store на GitHub Pages

Этот шаблон содержит минимально необходимые страницы:
- `index.html` — главная страница приложения (может выступать **Support URL**).
- `privacy.html` — **Политика конфиденциальности** (укажите её URL в App Store Connect).
- Папка `assets/` — иконка и скриншоты.

## Как использовать
1. Переименуйте «Название приложения» и контакты в файлах `index.html` и `privacy.html`.
2. Замените ссылки и добавьте настоящие скриншоты в папку `assets/`.
3. Загрузите всё это в новый публичный репозиторий на GitHub.
4. Включите GitHub Pages: Settings → Pages → Deploy from a branch → `main` / `/root` → Save.
5. Получите URL:
   - Главная: `https://USERNAME.github.io/REPO/`
   - Политика: `https://USERNAME.github.io/REPO/privacy.html`

## Что поставить в App Store Connect
- **Support URL**: ссылка на `index.html` (главная страница, должна содержать контакт для поддержки).
- **Privacy Policy URL**: ссылка на `privacy.html`.
- **Marketing URL** (опционально): можно использовать главную страницу.

## Дата
Сгенерировано: 2025-08-09
