# Tailwind HTML Starter

Простой стартовый шаблон для разработки HTML с Tailwind CSS (локальная сборка через PostCSS).

Как использовать (PowerShell):

1. Установить зависимости:

```powershell
npm install
```

2. Построить CSS один раз:

```powershell
npm run build
```

3. Или следить за изменениями во время разработки:

```powershell
npm run watch:css
```

Откройте `index.html` в браузере (локально) — он подключает `dist/output.css`.

Если предпочитаете CDN-версию Tailwind (без сборки), скажите — я заменю index.html на CDN-версию.
