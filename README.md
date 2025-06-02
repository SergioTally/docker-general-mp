# Prueba Técnica MP – Contenedor General

Este repositorio contiene la configuración general con Docker para levantar el sistema completo de la Prueba Técnica del MP, incluyendo:

- Backend (Node.js + Express + Sequelize)
- Frontend (React)
- Base de datos SQL Server

---

## 🚀 Instrucciones para ejecutar todo el sistema

### 1. Clonar este repositorio

```bash
git clone https://github.com/usuario/docker-general-mp.git .
```

### 2. Clonar los módulos `backend` y `frontend`

```bash
git clone https://github.com/SergioTally/backend-mp backend
git clone https://github.com/SergioTally/backend-mp frontend
```

---

### 3. Ejecutar Docker Compose

```bash
docker-compose up --build
```

Esto construirá e iniciará:

- El backend en [http://localhost:4000](http://localhost:4000)
- El frontend en [http://localhost:3000](http://localhost:3000)
- SQL Server en `localhost:1533`

---

## 🔧 Requisitos

- Docker y Docker Compose instalados
- Acceso a los repositorios privados o públicos del frontend y backend
- Puerto `1533` libre (para SQL Server)

---

## 📄 Documentación adicional

Consulta el archivo `Manual Tecnico.docx` incluido en este repositorio para más detalles de configuración, roles, seguridad y estructura.
