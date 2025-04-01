# 💰 MoneyFlow - Gestión Inteligente de Finanzas Personales

## 📌 Descripción
MoneyFlow es una aplicación web diseñada para simplificar la gestión financiera personal, permitiendo registrar ingresos/gastos, establecer presupuestos y visualizar métricas clave mediante gráficos interactivos. Desarrollada para la clase de Ingeniería de Software (UVG) con tecnologías modernas.

---

## 🌟 Características Principales
- 📊 Dashboard financiero con gráficos interactivos
- 💸 Registro manual de transacciones con categorías personalizables
- 🎯 Metas de ahorro y alertas de presupuesto
- 📤 Exportación de reportes en PDF/CSV
- 🔐 Autenticación segura con JWT

---

## 🛠️ Tecnologías Utilizadas

| Frontend          | Backend        | Base de Datos    | Infraestructura            |
|------------------|---------------|----------------|----------------------------|
| React 19 + Vite | Node.js 18     | PostgreSQL 13  | Docker + Docker Compose   |
| TypeScript      | Express.js     | Sequelize (ORM) | Nginx (producción)        |
| Chart.js        | JWT            |                |                            |

---

## 🚀 Cómo Empezar

### Prerrequisitos
- Docker 20.10+ y Docker Compose
- Node.js 18+
- npm 9+

### Instalación Local

Clonar el repositorio:

```bash
git clone https://github.com/tu-usuario/Proyecto_Software_MoneyFlow.git
cd Proyecto_Software_MoneyFlow
```

Configurar variables de entorno:

Crear archivo `.env` en `/backend` basado en `.env.example`:

```env
DB_HOST=db
DB_USER=postgres
DB_PASSWORD=1234
JWT_SECRET=tu_clave_secreta
```

Levantar servicios con Docker:

```bash
docker-compose up --build
```

Acceder a la aplicación:

- 🔹 **Frontend**: [http://localhost:3001](http://localhost:3001)  
- 🔹 **Backend (API)**: [http://localhost:3000](http://localhost:3000)  

---

## 📂 Estructura del Proyecto

```bash
.
├── backend/          # API en Node.js
│   ├── models/       # Modelos de PostgreSQL
│   ├── routes/       # Endpoints API
│   └── db/           # Configuración de la base de datos
├── frontend/         # Aplicación React
│   ├── src/components/
│   └── src/pages/     # Vistas principales
├── docs/             # Documentación técnica
└── docker-compose.yml # Orquestación de contenedores
```

---

## 🔧 Comandos Útiles

| Comando                        | Descripción                         |
|--------------------------------|-------------------------------------|
| `docker-compose up --build`    | Levanta todos los servicios        |
| `docker-compose down -v`       | Detiene servicios y elimina volúmenes |
| `npm run dev` (en `/frontend`) | Modo desarrollo frontend           |
| `npm test` (en `/backend`)     | Ejecuta tests unitarios            |

---

## 📄 Documentación Adicional
- 📘 Documento de diseño técnico
- 📋 Historias de usuario y backlog
- 📚 API Reference (Si usas Swagger)

---

## 🤝 Cómo Contribuir

1. Haz fork del proyecto
2. Crea una rama (`git checkout -b feature/nueva-funcionalidad`)
3. Haz commit de tus cambios (`git commit -m 'Add some feature'`)
4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

---

## 📜 Licencia

MIT License - Ver `LICENSE` para más detalles.

---

✨ Desarrollado por [Tu Nombre] - [@tu-github](https://github.com/tu-github)  
🏛 Universidad del Valle de Guatemala - Ingeniería de Software 2025

---

## 🔗 Enlaces Rápidos
- 🌍 **Deploy en Render**
- ⚡ **Frontend en Vercel**