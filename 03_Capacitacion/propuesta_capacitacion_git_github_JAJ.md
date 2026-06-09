# Propuesta de Capacitación: Git y GitHub para Programador Junior

---

## 1. Objetivo de Aprendizaje

Al finalizar esta actividad, el Programador Junior será capaz de:

- Clonar un repositorio remoto en su máquina local.
- Identificar la estructura de un proyecto y ejecutarlo localmente.
- Crear y gestionar ramas de trabajo (`git branch`, `git checkout`).
- Registrar cambios mediante commits con mensajes descriptivos.
- Sincronizar cambios con el repositorio remoto (`git push`, `git pull`).
- Resolver conflictos de fusión simples.
- Crear Pull Requests y participar en revisiones de código.
- Revisar, aprobar o solicitar cambios en el PR de un compañero.

---

## 2. Descripción de la Dinámica

### Modalidad

La actividad es **colaborativa** y se realiza en equipos de 2 a 4 personas, simulando un equipo de desarrollo real dentro de la empresa.

### Proyecto

Se trabajará sobre un **proyecto ficticio pero funcional**: una aplicación web sencilla (por ejemplo, una lista de tareas en HTML/CSS/JavaScript o una API básica en Python), alojada en un repositorio de GitHub creado específicamente para la capacitación.

### Estructura

La actividad está organizada en **4 niveles progresivos** (misiones), donde cada nivel introduce nuevos conceptos y habilidades. El participante debe completar cada nivel antes de avanzar al siguiente.

### Evaluación del Progreso

El líder técnico (o facilitador) verificará el progreso mediante:

- Revisión del historial de commits en GitHub.
- Inspección de las ramas creadas y los Pull Requests abiertos.
- Revisión de las evidencias entregadas al finalizar cada nivel.

---

## 3. Retos o Misiones

### Nivel 1 — Explorador Git 🗺️

**Objetivo:** Familiarizarse con el entorno y el repositorio.

**Actividades:**

1. Instalar Git en la máquina local y configurar nombre de usuario y correo:
   ```bash
   git config --global user.name "Tu Nombre"
   git config --global user.email "tucorreo@ejemplo.com"
   ```
2. Clonar el repositorio de capacitación:
   ```bash
   git clone https://github.com/empresa/proyecto-capacitacion.git
   ```
3. Explorar la estructura de archivos y carpetas del proyecto.
4. Ejecutar la aplicación localmente siguiendo el archivo `README.md`.
5. Verificar el historial de commits existente:
   ```bash
   git log --oneline
   ```

**Evidencia requerida:** Captura de pantalla del repositorio clonado y la aplicación ejecutándose en el navegador o terminal.

---

### Nivel 2 — Constructor de Funcionalidades 🔨

**Objetivo:** Aprender el flujo básico de trabajo con ramas y commits.

**Actividades:**

1. Crear una rama personal con el formato `feature/nombre-apellido`:
   ```bash
   git checkout -b feature/juan-garcia
   ```
2. Realizar una modificación en el proyecto (por ejemplo, agregar una nueva tarea o sección en la aplicación).
3. Verificar los cambios realizados:
   ```bash
   git status
   git diff
   ```
4. Registrar los cambios con un commit descriptivo:
   ```bash
   git add .
   git commit -m "feat: agrega sección de contacto al proyecto"
   ```
5. Realizar al menos 3 commits separados con cambios distintos, usando mensajes claros y en formato convencional (`feat:`, `fix:`, `docs:`).

**Evidencia requerida:** Captura del historial de commits (`git log --oneline`) mostrando al menos 3 commits propios.

---

### Nivel 3 — Colaborador del Equipo 🤝

**Objetivo:** Sincronizar trabajo con el repositorio remoto y manejar conflictos.

**Actividades:**

1. Subir la rama personal al repositorio remoto:
   ```bash
   git push origin feature/juan-garcia
   ```
2. Actualizar la rama local con los últimos cambios de `main`:
   ```bash
   git fetch origin
   git merge origin/main
   ```
3. Resolver el conflicto de fusión que el facilitador habrá preparado intencionalmente en el archivo `README.md` o en el archivo principal del proyecto.
4. Una vez resuelto el conflicto, registrar el merge con un commit:
   ```bash
   git add .
   git commit -m "fix: resuelve conflicto en README con rama main"
   ```
5. Abrir un **Pull Request** en GitHub desde la rama personal hacia `main`, incluyendo:
   - Título descriptivo.
   - Descripción de los cambios realizados.
   - Al menos un compañero asignado como revisor.

