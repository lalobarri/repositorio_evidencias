# Propuesta de Capacitación: Git y GitHub para Programador Junior

## Nombre del Proyectoo

### BakerySys

---

# Descripción del Proyecto

BakerySys es una solución digital diseñada para panaderías y negocios dedicados a la elaboración y venta de productos horneados. Su propósito es automatizar y centralizar la gestión de inventario, ventas y materias primas, reduciendo errores derivados de procesos manuales y mejorando la toma de decisiones mediante reportes automatizados.

La aplicación permite registrar productos terminados, controlar existencias en tiempo real, administrar materias primas, generar alertas de reabastecimiento y elaborar reportes de ventas por diferentes periodos de tiempo.

### Funcionalidades principales

* Registro de productos terminados.
* Gestión de materias primas.
* Control de inventario en tiempo real.
* Registro de ventas.
* Alertas de reorden.
* Generación de reportes exportables.
* Administración de usuarios mediante roles.

### Tecnologías utilizadas

* Frontend: React
* Backend: Node.js
* Base de Datos: PostgreSQL
* Control de Versiones: Git y GitHub

---

# 1. Objetivo de Aprendizaje

Al finalizar la capacitación, el Programador Junior será capaz de:

* Clonar repositorios desde GitHub.
* Configurar Git en su entorno local.
* Comprender la estructura general del proyecto BakerySys.
* Crear y administrar ramas de desarrollo.
* Registrar cambios mediante commits descriptivos siguiendo buenas prácticas.
* Sincronizar cambios con repositorios remotos.
* Resolver conflictos de integración.
* Crear Pull Requests correctamente documentados.
* Participar en revisiones de código.
* Trabajar colaborativamente dentro de un equipo de desarrollo ágil.

---

# 2. Descripción de la Dinámica

## Modalidad

La actividad será colaborativa y se desarrollará en equipos de dos a cuatro integrantes, simulando el entorno de trabajo utilizado por el equipo de desarrollo de BakerySys.

## Metodología

La capacitación se realizará en dos etapas:

### Etapa 1: Fundamentos de Git

Los participantes utilizarán la plataforma Learn Git Branching para comprender conceptos básicos como:

* Commits
* Branches
* Merge
* Rebase
* Pull Requests

### Etapa 2: Aplicación Práctica

Posteriormente, los participantes trabajarán directamente sobre el repositorio de BakerySys, realizando actividades similares a las que desarrolla diariamente el equipo de trabajo.

## Evaluación del progreso

El avance será evaluado mediante:

* Historial de commits.
* Ramas creadas.
* Pull Requests realizados.
* Resolución de conflictos.
* Revisiones de código efectuadas.
* Evidencias entregadas.

---

# 3. Retos o Misiones

## Nivel 1 – Explorador Git

### Objetivo

Conocer la estructura del proyecto y configurar el entorno de trabajo.

### Actividades

1. Instalar Git.
2. Configurar usuario y correo.

```bash
git config --global user.name "Nombre Apellido"
git config --global user.email "correo@ejemplo.com"
```

3. Clonar el repositorio BakerySys.

```bash
git clone https://github.com/empresa/BakerySys.git
```

4. Analizar la estructura del proyecto.
5. Ejecutar la aplicación localmente.
6. Identificar los módulos:

* Productos
* Inventario
* Ventas
* Reportes
* Usuarios

### Evidencia

Captura del proyecto ejecutándose correctamente.

---

## Nivel 2 – Constructor de Funcionalidades

### Objetivo

Aprender el flujo de trabajo mediante ramas.

### Actividades

1. Crear una rama de trabajo.

```bash
git checkout -b feature/documentacion-productos
```

2. Actualizar el README agregando información sobre el módulo de productos.
3. Verificar cambios.

```bash
git status
```

4. Registrar cambios.

```bash
git add .
git commit -m "docs: actualización documentación módulo productos"
```

5. Realizar al menos tres commits independientes.

### Evidencia

Historial de commits mostrando los cambios realizados.

---

## Nivel 3 – Gestor de Inventario

### Objetivo

Trabajar sobre una funcionalidad relacionada con el inventario.

### Actividades

1. Crear la rama:

```bash
feature/alertas-stock
```

2. Agregar documentación sobre:

* Umbrales mínimos.
* Alertas de reorden.
* Actualización automática de inventario.

3. Realizar commits progresivos.

### Evidencia

Captura del historial de commits.

---

## Nivel 4 – Colaborador del Equipo

### Objetivo

Aprender a integrar cambios de otros desarrolladores.

### Actividades

1. Obtener cambios recientes.

```bash
git fetch origin
git pull origin main
```

2. Resolver un conflicto preparado por el instructor.
3. Registrar la solución.

```bash
git commit -m "fix: resolución de conflicto en README"
```

### Evidencia

Captura antes y después de resolver el conflicto.

---

## Nivel 5 – Entrega Profesional

### Objetivo

Utilizar Pull Requests para integrar cambios.

### Actividades

1. Subir la rama.

```bash
git push origin feature/alertas-stock
```

2. Crear Pull Request.
3. Incluir:

* Descripción.
* Archivos modificados.
* Evidencias.
* Impacto del cambio.

### Evidencia

Captura del Pull Request creado.

---

