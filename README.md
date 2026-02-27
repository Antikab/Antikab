# Арсений Просветов

Frontend Developer (Vue 3 + TypeScript) с опытом Node.js и PostgreSQL/PostGIS.  
Делаю аналитические интерфейсы и сложные пользовательские сценарии: **данные → метрики → таблицы → отчёты**. Фокус — performance и архитектура.

## Ключевые навыки

- Продуктовый data-flow: UI → API → БД, устойчивые сценарии и понятные контракты
- Performance: профилирование DevTools, оптимизация рендера/JS/запросов, поиск bottleneck’ов
- Экспорт: ExcelJS (шаблоны, много листов, форматирование, формулы)
- Большие объёмы: пайплайны GeoJSON до **8+ ГБ / 3+ млн объектов** (батчи, прогресс, контроль ошибок)
- Карты/геоданные: OpenLayers + GeoServer (WMS/WFS), GeoJSON, hover/selection, стили слоёв
- Backend: Express + TypeScript; расчёты и агрегации в SQL/PostGIS

## Публичные проекты

- **Brix Form** — многошаговая форма  
  Demo: https://brix-form.vercel.app · Repo: https://github.com/Antikab/brix-form

- **Weather Widget** — Vue 3 виджет погоды  
  Demo: https://widgetweather.vercel.app · Repo: https://github.com/Antikab/weather

## Опыт

**ГлавАПУ — Frontend Engineer (11.2023 — н.в.)**  
`glavapu-stat` — аналитический продукт: карта/визуализация → расчёты → отчётность
- Реализовал сценарий “карта → метрики → отчёт” в одном интерфейсе
- OpenLayers + GeoServer: WMS/WFS слои, интерактивность, импорт/экспорт GeoJSON
- Backend: Express + TS; перенёс **50+** агрегаций в SQL/PostGIS
- Экспорт отчётов: ExcelJS  
**Результат:** 10+ геослоёв, 100+ отчётов/мес, стабильность при росте данных

**Arch Town Labs CIC — Frontend Developer (05.2024 — 11.2024)**
- Фиксы видео-сценариев Safari/Firefox, стабилизация ключевых пользовательских потоков
- Упрощение публикации/поиска/навигации

## Технологии

**Frontend:** Vue 3, TypeScript, Pinia, Vite, TailwindCSS  
**Backend/Data:** Node.js (Express), PostgreSQL, PostGIS, Prisma, WebSocket  
**GIS:** OpenLayers, GeoServer (WMS/WFS), GeoJSON  
**Infra/Tools:** Docker, MinIO, Git, CI, Postman, Figma
