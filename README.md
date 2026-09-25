# RETRACTA

## Sistema Inteligente de Automação Residencial

O RETRACTA é um sistema IoT que automatiza um varal retrátil, utilizando sensores e um aplicativo para monitorar as condições climáticas e controlar o varal.

## Tecnologias

- React Native + Expo
- TypeScript
- Python + FastAPI
- SQLAlchemy
- SQLite
- ESP32 (integração futura)

---

# Como executar o projeto

## 1. Pré-requisitos

**Instale no computador:**

- Node.js
- Python
- Git

**Verifique:**

node --version
npm --version
python --version (winget install Python.Python.3.14)
git --version

---

cd C:\Users\Dell\Documents\RETRACTA\app
npx expo start

Terminal 1 — backend:

cd C:\Users\Dell\Documents\RETRACTA\backend
fastapi dev main.py

Terminal 2 — app:

cd C:\Users\Dell\Documents\RETRACTA\app
npx expo start -c

