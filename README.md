# 🩺 HealthCooperationWeb

**Proyecto final del curso Full Stack Web Developer – Egg Academy (2024)**  
Aplicación web funcional para la gestión integral de turnos médicos, desarrollada con **Java Spring Boot**, **Thymeleaf** y **MySQL**.

---

## 🚀 Descripción

HealthCooperationWeb es una aplicación diseñada para clínicas o consultorios médicos, que permite a los pacientes **registrarse, iniciar sesión y solicitar turnos** con distintos profesionales de la salud.

Incluye funcionalidades para administración, profesionales y pacientes, brindando una gestión completa de la información médica y los horarios de atención.

---

## ⚙️ Características principales

- 🔐 **Sistema de autenticación y roles** (Administrador, Profesional, Paciente)
- 🗓️ **Gestión de turnos**: creación, asignación, modificación y cancelación
- 👩‍⚕️ **Agenda semanal** para profesionales
- 📋 **Historias clínicas y fichas médicas** por paciente
- 💬 **Notificaciones por correo electrónico**
- 💻 **Panel de administración** con control de usuarios y horarios
- 🌐 **Interfaz desarrollada con HTML, CSS y Thymeleaf**
- 🧩 Arquitectura **MVC (Modelo-Vista-Controlador)** implementada con Spring Boot

---

## 🧰 Tecnologías utilizadas

| Categoría | Herramientas |
|------------|---------------|
| **Backend** | Java 17 · Spring Boot · Maven · JPA/Hibernate |
| **Frontend** | HTML · CSS · Bootstrap · Thymeleaf |
| **Base de datos** | MySQL |
| **Control de versiones** | Git · GitHub |

---

## 🏗️ Estructura del proyecto

src/
├── main/
│ ├── java/com/grupo3/HealthCooperationWeb/
│ │ ├── controladores/ → Controladores de la aplicación
│ │ ├── entidades/ → Clases de modelo (Pacientes, Profesionales, Turnos, etc.)
│ │ ├── repositorios/ → Repositorios JPA
│ │ └── seguridad/ → Configuración de seguridad
│ └── resources/
│ ├── templates/ → Vistas Thymeleaf
│ ├── static/ → Recursos estáticos (CSS, imágenes, JS)
│ └── application.properties


---

## 🧑‍💻 Equipo de desarrollo

Proyecto desarrollado por el grupo 3 – Egg Academy.  
Integrantes:
- **Ezequiel Gamarro** – Backend / Integración


---

## 🏁 Cómo ejecutar el proyecto

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tuusuario/HealthCooperationWeb.git
   
1-Abrir el proyecto en IntelliJ IDEA o Spring Tool Suite.

2-Configurar la base de datos MySQL en application.properties.

3-Ejecutar la clase HealthCooperationWebApplication.java.

Acceder desde el navegador:
http://localhost:8080

📜 Licencia

Proyecto educativo desarrollado para fines de aprendizaje – Egg Academy (2024).

