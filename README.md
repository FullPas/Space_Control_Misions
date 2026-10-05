# Space_Control_Misions
🚀 Mission Control AI
Plataforma de gestión y simulación de misiones espaciales con IA operativa
Mission Control AI es una aplicación web Full Stack donde la inteligencia artificial no es un chatbot, sino un copiloto operativo capaz de:

crear misiones automáticamente,

optimizar recursos,

simular escenarios,

detectar fallos,

generar informes,

modificar datos en tiempo real,

y asistir al usuario en la toma de decisiones críticas.

El proyecto está construido con Python, Flask, React, SQL, JWT, Docker y un sistema de agentes IA + skills + MCPs que interactúan con el backend para añadir valor real a la experiencia del usuario.

🧠 Características principales
🔸 IA operativa (no solo informativa)
La IA puede:

Crear misiones completas a partir de parámetros del usuario.

Optimizar combustible, recursos y rutas.

Detectar riesgos y generar eventos automáticamente.

Simular escenarios (tormentas solares, fallos de módulo, etc.).

Recomendar abortar o continuar una misión.

Generar informes técnicos en tiempo real.

Actuar como copiloto en el panel de misión.

🔸 Panel de control estilo NASA
Dashboard con telemetría, gráficos orbitales y estado global.

Animaciones fluidas y diseño curvado inspirado en estética espacial.

Paletas de color dinámicas según sección (misiones, IA, recursos, etc.).

🔸 Arquitectura profesional en contenedores
Frontend (React + Bootstrap)

Backend (Flask + IA + JWT)

Base de datos (PostgreSQL)
Todo orquestado con Docker Compose.

🔸 Seguridad y autenticación
JWT para login y roles (admin, comandante, analista).

Validaciones completas en formularios y endpoints.

🔸 Tests
Tests unitarios (Flask).

Tests de integración (React + API).

Tests de IA con mocks.

📁 Estructura de carpetas
Código
Mission-Control-AI/
│
├── frontend/                 # React + Bootstrap
│   ├── public/
│   ├── src/
│   │   ├── components/       # Componentes reutilizables
│   │   │   ├── layout/
│   │   │   ├── dashboard/
│   │   │   ├── missions/
│   │   │   ├── missionDetail/
│   │   │   ├── ai/
│   │   │   └── ui/
│   │   ├── pages/            # Vistas principales
│   │   ├── hooks/
│   │   ├── context/          # ThemeProvider, AuthContext
│   │   ├── services/         # Llamadas a la API
│   │   └── router/
│   └── package.json
│
├── backend/                  # Flask + IA + JWT
│   ├── app/
│   │   ├── controllers/      # Endpoints REST
│   │   ├── models/           # SQLAlchemy
│   │   ├── services/         # Lógica de negocio
│   │   ├── ai/               # Agentes, skills, MCPs
│   │   ├── utils/            # JWT, validaciones, helpers
│   │   └── config/
│   ├── tests/
│   └── requirements.txt
│
├── db/                       # Scripts SQL, migraciones
│   ├── init.sql
│   └── migrations/
│
├── docker-compose.yml
├── README.md
└── .env
🧩 Tecnologías utilizadas
Frontend
React

Bootstrap

React Router

Context API

Chart.js / Recharts

Animaciones CSS fluidas

Backend
Python

Flask

SQLAlchemy

JWT Authentication

Blueprints

Validaciones personalizadas

Base de datos
PostgreSQL

Migraciones SQL

IA
Sistema de agentes

Skills especializadas (riesgo, ruta, simulación, informes)

MCPs para APIs externas (NASA, SpaceX, etc.)

Infraestructura
Docker

Docker Compose

Entornos .env

Testing
Pytest

Jest / React Testing Library

Mocks para IA

🌌 Objetivo del proyecto
Demostrar cómo una aplicación web moderna puede integrar IA operativa para añadir valor real al usuario, automatizar procesos complejos y simular escenarios en tiempo real, todo dentro de una arquitectura profesional y escalable.

Mission Control AI está diseñado para ser un proyecto Full Stack con IA avanzada, ideal para demostrar habilidades técnicas en:

desarrollo web,

diseño de arquitectura,

integración de IA,

gestión de datos,

y despliegue con contenedores.
