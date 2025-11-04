# ClinicaMed – Sistema de Gestão Médica

> Full-stack: Login JWT, Dashboard (Chart.js), CRUD pacientes. Substitui Java Swing por web moderno.

<image-card alt="Demo GIF aqui" src="https://via.placeholder.com/800x400?text=Login+Demo" ></image-card>  

## Funcionalidades
- Login/Logout seguro
- Dashboard com métricas/gráficos
- Tabela de pacientes (futuro CRUD)

## Tech Stack
| Camada | Tech |
|--------|------|
| Front | React + Vite + Tailwind |
| Estado | Zustand |
| Back | Node.js + Express + JWT |
| DB | MySQL |

## Deploy
- Front: [clinicamed.adailc.dev](https://clinicamed.vercel.app)  
- API: [api.clinicamed.railway.app](...)  

## Como Rodar
```bash
cd frontend && npm install && npm run dev  # http://localhost:5173
cd backend && npm install && npm run dev   # http://localhost:3001
