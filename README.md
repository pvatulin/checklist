# Двухъязычный сайт (RU/EN) без перезагрузки — GitHub Pages

Содержимое:
- `index.html` — главная страница (RU/EN переключение на месте).
- `privacy.html` — политика конфиденциальности (RU/EN переключение на месте).
- `assets/` — иконка и заглушки скриншотов.

## Использование
1. Откройте `index.html` и замените:
   - Название приложения (`data-i18n='app.title'`) — можете прописать RU/EN в блоке i18n.
   - Описание (`app.lead`), ссылки и email.
2. В `privacy.html` при необходимости измените дату и email.
3. Положите реальные скриншоты в папку `assets/` с теми же именами.

## Публикация
- Загрузите всё в публичный репозиторий GitHub.
- Включите GitHub Pages: Settings → Pages → Deploy from a branch → `main` / `/root`.
- Ссылки:
  - Landing: `https://USERNAME.github.io/REPO/index.html`
  - Privacy: `https://USERNAME.github.io/REPO/privacy.html`
