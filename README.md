# To-Do API – FastAPI + React

Este proyecto es una aplicación **Full Stack** sencilla que implementa un **CRUD de tareas**, desarrollada con **FastAPI** en el backend y **React + Vite** en el frontend.  
El objetivo del proyecto es demostrar el uso y la implementación de una **API REST**, consumo desde una **SPA**, y persistencia de datos con una base de datos relacional.

---

## Tecnologías utilizadas

### API Service
- **Python**
- **FastAPI** – Framework para crear APIs REST
- **SQLite** – Base de datos ligera
- **SQLAlchemy** – ORM para la gestión de datos
- **Pydantic** – Validación y serialización de datos

### Frontend
- **React**
- **Vite**
- **JavaScript**
- **CSS** (diseño responsivo)

---

## Funcionalidades

- Crear tareas
- Listar todas las tareas
- Buscar tareas por nombre
- Editar tareas
- Eliminar tareas
- Marcar tareas como completadas

---

## Ejecución del proyecto

### API Service

cd toDoAPI

uvicorn main:app --reload

> La API estará disponible en:
http://127.0.0.1:8000

> Documentación automática:
http://127.0.0.1:8000/docs

### Frontend

cd todo_frontend

npm install

npm run dev