**Evidencia requerida:** Captura del Pull Request abierto en GitHub con la descripción completa y el revisor asignado.

---

### Nivel 4 — Revisor de Código 🔍

**Objetivo:** Participar activamente en la revisión de código de otro desarrollador.

**Actividades:**

1. Revisar el Pull Request asignado por un compañero.
2. Inspeccionar los cambios en la pestaña **Files changed** de GitHub.
3. Dejar al menos **2 comentarios de revisión** en líneas específicas del código (sugerencias, preguntas o mejoras).
4. Según la calidad del código revisado:
   - Si cumple los criterios → **Aprobar el PR** ("Approve").
   - Si requiere correcciones → **Solicitar cambios** ("Request changes") explicando qué debe corregirse.
5. Una vez aprobado el propio PR, colaborar en el merge hacia `main`.

**Evidencia requerida:** Captura de la revisión realizada en GitHub, mostrando los comentarios dejados y la decisión tomada (aprobado o cambios solicitados).

---

## 4. Evidencias de Aprendizaje

| Nivel | Evidencia Requerida |
|-------|---------------------|
| Nivel 1 | Captura del repositorio clonado y la app ejecutándose localmente |
| Nivel 2 | Captura del `git log --oneline` con al menos 3 commits propios |
| Nivel 3 | Captura del Pull Request abierto en GitHub con descripción y revisor asignado |
| Nivel 4 | Captura de la revisión de código con comentarios y decisión tomada |
| General | Historial de commits visible en GitHub con mensajes claros y convencionales |
| Desafío Extra | Breve documento o sección adicional en el README explicando las herramientas investigadas |

---

## 5. Criterios de Evaluación

| Criterio | Excelente (4) | Satisfactorio (3) | En Desarrollo (2) | Insuficiente (1) |
|----------|---------------|-------------------|-------------------|------------------|
| **Clonación y configuración** | Configura Git correctamente y clona sin errores | Clona con mínima ayuda | Requiere guía constante | No logra clonar el repositorio |
| **Gestión de ramas** | Crea y nombra ramas correctamente siguiendo la convención | Crea ramas con pequeños errores de nomenclatura | Crea la rama con ayuda | No crea ramas independientes |
| **Calidad de commits** | Mensajes claros, descriptivos y en formato convencional | Mensajes aceptables pero inconsistentes | Mensajes poco descriptivos | Mensajes vacíos o sin sentido |
| **Resolución de conflictos** | Resuelve el conflicto de forma autónoma y correcta | Resuelve con mínima orientación | Resuelve con apoyo constante | No logra resolver el conflicto |
| **Pull Request** | PR completo con título, descripción y revisor asignado | PR con información parcial | PR abierto pero incompleto | No abre el Pull Request |
| **Revisión de código** | Revisión detallada con comentarios útiles y decisión justificada | Revisión con comentarios básicos | Revisión superficial | No realiza la revisión |
| **Colaboración** | Participa activamente, apoya al equipo y comunica avances | Participa de forma regular | Participación limitada | No interactúa con el equipo |

**Escala de calificación:**

- 25–28 puntos → Excelente
- 19–24 puntos → Satisfactorio
- 13–18 puntos → En Desarrollo
- Menos de 13 puntos → Requiere refuerzo

---

## 6. Preguntas de Reflexión

### 1. ¿Qué ventajas ofrece Git frente a guardar múltiples versiones de un archivo manualmente?

Git ofrece un sistema de control de versiones automatizado que registra cada cambio de forma precisa, indicando qué se modificó, quién lo hizo y cuándo. A diferencia de guardar archivos manualmente como `proyecto_v1`, `proyecto_v2_final`, `proyecto_FINAL_DEFINITIVO`, Git permite navegar el historial completo sin duplicar archivos, revertir cambios erróneos con un solo comando, comparar versiones fácilmente y trabajar en paralelo con otros desarrolladores sin sobrescribir el trabajo ajeno.

### 2. ¿Por qué es importante trabajar mediante ramas?

Las ramas permiten desarrollar nuevas funcionalidades o corregir errores de forma aislada, sin afectar el código estable del proyecto (usualmente en `main` o `master`). Esto significa que varios desarrolladores pueden trabajar simultáneamente en diferentes características sin interferirse entre sí. Si una rama resulta fallida, simplemente se descarta sin comprometer el resto del proyecto. Las ramas son la base del trabajo colaborativo en equipos de desarrollo modernos.

### 3. ¿Qué beneficios aportan los Pull Requests en un equipo de desarrollo?