## Nivel 6 – Revisor de Código

### Objetivo

Participar en la revisión colaborativa.

### Actividades

1. Revisar un Pull Request de otro compañero.
2. Analizar los cambios.
3. Dejar comentarios de mejora.
4. Aprobar o solicitar cambios.

### Evidencia

Captura de la revisión realizada.

---

# 4. Evidencias de Aprendizaje

| Nivel   | Evidencia                               |
| ------- | --------------------------------------- |
| Nivel 1 | Proyecto clonado y ejecutándose         |
| Nivel 2 | Historial de commits                    |
| Nivel 3 | Rama de inventario y commits            |
| Nivel 4 | Resolución de conflicto                 |
| Nivel 5 | Pull Request documentado                |
| Nivel 6 | Revisión de código realizada            |
| General | README actualizado y video demostrativo |

---

# 5. Criterios de Evaluación

| Criterio                  | Excelente (4)                      | Bueno (3)                     | Regular (2)              | Insuficiente (1)        |
| ------------------------- | ---------------------------------- | ----------------------------- | ------------------------ | ----------------------- |
| Configuración y clonación | Configura y ejecuta sin errores    | Presenta mínimos errores      | Requiere apoyo frecuente | No logra completar      |
| Manejo de ramas           | Uso correcto y autónomo            | Pequeños errores              | Requiere apoyo           | No comprende el proceso |
| Calidad de commits        | Claros y descriptivos              | Aceptables                    | Poco descriptivos        | Incorrectos             |
| Resolución de conflictos  | Correcta y autónoma                | Correcta con apoyo mínimo     | Requiere mucha ayuda     | No logra resolver       |
| Pull Request              | Completo y profesional             | Completo con detalles menores | Incompleto               | No realizado            |
| Revisión de código        | Comentarios útiles y fundamentados | Comentarios básicos           | Revisión superficial     | No participa            |

### Escala

* 22 – 24 puntos: Excelente
* 18 – 21 puntos: Bueno
* 14 – 17 puntos: Satisfactorio
* Menos de 14 puntos: Requiere reforzamiento

---

# Preguntas de Reflexión

## ¿Qué ventajas ofrece Git frente a guardar múltiples versiones de un archivo manualmente?

Git permite mantener un historial completo y organizado de cambios, facilitando la recuperación de versiones anteriores y el trabajo colaborativo. A diferencia del almacenamiento manual de múltiples copias de archivos, Git evita duplicidades y mejora la trazabilidad de cada modificación realizada.

## ¿Por qué es importante trabajar mediante ramas?

Las ramas permiten desarrollar nuevas funcionalidades o corregir errores sin afectar la versión estable del proyecto. Esto facilita el trabajo simultáneo de varios desarrolladores y reduce riesgos durante el desarrollo.

## ¿Qué beneficios aportan los Pull Requests en un equipo de desarrollo?

Los Pull Requests permiten revisar el código antes de integrarlo al proyecto principal, favoreciendo la detección temprana de errores, el intercambio de conocimientos y el mantenimiento de estándares de calidad.

## ¿Cómo puede un líder técnico verificar que todos los integrantes están contribuyendo al proyecto?

Puede analizar el historial de commits, Pull Requests, revisiones de código, Issues asignados y métricas de contribución disponibles en GitHub.

## ¿Qué habilidades técnicas y de colaboración desarrolla un programador al utilizar Git y GitHub?

Desarrolla competencias relacionadas con control de versiones, gestión de cambios, resolución de conflictos, documentación, comunicación técnica, trabajo colaborativo y metodologías ágiles.

---

# 6. Desafío Extra – Herramientas Complementarias

## GitHub Projects

Permite organizar tareas mediante tableros Kanban y visualizar el progreso del desarrollo de BakerySys.

## GitHub Issues

Facilita la gestión de errores, solicitudes de mejora y nuevas funcionalidades.

## GitHub Actions

Automatiza pruebas, compilaciones y despliegues mediante integración continua.

## GitLab

Alternativa a GitHub que integra control de versiones, CI/CD y administración de proyectos.

## Jira

Herramienta ampliamente utilizada para la gestión de proyectos ágiles mediante historias de usuario, épicas y sprints.

## Azure DevOps

Plataforma integral que ofrece repositorios Git, pipelines de integración continua, tableros ágiles y herramientas de despliegue.

Estas herramientas fortalecen la colaboración, organización y automatización de los procesos de desarrollo de software.

---

# 7. Meta Final

Diseñar una experiencia de aprendizaje que permita al Programador Junior adquirir las competencias necesarias para integrarse exitosamente al equipo de desarrollo de BakerySys.

Al finalizar la capacitación, el participante deberá ser capaz de colaborar activamente en el mantenimiento y evolución del sistema, utilizando Git y GitHub como herramientas fundamentales para gestionar funcionalidades relacionadas con inventario, ventas, reportes, productos y administración de usuarios.

---

# Conclusión

La presente propuesta busca que el Programador Junior no solo aprenda comandos de Git y GitHub, sino que experimente un flujo de trabajo similar al utilizado en entornos profesionales. Mediante actividades progresivas relacionadas con BakerySys, el participante desarrollará habilidades técnicas y colaborativas esenciales para integrarse de manera efectiva a un equipo moderno de desarrollo de software.
