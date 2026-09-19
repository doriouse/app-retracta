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
- Modelo 3D do produto

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
python --version
git --version

---

## 2. Baixar o projeto

No GitHub, clique em **Code → Download ZIP** ou clone usando:

git clone URL_DO_REPOSITORIO

Extraia/abra a pasta:

RETRACTA

---

# 3. Executar o Backend

Abra um terminal dentro da pasta `backend`:

cd RETRACTA/backend

Instale as dependências:

pip install -r requirements.txt

Inicialize o banco de dados:

python init_db.py

Inicie o servidor:

uvicorn main:app --reload --host 0.0.0.0 --port 8000

A API estará disponível em:

http://127.0.0.1:8000

A documentação pode ser acessada em:

http://127.0.0.1:8000/docs

# 4. Executar o aplicativo

Abra um **segundo terminal** dentro da pasta `app`:

cd RETRACTA/app

Instale as dependências:

npm install

Inicie o Expo:

```bash
npx expo start
```

Pressione: W

para abrir o aplicativo no navegador.

---

# 5. Estrutura do projeto

RETRACTA/
├── app/        → Aplicativo
├── backend/    → API e banco de dados
├── arduino/    → Sistema embarcado
├── 3d/         → Modelo 3D
└── README.md   → Documentação

---

# 6. Funcionalidades

O projeto possui:

* Splash Screen
* Cadastro de usuários
* Login
* Banco de dados
* Controle do varal
* Automação
* Simulação de chuva e sensores
* Histórico e métricas
* Navegação entre telas
* Modelo 3D
* Simulação do sistema embarcado

## Fluxo do sistema

Aplicativo
    ↓
FastAPI
    ↓
Banco de dados
    ↓
Simulação do sistema
    ↓
Futuro ESP32 + sensores + motor

**RETRACTA — Automação inteligente para proteger suas roupas da chuva.**

