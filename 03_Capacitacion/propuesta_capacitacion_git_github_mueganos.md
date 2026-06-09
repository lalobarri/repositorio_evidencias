# Propuesta de Capacitación: Git y GitHub para Programadores Junior
## Equipo Los Mueganos

## 🎯 Objetivo de aprendizaje

Al finalizar la actividad, el Programador Junior será capaz de:

- Clonar repositorios remotos y mantenerlos actualizados.
- Crear y gestionar ramas para desarrollar funcionalidades de forma aislada.
- Realizar commits con mensajes descriptivos siguiendo buenas prácticas.
- Resolver conflictos de fusión (merge conflicts) en escenarios simples.
- Crear Pull Requests y solicitar revisiones de código.
- Revisar contribuciones de otros desarrolladores y aprobar o solicitar cambios.
- Sincronizar su trabajo local con el repositorio remoto.

---

## 📝 Descripción de la dinámica

**Formato:** Colaborativa (por parejas o tríos)

**Proyecto base:** Un repositorio ficticio llamado `calculadora-colaborativa` que contiene una calculadora básica en JavaScript con funciones incompletas.

**Mecánica:** Los participantes avanzan por 4 niveles (misiones), cada uno con desafíos específicos. Cada nivel debe ser completado y validado por un compañero antes de pasar al siguiente.

**Evaluación del progreso:** Cada nivel otorga una insignia virtual. Al completar los 4 niveles, el participante recibe un certificado de "Git Explorer".

**Duración estimada:** 2 horas

---

## 🧪 Retos o misiones

### Nivel 1: Explorador Git (Fundamentos)

| Desafío | Comandos a usar |
|---------|----------------|
| Clonar el repositorio `calculadora-colaborativa` | `git clone <url>` |
| Explorar el historial de commits | `git log --oneline` |
| Identificar en qué rama se encuentra | `git branch` |
| Ejecutar el proyecto localmente | Abrir `index.html` |

**Entregable:** Captura de pantalla del proyecto funcionando localmente.

---

### Nivel 2: Constructor de Funcionalidades (Ramas y commits)

| Desafío | Comandos a usar |
|---------|----------------|
| Crear una rama llamada `feature/resta` | `git checkout -b feature/resta` |
| Implementar la función de resta en `calculadora.js` | Editar archivo |
| Registrar el cambio con un commit descriptivo | `git add .` + `git commit -m "[RESTA] Implementa función restar"` |
| Subir la rama al repositorio remoto | `git push origin feature/resta` |

**Entregable:** Captura del commit y confirmación de que la rama está en GitHub.

---

### Nivel 3: Colaborador del Equipo (PR y conflictos)

| Desafío | Comandos a usar |
|---------|----------------|
| Crear un Pull Request desde `feature/resta` hacia `main` | Interfaz web de GitHub |
| Solicitar revisión a un compañero | Asignar reviewer |
| Simular un conflicto (ambos modifican la misma línea) | Editar mismo archivo en paralelo |
| Resolver el conflicto localmente | `git pull origin main` + resolver marcadores |
| Completar el merge | `git add .` + `git commit` + `git push` |

**Entregable:** Captura del PR aprobado y del conflicto resuelto.

---

### Nivel 4: Revisor de Código (Revisión de contribuciones)

| Desafío | Acción |
|---------|--------|
| Revisar el PR de un compañero | Analizar cambios |
| Probar la funcionalidad localmente | `git checkout feature/multiplicacion` |
| Dejar comentarios específicos | Usar interfaz de GitHub |
| Aprobar el PR o solicitar cambios | Hacer clic en "Approve" o "Request changes" |

**Entregable:** Captura de pantalla donde se vea la revisión realizada.

---

## 📸 Evidencias de aprendizaje

El participante deberá entregar:

1. **Capturas de pantalla** de cada nivel completado.
2. **Historial de commits** (`git log --oneline`) al finalizar la actividad.
3. **Listado de Pull Requests** creados y revisados (enlaces a GitHub).
4. **README reflexivo** donde responda las preguntas de reflexión.
5. **Video corto (opcional)** mostrando la resolución de un conflicto.

---

## 📊 Criterios de evaluación

