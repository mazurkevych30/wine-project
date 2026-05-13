## About the Project
This repository contains the frontend and backend parts of the **Wine Project** — a **team project** focused on exploring the wine industry of Georgia and Ukraine.

The platform provides convenient tools for:
- researching wines,
- discovering wineries,
- browsing wine regions,
- and planning wine tours.

It serves as an informational and navigational web platform designed to help users learn about wine culture and find relevant wine-related experiences.

## My Contributions (Frontend and Backend)
I contributed to both backend and frontend development, implementing key modules, UI components, and application logic.

### Backend
- Added Dockerfile.dev and docker-compose.dev configuration for local development
- Implemented API modules for tours, including controllers, services, routes, and validation
- Created region module: controller, router, service, schema, and validation middleware

### Frontend
- Built responsive Container component and configured global breakpoints
- Initialized wines API service, store logic, and base UI components
- Implemented full Wine Details page (layout, data loading, UI)
- Styled Wine Page and improved visual consistency
- Added search bar with filtering logic
- Implemented pagination for wines list
- Enhanced wine page functionality (sorting, filtering, UI improvements)
- Fixed layout and logic issues on wine page
- Developed Tours module UI
- Added 404 page
- Created About page with layout and content
- Wrote integration tests for wines store (error handling, filtering, API interactions)
- Fixed Tiptap editor initialization and restored static imports
- Improved wines page with responsive design and new UI components


# Wine Discovery Platform 🍷

Інформаційно-навігаційна веб-платформа для дослідження винної індустрії Грузії та України. Проєкт надає зручні інструменти для пошуку вин, знайомства з виноробнями та планування винних турів.

## 📜 Про проєкт

Метою платформи є створення єдиного простору для поціновувачів вина, де поєднуються актуальна база даних, інтелектуальний пошук та персоналізовані поради від ШІ-сомельє.

### Основні можливості:
- **Каталог вин та виноробень:** Детальна інформація, фільтрація та розумний пошук.
- **AI-Сомельє:** Інтеграція з Google Gemini для надання рекомендацій користувачам.
- **Винні тури:** Можливість перегляду та вибору екскурсій.
- **Профілі користувачів:** Збереження улюблених вин, керування відгуками та налаштуваннями.
- **VIP-статус:** Пріоритетне відображення для перевірених виноробень.

## 🛠️ Технологічний стек

| Призначення | Технології |
| :--- | :--- |
| **Frontend** | React 19, TypeScript, Vite, Zustand, React Query, Styled Components |
| **Backend** | Node.js, Express, TypeScript, Mongoose, Firebase Admin SDK |
| **AI** | Google Generative AI (Gemini 2.5 Flash) |
| **Безпека** | Helmet (CSP), Firebase Auth, RBAC |
| **Інфраструктура** | Docker, GitHub Actions, Vercel, Render, MongoDB Atlas |

## 📚 Документація

*   [**Функціонал**](./docs/FEATURES.md) — повний перелік можливостей.
*   [**Архітектура**](./docs/ARCHITECTURE.md) — опис структури системи.
*   [**Безпека та CSP**](./docs/SECURITY.md) — детально про захист проекту.
*   [**Інструкція для розробників**](./docs/DEVELOPMENT.md) — запуск та налаштування.
*   [**API Documentation**](./docs/API.md) — опис ендпоінтів.
*   [**Моделі даних**](./docs/DB-MODELS.md) — структура бази даних.
*   [**Бенчмарки**](./docs/BENCHMARK.md) — показники продуктивності.

---
## 👥 Наша команда

Цей проєкт — результат злагодженої роботи команди професіоналів:

| Учасник | Роль | GitHub |
| :--- | :--- | :--- |
| **Andrii Veremii** | Team Lead, Scrum Master, Fullstack Developer | [AndriiVeremii](https://github.com/AndriiVeremi) |
| **Andrii Popov** | Fullstack Developer, QA Engineer | [Andrii0207](https://github.com/Andrii0207) |
| **Vladyslav Mazurkevych** | Fullstack Developer, QA Engineer | [mazurkevych30](https://github.com/mazurkevych30) |
| **Ihor Dykyi** | UI/UX Designer, PM, Fullstack Developer, QA | [jure-s](https://github.com/jure-s) |

---
## Демо | [Wine Discovery](https://wine-project-three.vercel.app) 

  ![Deployment status](./Demo.jpg)

Розроблено командою **Wine Project**.
