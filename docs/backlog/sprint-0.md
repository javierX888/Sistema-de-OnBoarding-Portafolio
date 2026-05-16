# Sprint 0: Cimentación y Configuración Base 🏗️

Este Sprint se enfoca en establecer las bases técnicas y administrativas del proyecto para asegurar un desarrollo fluido en los sprints funcionales posteriores.

## Historias de Usuario (Backlog Sprint 0)

| ID | Título | Descripción | Estado |
| :--- | :--- | :--- | :--- |
| **HU-00-01** | Estructura de Repositorio | Definir carpetas, ramas y convenciones (GitFlow, Commits). | ✅ Completado |
| **HU-00-02** | Inicialización Técnica | Configuración base de entornos Backend y Frontend. | 🔄 En Progreso |
| **HU-00-03** | Autenticación Keycloak | Configurar Realm, Clientes y Roles base en Keycloak. | ⏳ Pendiente |
| **HU-00-04** | Definición de Endpoints | Documentar contratos de API internos (Request/Response). | ⏳ Pendiente |

---

## Detalle HU-00-01: Estructura y Convenciones

### 📂 Estructura del Repositorio
- `backend/`: API y Lógica de negocio.
- `frontend/`: Aplicación cliente (Web/Mobile).
- `docs/`: Documentación del proyecto.
- `Fase 1/`: Archivos legacy y wireframes iniciales.

### 🌿 Estrategia de Ramas
Se utilizará un modelo GitFlow simplificado:
- **`main`**: Rama productiva.
- **`develop`**: Rama de integración continua.
- **`feature/HU-[ID]-[Descripcion]`**: Ramas de desarrollo por tarea.

### 💬 Convenciones de Commits
Formato: `<tipo>: <descripción>`
Ejemplos:
- `feat: agregar login con keycloak`
- `fix: corregir error en redirección de logout`
- `docs: actualizar readme con estructura de sprint 0`

---

## Próximos Pasos (Sprint 0)
1. **HU-00-02**: Decidir Stack tecnológico definitivo (Ej: Express + React) e inicializar proyectos con `npm init`.
2. **HU-00-04**: Crear archivo `docs/api/endpoints.md` con los primeros CRUDs de Empresas y Usuarios.