Los Pull Requests crean un espacio formal de revisión antes de integrar código al proyecto principal. Sus principales beneficios son:

- **Revisión de calidad:** otro desarrollador verifica que el código sea correcto, legible y cumpla los estándares del equipo.
- **Detección de errores:** se identifican bugs o problemas de lógica antes de que lleguen a producción.
- **Transferencia de conocimiento:** los desarrolladores aprenden del código de sus compañeros.
- **Trazabilidad:** queda registrado quién aprobó cada cambio y por qué.
- **Colaboración estructurada:** fomenta la comunicación técnica entre integrantes del equipo.

### 4. ¿Cómo puede un líder técnico verificar que todos los integrantes están contribuyendo al proyecto?

Un líder técnico puede verificar las contribuciones a través de:

- El **historial de commits** en GitHub, que muestra quién realizó cada cambio y con qué frecuencia.
- La sección de **Contributors** en el repositorio, que resume las aportaciones de cada persona.
- La revisión de **Pull Requests** abiertos y cerrados por cada integrante.
- El uso de herramientas como **GitHub Projects** o **GitHub Issues**, donde se asignan tareas y se rastrea su avance.
- Gráficas de actividad disponibles en la pestaña **Insights** del repositorio.

### 5. ¿Qué habilidades técnicas y de colaboración desarrolla un programador al utilizar Git y GitHub?

**Habilidades técnicas:**

- Control de versiones y gestión del historial de un proyecto.
- Trabajo con ramas, merges y resolución de conflictos.
- Uso de la terminal y comandos Git.
- Comprensión del flujo de trabajo `feature branch` y `pull request`.
- Documentación técnica mediante archivos `README.md` y mensajes de commit.

**Habilidades de colaboración:**

- Comunicación efectiva mediante comentarios en Pull Requests e Issues.
- Revisión crítica y constructiva del código de otros.
- Responsabilidad y trazabilidad en las contribuciones propias.
- Adaptación a estándares y convenciones de equipo.
- Trabajo organizado bajo metodologías ágiles con herramientas de gestión integradas.

---

## 7. Desafío Extra — Herramientas Complementarias a Git y GitHub

Las empresas de desarrollo de software utilizan diversas herramientas que se integran con Git y GitHub para mejorar la colaboración, automatizar procesos y gestionar proyectos de manera más eficiente.

### GitHub Projects

Es un tablero Kanban integrado directamente en GitHub. Permite organizar Issues y Pull Requests en columnas como "Por hacer", "En progreso" y "Completado". Su principal ventaja es que toda la gestión del proyecto vive en el mismo lugar que el código, facilitando la visibilidad del equipo sin salir de GitHub.

### GitHub Issues

Sistema de seguimiento de tareas, errores y solicitudes de mejora. Cada Issue puede asignarse a un desarrollador, etiquetarse por categoría (bug, feature, documentation) y vincularse directamente a un Pull Request. Es la base para la comunicación técnica y la gestión de trabajo pendiente dentro del repositorio.

### GitHub Actions

Plataforma de integración y entrega continua (CI/CD) integrada en GitHub. Permite automatizar flujos de trabajo como ejecutar pruebas automáticas al abrir un Pull Request, desplegar la aplicación al hacer merge en `main`, o generar reportes de calidad de código. Reduce el trabajo manual y minimiza errores humanos en el proceso de entrega.

### GitLab

Plataforma alternativa a GitHub que ofrece, en un solo lugar, control de versiones, CI/CD, gestión de proyectos y registro de contenedores Docker. Es muy utilizada por empresas que prefieren instalar la herramienta en sus propios servidores (self-hosted) por razones de seguridad o privacidad.

### Jira

Herramienta de gestión de proyectos de Atlassian, ampliamente utilizada en equipos que trabajan con metodologías ágiles (Scrum, Kanban). Permite crear sprints, épicas, historias de usuario y tareas, y se integra con GitHub y GitLab para vincular commits y Pull Requests directamente a los tickets de trabajo. Es el estándar de facto en muchas empresas medianas y grandes.

### Azure DevOps

Plataforma de Microsoft que integra repositorios de código (Azure Repos), pipelines de CI/CD (Azure Pipelines), tableros de trabajo (Azure Boards) y gestión de artefactos (Azure Artifacts). Es especialmente popular en empresas que utilizan el ecosistema de Microsoft (Azure Cloud, .NET, Visual Studio) y permite gestionar todo el ciclo de vida del software desde una sola plataforma.

---

*Documento elaborado como propuesta de capacitación para el equipo de desarrollo.*  
*Fecha: Junio 2026*