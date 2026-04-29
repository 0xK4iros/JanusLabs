# Janus - Fase 1: Estructura de Issues

## ÉPICA 1: Arquitectura Base e Infraestructura (Semanas 1-2 | Mayo)

### Epic Description
Fundamentos del backend, bases de datos y la persistencia de estado dual (Ataque y Defensa).

### Tickets
- Ticket 1.1: Setup de Repositorios y Entorno ✅ (¡Completado!)
- Ticket 1.2: Infraestructura Local (Docker)
- Ticket 1.3: Modelado de BD (Core y Defensa)
- Ticket 1.4: Modelado de BD (Modo Ataque)
- Ticket 1.5: Migraciones con Alembic
- Ticket 1.6: El "Walking Skeleton"

---

## ÉPICA 2: El Motor de Contenido (Semana 3 | Mayo)

### Epic Description
Creación del "molde" (el esquema) para estandarizar los retos y separar el contenido del código.

### Tickets
- Ticket 2.1: Diseño del challenge_schema.json (Dual)
- Ticket 2.2: Modelos Pydantic en FastAPI

---

## ÉPICA 3: Diseño Técnico de los Retos MVP Reducido (Semanas 4-7 | Junio)

### Epic Description
Diseño de aplicaciones vulnerables, caminos de explotación y pruebas DAST para los 3 retos principales.

### Tickets
- Ticket 3.1: Reto 01 — "Login Roto" (SQLi - Fácil)
- Ticket 3.2: Reto 02 — "El Comentario" (XSS Reflejado - Fácil)
- Ticket 3.3: Reto 03 — "Mi Perfil" (IDOR - Fácil)
- Ticket 3.4: Buffer, Integración y Documentación

---

## ÉPICA 4: Burocracia Académica y Protocolo (Semana 8 | Fin de Junio)

### Epic Description
Blindaje del proyecto ante la universidad para pasar a la Fase 2 sin riesgos.

### Tickets
- Ticket 4.1: Encuesta de Validación Empírica
- Ticket 4.2: Anexos Legales
- Ticket 4.3: Registro del Protocolo Formal
- Ticket 4.4: Prueba End-to-End del Flujo MVP
