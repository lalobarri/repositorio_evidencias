# 🎮 Propuesta de Capacitación: Git y GitHub para Programador Junior

## Equipo: MarketPlaze
- Miguel Angel Alvares Ibarra
- Pedro Uriel Perez Monzon
- Claudio Angel Huerta Ducoing

---

## 1. 🎯 Objetivo de Aprendizaje

Al finalizar la actividad, el Programador Junior será capaz de:

- Clonar repositorios remotos desde GitHub.
- Crear y administrar ramas de trabajo.
- Realizar commits con mensajes descriptivos.
- Sincronizar cambios con repositorios remotos.
- Resolver conflictos básicos de fusión.
- Crear y revisar Pull Requests.
- Colaborar en un equipo de desarrollo usando Git y GitHub.

---

## 2. 📖 Descripción de la Dinámica

La actividad será **colaborativa** y se trabajará sobre un **proyecto ficticio** llamado "MarketPlaze Web".

- Se organizará en **4 niveles progresivos** (misiones).
- Cada nivel deberá completarse antes de pasar al siguiente.
- El progreso se evaluará mediante **evidencias** (capturas de pantalla, commits y Pull Requests).
- El líder técnico revisará y aprobará cada Pull Request antes de continuar.
- Se usará la plataforma [learngitbranching.js.org](https://learngitbranching.js.org/?locale=es_ES) como punto de partida.

---

## 3. 🚀 Retos o Misiones

### 🟢 Nivel 1: Explorador Git
**Objetivo:** Familiarizarse con el entorno de trabajo.

- Instalar Git y configurar usuario y correo.
- Clonar el repositorio del proyecto.
- Identificar la estructura del proyecto.
- Ejecutar los siguientes comandos:
```bash
git clone https://github.com/equipo/proyecto.git
git status
git log --oneline
```

### 🔵 Nivel 2: Constructor de Funcionalidades
**Objetivo:** Aprender a trabajar con ramas y commits.

- Crear una rama propia:
```bash
git checkout -b feature_mi_modulo
```
- Modificar un archivo del proyecto.
- Registrar los cambios:
```bash
git add .
git commit -m "Implementa módulo asignado"
```

### 🟡 Nivel 3: Colaborador del Equipo
**Objetivo:** Sincronizar y colaborar con el equipo.

- Subir cambios al repositorio remoto:
```bash
git push origin feature_mi_modulo
```
- Sincronizar con el repositorio principal:
```bash
git fetch origin
git merge origin/main
```
- Resolver un conflicto sencillo.
- Crear un Pull Request hacia `main`.

### 🔴 Nivel 4: Revisor de Código
**Objetivo:** Aprender a revisar el trabajo de otros.

- Revisar el Pull Request de otro integrante.
- Agregar comentarios constructivos.
- Aprobar o solicitar cambios.
- Verificar que el proyecto funcione correctamente.

---

## 4. 📦 Evidencias de Aprendizaje

| Evidencia | Descripción |
|-----------|-------------|
| Captura 1 | Resultado de `git clone` exitoso |
| Captura 2 | Resultado de `git branch` con rama creada |
| Captura 3 | Resultado de `git log --oneline` con commits |
| Captura 4 | Pull Request creado en GitHub |
| Captura 5 | Revisión de Pull Request de un compañero |
| README | Archivo documentado con todos los pasos |

---

## 5. 📊 Criterios de Evaluación

| Criterio | Valor |
|----------|-------|
| Configuración correcta de Git | 10% |
| Uso correcto de ramas | 20% |
| Commits con mensajes descriptivos | 20% |
| Pull Requests realizados | 20% |
| Revisión de código de compañeros | 15% |
| Evidencias entregadas | 15% |

---

## 6. 💡 Preguntas de Reflexión

**¿Qué ventajas ofrece Git frente a guardar múltiples versiones manualmente?**
Git mantiene un historial completo de cambios, permite revertir errores fácilmente, ocupa menos espacio y facilita el trabajo en equipo sin riesgo de perder información.

**¿Por qué es importante trabajar mediante ramas?**
Las ramas permiten desarrollar funcionalidades de forma aislada sin afectar el código estable del proyecto. Cada integrante trabaja en su propia rama y solo se integra al proyecto cuando el código está revisado y aprobado.

**¿Qué beneficios aportan los Pull Requests?**
Los Pull Requests permiten revisar el código antes de integrarlo, detectar errores, compartir conocimiento entre el equipo y mantener un historial documentado de todos los cambios realizados.

**¿Cómo puede un líder técnico verificar que todos contribuyen?**
Mediante el comando `git shortlog -sn`, la sección **Insights → Contributors** en GitHub, y revisando el historial de commits y Pull Requests de cada integrante.

**¿Qué habilidades desarrolla un programador al usar Git y GitHub?**
Desarrolla habilidades técnicas como control de versiones, manejo de ramas y resolución de conflictos, y habilidades de colaboración como comunicación efectiva, revisión de código y trabajo en equipo organizado.

---

## 7. 🏆 Desafío Extra: Herramientas Complementarias

| Herramienta | Descripción |
|-------------|-------------|
| **GitHub Projects** | Tablero visual para gestionar tareas del equipo |
| **GitHub Issues** | Sistema para reportar bugs y proponer mejoras |
| **GitHub Actions** | Automatización de pruebas y despliegues (CI/CD) |
| **GitLab** | Plataforma alternativa con funciones similares a GitHub |
| **Jira** | Gestión de proyectos con metodologías ágiles (Scrum/Kanban) |
| **Azure DevOps** | Suite completa de herramientas para desarrollo empresarial |

Estas herramientas mejoran la colaboración al centralizar la comunicación, automatizar procesos repetitivos y dar visibilidad del progreso a todo el equipo.

---

## 🚀 Meta Final
Diseñar una experiencia de aprendizaje que permita a un Programador Junior adquirir las competencias básicas necesarias para integrarse exitosamente a un equipo profesional de desarrollo de software que utiliza Git y GitHub.