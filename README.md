# Sistema Educativo Distribuido - Microservicios

Este proyecto implementa un **sistema educativo distribuido** basado en arquitectura de microservicios. Cada módulo funcional (usuarios, asignaturas, matrículas, etc.) es independiente, escalable y desplegable de manera autónoma.

## 🧩 Microservicios

- `usuarios-servicio`: Gestión de usuarios, autenticación y roles.
- `asignaturas-servicio`: Administración de asignaturas y programas académicos.
- `matriculas-servicio`: Registro de inscripciones y control de matrículas.
- `notas-servicio`: Gestión de calificaciones y reportes.

## 🚀 Tecnologías utilizadas

- Java 17 / Spring Boot
- Spring Cloud (Eureka, Feign, Gateway)
- MySQL
- Docker
- GitHub Actions para CI/CD

## 📦 Enfoque distribuido

El sistema está dividido en varios microservicios que se comunican a través de **REST** y **mensajería asíncrona (si aplica)**. Cada servicio tiene su propia base de datos y puede ser escalado independientemente.

---

<!---
Davinsonpympy/Davinsonpympy is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
