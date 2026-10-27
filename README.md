# Эфир — IPTV плеер для Windows

## Получить .exe без установки инструментов (через GitHub)
1. Создайте бесплатный аккаунт на github.com и новый репозиторий (ветка main).
2. Загрузите в него всё содержимое этой папки (Add file → Upload files),
   включая скрытую папку .github.
3. Откройте вкладку Actions → "Build Windows installer" → Run workflow.
4. Через 5-10 минут откройте завершённый запуск и скачайте артефакт efir-installer.
   Внутри установщик .exe.

## Локальная сборка
Node.js, Rust, Visual Studio Build Tools (C++), затем:
npm install, npx tauri icon icon.png, npm run build
