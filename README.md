# Арсений Просветов

**Frontend / Fullstack Engineer · Vue 3 / TypeScript / Node.js · аналитические и геоинформационные системы**

[Резюме](https://resume-proars.vercel.app) · [Telegram](https://t.me/ProArS) · [Email](mailto:arsprosvet@mail.ru) · Москва

Разрабатываю аналитические веб-приложения: интерактивные карты, дашборды и интерфейсы для работы с большими объёмами данных. Более 3 лет коммерческого опыта; официальный переход в IT — с января 2024 года. Сейчас — ведущий программист в Институте Генплана Москвы.

## Чем занимаюсь

- Проектирую SPA на Vue 3 и TypeScript: компоненты, состояние, API-контракты и асинхронные сценарии.
- Разделяю внешние DTO, доменные модели и представление; валидирую данные на границах системы.
- Разрабатываю геоинтерфейсы на MapLibre GL и OpenLayers, работаю с GeoJSON, WMS/WFS и GeoServer.
- Веду задачи до backend и данных: Node.js, NestJS/Express, PostgreSQL/PostGIS, WebSocket и CI/CD.

## Ключевые коммерческие проекты

### Geoanalyst

Геоаналитическая платформа с поиском объектов, 22 пространственными слоями и тремя режимами анализа территории.

- Vue 3, TypeScript и MapLibre GL на frontend; NestJS, PostgreSQL/PostGIS и Zod на backend.
- Загрузка данных по видимой области карты, облегчённые DTO и отмена устаревших запросов.
- Подключение новых слоёв через общий конфиг; контракты и расчёты защищены тестами.

### Moscow Strategy Dashboard

Интерактивный дашборд стратегии Москвы до 2050 года с картой районов и 10 показателями.

- Поток данных REST API → runtime-валидация → domain/view model.
- Картограммы OpenLayers, интерактивная легенда, сравнение периодов и обработка неполных данных.
- Express API, PostgreSQL/PostGIS, unit-тесты и автоматический деплой.

### ГлавАПУ Stat

Внутренний сервис, объединяющий выбор территории, пространственные расчёты, дашборды и Excel-отчёты.

- Vue 3, TypeScript и OpenLayers: выбор районов, рисование областей, импорт и экспорт GeoJSON.
- WMS/WFS-слои GeoServer, маршруты и изохроны OpenRouteService, визуализация показателей в ECharts.
- Express API, агрегации в PostGIS и формирование Excel-отчётов по шаблонам через ExcelJS.

### VectorGIS Loader

ETL-сервис для потоковой обработки GeoJSON объёмом более 8 ГБ и 3 млн объектов.

- Потоковая загрузка без размещения всего файла в памяти.
- PostgreSQL COPY в транзакции с откатом при ошибке и проверкой изменений схемы.
- Очередь с восстановлением после перезапуска и realtime-мониторинг через Socket.IO.

## Публичные проекты

- [Resume](https://github.com/Antikab/resume) — резюме как Vue-приложение с общей моделью данных и экспортом в HTML, TXT и PDF. [Открыть](https://resume-proars.vercel.app)
- [ArchTown Platform](https://archtown.org) — контентная платформа на Nuxt 3 / Vue 3 с публикациями, видео, комментариями и подписками.
- [GeoServer Styles](https://github.com/Antikab/geostyle) — библиотека стилей GeoServer с поиском, фильтрами, пагинацией и историей обновлений. [Demo](https://geostyle-dun.vercel.app)
- [Brix Form](https://github.com/Antikab/brix-form) — многошаговая Vue-форма с валидацией и сохранением прогресса. [Demo](https://brix-form.vercel.app)
- [Weather Widget](https://github.com/Antikab/weather) — погодный виджет на Vue 3 с динамическим фоном и автоопределением локации. [Demo](https://widgetweather.vercel.app)

## Опыт

- **ГАУ «Институт Генплана Москвы»** — ведущий программист / Frontend Engineer, март 2026 — настоящее время.
- **ГБУ «ГлавАПУ»** — октябрь 2019 — март 2026: до декабря 2023 архитектор; с января 2024 специалист 1 категории в Центре информационных технологий; с ноября 2024 ведущий специалист; с ноября 2025 ведущий программист / Frontend Engineer.
- **Arch Town Labs CIC** — Frontend Developer, март 2023 — сентябрь 2023.

## Технологии

**Frontend:** Vue 3, Composition API, TypeScript, JavaScript, Nuxt 3, Pinia, Vue Router, Vite, Tailwind CSS

**Архитектура и интеграции:** SPA, REST API, DTO / domain / view models, Zod, AbortController, WebSocket / Socket.IO

**Карты и визуализация:** MapLibre GL, OpenLayers, ECharts, GeoJSON, GeoServer

**Backend и данные:** Node.js, NestJS, Express, PostgreSQL, SQL, PostGIS, MinIO, ExcelJS

**Качество и инфраструктура:** Vitest, Jest, Git, GitHub Actions, CI/CD, ESLint, Prettier, Nginx, PM2

**Дополнительный опыт:** React, Next.js, Prisma, Strapi, Figma
