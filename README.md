# Hola, soy Florencia Peña Sepúlveda 👋

Estudiante de la **Universidad Católica del Norte** en proceso de **capstone project**. Trabajo como desarrolladora en mi proyecto de título para **FyC Chile SpA**, y he construido sistemas web y móviles con arquitecturas de microservicios durante la carrera.

📫 **Contacto:** florenciapenasepulveda@gmail.com

---

## 🎓 Proyecto de título (capstone)

### FyC: sistema de gestión integrada
Sistema de gestión integrada desarrollado para la empresa **FyC Chile SpA**, donde mi rol es **desarrolladora**. Está formado por un frontend y un conjunto de microservicios independientes (usuarios, auditoría, organización, notificaciones, documentos, analítica, inventario y requerimientos) detrás de un API Gateway, con scripts de despliegue para QA y producción.

> 🔒 Por confidencialidad el código es privado.

---

## 🚀 Proyectos académicos

Cada componente (frontend, backend, microservicios y gateway) está en su propio repositorio.

### 🏫 AulaConecta: gestión escolar
**Ramo:** Proyecto Integrador de Plataforma

Sistema de gestión escolar con dos tipos de actores, **padres y profesores**: consulta de horarios, publicación de notas y comunicación entre padres y profesores.

| Componente | Repositorio | Tecnologías |
|---|---|---|
| Backend | [aulaconecta-backend](https://github.com/florenciaPenaSepulveda/aulaconecta-backend) | NestJS, TypeScript, MySQL |
| App móvil | [aulaconecta-app](https://github.com/florenciaPenaSepulveda/aulaconecta-app) | React Native / Expo, TypeScript |
| Web | [aulaconecta-web](https://github.com/florenciaPenaSepulveda/aulaconecta-web) | React, Vite, TypeScript, Tailwind CSS |

### 🥗 Remi Recetas: contra el desperdicio de comida
**Ramo:** Cloud Computing

Ayuda a reducir el desperdicio de comida en los hogares: el usuario **busca recetas por los ingredientes que tiene**, para aprovechar todo lo que dispone. También permite **crear recetas, puntuarlas y comentarlas**. Un sistema de **tags** organiza las recetas por categoría (italiana, dulce, desayuno, etc.) y por avisos y filtros (apto para veganos, apto para celíacos, etc.). Los usuarios registrados pueden **guardar recetas**.

| Componente | Repositorio | Tecnologías |
|---|---|---|
| Frontend | [remi-frontend](https://github.com/florenciaPenaSepulveda/remi-frontend) | React |
| API Gateway | [remi-gateway](https://github.com/florenciaPenaSepulveda/remi-gateway) | NestJS, RabbitMQ |
| Recetas | [remi-ms-recetas](https://github.com/florenciaPenaSepulveda/remi-ms-recetas) | NestJS, MongoDB |
| Usuarios | [remi-ms-users](https://github.com/florenciaPenaSepulveda/remi-ms-users) | NestJS, MongoDB |
| Social (puntuaciones y comentarios) | [remi-ms-socials](https://github.com/florenciaPenaSepulveda/remi-ms-socials) | NestJS, RabbitMQ |
| Tags | [remi-ms-tags](https://github.com/florenciaPenaSepulveda/remi-ms-tags) | NestJS, RabbitMQ |

### 🕒 Marcapp: control de asistencia
**Ramo:** Introducción al Desarrollo Web/Mobile

Aplicación para que los trabajadores **marquen entradas y salidas**, pensada para poder usarse y **guardar los registros incluso en lugares sin señal**.

| Componente | Repositorio | Tecnologías |
|---|---|---|
| App | [marcapp-front](https://github.com/florenciaPenaSepulveda/marcapp-front) | React Native / Expo, TypeScript |
| Login y roles | [marcapp-login-ms](https://github.com/florenciaPenaSepulveda/marcapp-login-ms) | NestJS, TypeORM, MySQL |
| Marcaje | [marcapp-marcaje-ms](https://github.com/florenciaPenaSepulveda/marcapp-marcaje-ms) | NestJS, TypeORM, PostgreSQL |

### 🔧 AutoTaller: gestión de talleres mecánicos
**Ramo:** Arquitectura de Sistemas

Plataforma para que los **talleres mecánicos** se comuniquen con sus clientes: los clientes **registran sus vehículos y reservan horas**, y los mecánicos **gestionan su disponibilidad, atienden las reservas y dejan observaciones** que quedan como **historial del vehículo**.

| Componente | Repositorio | Tecnologías |
|---|---|---|
| Frontend (cliente y mecánico) | [arquitectura-frontend-sistema](https://github.com/florenciaPenaSepulveda/arquitectura-frontend-sistema) | React, Vite, Tailwind CSS |
| MS1: autenticación, usuarios y vehículos | [arquitectura-ms1](https://github.com/florenciaPenaSepulveda/arquitectura-ms1) | NestJS, gRPC, MongoDB |
| MS2: observaciones e historial del vehículo | [arquitectura-ms2](https://github.com/florenciaPenaSepulveda/arquitectura-ms2) | Java, Spring Boot, gRPC |
| MS3: disponibilidad y reservas | [arquitectura-ms3](https://github.com/florenciaPenaSepulveda/arquitectura-ms3) | Go, PostgreSQL, NATS |
| MS4: gateway GraphQL con autenticación JWT | [arquitectura-ms4](https://github.com/florenciaPenaSepulveda/arquitectura-ms4) | NestJS, GraphQL |
| Contratos gRPC | [arquitectura-proto-contracts](https://github.com/florenciaPenaSepulveda/arquitectura-proto-contracts) | Protocol Buffers |
| Despliegue | [arquitectura-k8s](https://github.com/florenciaPenaSepulveda/arquitectura-k8s) | Kubernetes |

### 🦷 Clínica dental: agenda de horas
**Ramo:** Arquitectura de Sistemas (primer proyecto)

Gestión de la **toma de horas en un centro de salud dental** con distintos especialistas: pacientes, dentistas por región, servicios con duración y precio, y agenda con **control de sobrecupos**.

| Componente | Repositorio | Tecnologías |
|---|---|---|
| Backend | [dental-clinic-backend](https://github.com/florenciaPenaSepulveda/dental-clinic-backend) | Django, Docker |
| Frontend | [dental-clinic-frontend](https://github.com/florenciaPenaSepulveda/dental-clinic-frontend) | React, TypeScript |

### 👥 Módulo de Recursos Humanos de un ERP
**Ramo:** Sistemas de Información I (trabajo en grupo)

Nuestra parte del trabajo fue el **módulo de RRHH** de un ERP, que luego se integró al sistema completo.

| Componente | Repositorio | Tecnologías |
|---|---|---|
| Backend RRHH | [rrhh-backend](https://github.com/florenciaPenaSepulveda/rrhh-backend) | NestJS, Prisma |
| Frontend del ERP | [erp-front](https://github.com/florenciaPenaSepulveda/erp-front) | React, Vite, TypeScript |

---

## 🛠️ Tecnologías

**Lenguajes:** TypeScript · JavaScript · Go · Java · Python
**Backend:** NestJS · Django · Spring Boot · gRPC · GraphQL · RabbitMQ · NATS
**Frontend y móvil:** React · React Native / Expo · Vite · Tailwind CSS
**Datos:** PostgreSQL · MySQL · MongoDB · Prisma · TypeORM
**DevOps:** Docker · Docker Compose · Kubernetes · CI/CD