| Criterio | Peso | Indicador |
|----------|------|-----------|
| Uso correcto de comandos Git | 25% | Ejecuta los comandos sin errores graves |
| Gestión de ramas | 20% | Crea, cambia y elimina ramas correctamente |
| Calidad de commits | 15% | Mensajes claros, cambios atómicos |
| Resolución de conflictos | 20% | Identifica y resuelve conflictos sin ayuda |
| Colaboración (PRs y revisiones) | 20% | Crea PRs descriptivos y revisa a compañeros |

**Escala de valoración:**
- **Excelente (90-100%):** Completa todos los niveles sin ayuda y ayuda a otros.
- **Satisfactorio (70-89%):** Completa los niveles con mínima asistencia.
- **En desarrollo (50-69%):** Completa parcialmente, requiere guía.
- **No logrado (<50%):** No completa los niveles básicos.

---

## 💬 Preguntas de reflexión

### 1. ¿Qué ventajas ofrece Git frente a guardar múltiples versiones de un archivo manualmente?

Git permite rastrear cambios de forma granular, volver a cualquier punto anterior, trabajar en paralelo mediante ramas y colaborar sin sobrescribir el trabajo de otros. Guardar versiones manualmente (ej: `script_final_v2_ultimo_realmente final.js`) es propenso a errores, pérdida de contexto y dificulta la colaboración.

### 2. ¿Por qué es importante trabajar mediante ramas?

Las ramas permiten desarrollar funcionalidades de forma aislada, experimentar sin afectar el código estable, y facilitar la integración progresiva. En equipos, cada miembro puede trabajar en su propia rama, reduciendo conflictos y manteniendo `main` siempre funcional.

### 3. ¿Qué beneficios aportan los Pull Requests en un equipo de desarrollo?

Los PRs son el centro de la revisión de código. Permiten:
- Detectar errores antes de que lleguen a `main`.
- Compartir conocimiento entre el equipo.
- Mantener un historial claro de qué cambió, quién lo hizo y por qué.
- Automatizar pruebas (con GitHub Actions) antes de fusionar.

### 4. ¿Cómo puede un líder técnico verificar que todos los integrantes están contribuyendo al proyecto?

A través de:
- `git shortlog -sn` para ver commits por autor.
- **Insights → Contributors** en GitHub.
- Revisar Pull Requests creados y comentados.
- Analizar el historial de Issues asignadas.
- Usar GitHub Projects para ver el progreso de tareas.

### 5. ¿Qué habilidades técnicas y de colaboración desarrolla un programador al utilizar Git y GitHub?

**Técnicas:**
- Gestión de versiones y ramas.
- Resolución de conflictos.
- Automatización con GitHub Actions.
- Documentación mediante README y comentarios.

**Colaborativas:**
- Comunicación asíncrona a través de PRs.
- Revisión de código respetuosa.
- Trabajo en paralelo sin bloqueos.
- Responsabilidad sobre el código propio y el del equipo.

---

## 🏆 Desafío Extra: Herramientas complementarias

| Herramienta | Propósito | Beneficio para colaboración |
|-------------|-----------|----------------------------|
| **GitHub Projects** | Tablero Kanban para gestionar tareas | Visualiza el flujo de trabajo, asigna responsables y da seguimiento. |
| **GitHub Issues** | Rastreo de bugs y mejoras | Centraliza discusiones, referencia a commits y PRs. |
| **GitHub Actions** | Automatización de CI/CD | Ejecuta pruebas automáticamente al crear PRs, evitando errores. |
| **GitLab** | Alternativa a GitHub (repositorios + CI/CD integrado) | Ofrece pipelines nativos y mayor control en entornos empresariales. |
| **Jira** | Gestión de proyectos ágiles | Integración con GitHub, seguimiento de épicas, historias y sprints. |
| **Azure DevOps** | Plataforma completa (repos, pipelines, boards) | Ideal para equipos que usan Microsoft stack, con trazabilidad total. |

---

## 🚀 Meta final

Al completar esta capacitación, el Programador Junior podrá integrarse a un equipo profesional de desarrollo de software, comprendiendo no solo los comandos de Git, sino el flujo de trabajo colaborativo basado en ramas, Pull Requests y revisiones de código.

---

**Equipo Los Mueganos**
- Carol Guadalupe Rios Rios
- Juana Jaqueline Camarillo Olaez
- Princes Rocio Guerrero Sánchez