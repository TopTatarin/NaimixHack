# Tarot Recruiter

## Описание
**Tarot Recruiter** — это инструмент для рекрутеров, который использует карты Таро и космограммы для оценки кандидатов и их совместимости с командой.

---

## Установка

1. **Backend**:
   - Установите зависимости:
     ```bash
     cd backend
     npm install
     ```
   - Настройте `.env`:
     ```
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```
   - Запустите сервер:
     ```bash
     npm run server
     ```

2. **Frontend**:
   - Установите зависимости:
     ```bash
     cd frontend
     npm install
     ```
   - Настройте прокси:
     ```json
     "proxy": "http://localhost:5000"
     ```
   - Запустите приложение:
     ```bash
     npm start
     ```

---

## Функционал
- Добавление кандидатов и сотрудников.
- Построение космограммы и анализ карт Таро.
- Оценка совместимости и генерация отчетов.
