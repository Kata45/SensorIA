<img width="940" height="511" alt="Captura de pantalla 2026-03-13 111356" src="https://github.com/user-attachments/assets/9de542de-5d15-44df-a713-979aaf58f59b" />

---

<div align="center">
<h1> SensorIA </h1>
</div>

Plataforma digital para la **gestión inteligente de residuos utilizando Inteligencia Artificial e IoT**, desarrollada para apoyar la correcta clasificación de residuos dentro del **SENA – Centro de Biotecnología Agropecuaria (CBA) Mosquera**.

---

<div align="center">
<h1> ☝🏻 Estructura </h1>
</div>

La estructura separa claramente:

- **Frontend** → Aplicación móvil y web para los usuarios  
- **Backend** → API y lógica del sistema  
- **Configuración** → Variables de entorno y dependencias  
- **Documentación** → Información general del proyecto  

---

<div align="center">
<h1> 📁 Estructura inicial del proyecto </h1>
</div>

```

SensorIA/
│
├── frontend/
│   ├── mobile_app/
│   │   ├── lib/
│   │   ├── assets/
│   │   ├── pubspec.yaml
│   │   └── main.dart
│   │
│   └── web_admin/
│       ├── src/
│       ├── public/
│       └── package.json
│
├── backend/
│   ├── app/
│   │   ├── controllers/
│   │   ├── services/
│   │   ├── models/
│   │   └── routes/
│   │
│   ├── config/
│   ├── Dockerfile
│   └── requirements.txt
│
├── database/
│   ├── migrations/
│   └── schema.sql
│
├── docs/
│   └── arquitectura.md
│
├── .env.example
├── docker-compose.yml
└── README.md

```

---

<div align="center">
<h1> 📄 Archivo `.env.example` </h1>
</div>

Este archivo contiene un ejemplo de las variables de entorno necesarias para ejecutar el sistema.

```

PORT=3000

DB_HOST=localhost
DB_PORT=5432
DB_NAME=sensorIA
DB_USER=postgres
DB_PASSWORD=password

JWT_SECRET=your_secret_key

````

---

<div align="center">
<h1> ⚙️ Configuración inicial de dependencias </h1>
</div>

### Frontend (Flutter)

Instalación de dependencias:

```bash
flutter pub get
````

Ejecución del proyecto:

```bash
flutter run
```

---

### Backend

Instalación de dependencias:

```bash
pip install -r requirements.txt
```

Ejecución del servidor:

```bash
python manage.py runserver
```

---

<div align="center">
<h1> 🖥 Evidencia </h1>
</div>

### Árbol de carpetas

La estructura del proyecto se organizó en **frontend, backend y configuración**, permitiendo mantener una arquitectura clara y escalable.

---

### Proyecto ejecutándose localmente

**Backend**

```
Servidor corriendo en:
http://localhost:3000
```

**Frontend**

La aplicación se ejecuta en:

* Emulador Android
* Dispositivo físico conectado

---

<div align="center">
<h1> 📦 Nombre del repositorio </h1>
</div>

```
sensorIA
```

Repositorio principal del proyecto donde se almacena todo el código fuente, documentación y configuraciones del sistema.

---


<div align="center">
<h1> 🌿 Ramas principales </h1>
</div>

Se definieron las siguientes ramas para el desarrollo:

| Rama      | Descripción                  |
| --------- | ---------------------------- |
| main      | Versión estable del proyecto |
| develop   | Rama principal de desarrollo |
| feature/* | Nuevas funcionalidades       |
| fix/*     | Corrección de errores        |

Ejemplos:

```
feature/login
feature/scan-residue
fix/authentication
```

---

<div align="center">
<h1> 📝 Convención de nombres </h1>
</div>

Para mantener consistencia en el código se definieron las siguientes reglas:

### Archivos

```
snake_case
```

Ejemplo:

```
user_service.py
recycling_controller.py
```

---

### Componentes

```
PascalCase
```

Ejemplo:

```
LoginComponent
ScanResidueComponent
DashboardComponent
```

---

### Variables

```
camelCase
```

Ejemplo:

```
userName
residueType
recyclingRecord
```

---

<div align="center">
<h1> 📂 Organización de carpetas </h1>
</div>

La organización del repositorio sigue una arquitectura modular:

```
frontend/
    mobile_app/
    web_admin/

backend/
    controllers/
    services/
    models/
    routes/

database/
    migrations/

docs/
```

Esta estructura permite:

* Separar responsabilidades
* Facilitar el mantenimiento
* Escalar el proyecto en el futuro

---

<div align="center">
<h1> 👨‍💻 Responsables del equipo </h1>
</div>

| Integrante     | Rol                                |
| -------------- | ---------------------------------- |
| Daniel Muñoz   | Desarrollo Backend                 |
| Yeisson Romero | Desarrollo Backend / Base de Datos |
| Sarah González | Desarrollo Frontend /  Diseño UI / Documentación |
| Camila Rivera  | Desarrollo Backend / Base de Datos |

---

<div align="center">
<h1> 🔗 Repositorio del Proyecto </h1>
</div>
```
https://github.com/usuario/sensorIA
```

---
##### © **2025** Creado por *Kata* — Todos los derechos reservados.
---
