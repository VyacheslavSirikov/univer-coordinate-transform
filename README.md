# 🧭 Преобразование координатных данных

## 📌 Описание

Веб-приложение для преобразования координат.  
Пользователь загружает Excel-файл с координатами (столбцы: Name, X, Y, `Z`).  
Приложение выполняет преобразование и возвращает Markdown-отчет с:

- Формулой преобразования
- Примером вычисления
- Таблицей координат до и после
- Статистикой отклонений

🖥️ Бэкенд: FastAPI  
🌐 Фронтенд: Streamlit

---

## 🌐 Онлайн-версия

👉 [ОТКРЫТЬ ПРИЛОЖЕНИЕ](https://univer-transform-app.streamlit.app) 👈

| 🔗 Компонент | URL                                                                                    | ⚡ Статус |
| ------------ | -------------------------------------------------------------------------------------- | --------- |
| Frontend     | [univer-transform-app.streamlit.app](https://univer-transform-app.streamlit.app)       | 🟥 LIVE   |
| Backend API  | [univer-transform-backend.onrender.com](https://univer-transform-backend.onrender.com) | 🟩 LIVE   |

⚠️ Важно: Первый запуск может занять 2–3 минуты из-за холодного старта сервера на Render.com.

---

## 🗂️ Структура проекта

- main.py — FastAPI-бэкенд для обработки Excel и генерации отчета.
- app.py — Streamlit-фронтенд для загрузки файла.
- coordinate_transform.py — функции преобразования координат и генерации отчета.
- generate_test.py — генерация тестового файла .xlsx.
- help.js — подсказки для команд в терминале.
- parameters.json — параметры преобразования.
- requirements.txt — зависимости.
- .gitignore — исключение ненужных файлов (`venv/`, **pycache**/ и т.д.).

---

## ⚙️ Установка и локальный запуск

1. Клонируйте репозиторий:

   ```bash
   git clone https://github.com/VyacheslavSirikov/univer-coordinate-transform.git
   cd univer-coordinate-transform
   ```
