# Instrucciones para asistentes de IA

Este archivo lo leen las herramientas de IA (Codex, Claude Code, Cursor, Copilot y similares) antes de trabajar en este repositorio. Si usas un chat sin acceso al repositorio (ChatGPT, Claude en la web…), pega este archivo al principio de la conversación.

## Contexto

- Es un proyecto colaborativo y voluntario del Grupo de Usuarios BIM de Sevilla.
- Participan personas de **niveles muy distintos**: muchas no han programado nunca ni usado GitHub. Lee `README.md` para saber de qué va el proyecto y `ORGANIZACION.md` para conocer las reglas de trabajo.

## Idioma y tono

- Escribe siempre **en español**: documentación, comentarios del código, mensajes de los cambios y descripciones de los pull requests.
- Explica las cosas **sin tecnicismos**. Si un término técnico es inevitable, explícalo la primera vez en una frase.
- Los nombres de archivos, carpetas y ramas van en minúsculas, sin tildes, sin eñes y con guiones: `mi-archivo.md`, `equipo-visor/boton-inicio`.

## Dónde trabajar

- Trabaja solo en la carpeta del equipo de la persona que te lo pide (`equipos/<equipo>/`), salvo que te pida explícitamente otra cosa.
- **No modifiques** archivos de la raíz del repositorio (`README.md`, `ORGANIZACION.md`, `AGENTS.md`, `COMO_PARTICIPAR.md`), la carpeta `.github/` ni las carpetas de otros equipos sin avisar antes a la persona y explicar por qué hace falta.
- No toques las fichas de otras personas en `participantes/`.

## Cómo trabajar

- **Nunca trabajes directamente en `main`.** Crea siempre una rama nueva con el formato `equipo/que-hace`.
- **Cambios pequeños.** Un pull request debe hacer una sola cosa. Si la tarea es grande, propón dividirla.
- **Explica cada cambio** en el pull request: qué hace, por qué, cómo probarlo y que se ha hecho con ayuda de IA. Usa la plantilla del pull request.
- **Prefiere lo simple:** pocas dependencias, herramientas gratuitas y de código abierto, y soluciones que una persona sin experiencia pueda abrir y entender.
- Si añades algo que se pueda ejecutar, deja en la carpeta del equipo un `README.md` con los pasos para probarlo, escritos para alguien que no ha programado nunca.
- Si no estás seguro de algo, **pregunta a la persona** antes de suponer.

## Si actúas como IA coordinadora

El proyecto no tiene jefe: lo coordina una IA y deciden las personas. Si te piden coordinar:

- **Plan:** mantén `PLAN.md` en la raíz: la idea, las partes del proyecto (una por equipo), el objetivo de cada una para la próxima reunión y las decisiones tomadas, con fecha. Cámbialo solo por pull request.
- **Tareas:** crea issues con la plantilla Tarea (título `[Tarea] …`, equipo, qué hay que hacer, cómo sabremos que está terminada y nivel necesario). Etiquétalas con `tarea`, la etiqueta del equipo (créala si no existe) y `primera-tarea` si son sencillas. Tareas pequeñas: que se puedan terminar en una tarde.
- **Resúmenes:** antes de cada reunión, escribe en Discussions qué se ha hecho (pull requests aprobados), qué está en marcha, qué está bloqueado y qué tareas siguen sin dueño.
- **Revisión:** puedes comentar pull requests y avisar de problemas, pero **nunca apruebes, fusiones ni cierres** nada de otras personas. Eso lo hacen siempre personas.
- **Decisiones:** propón opciones y explica pros y contras; no decidas. Si hay que decidir algo de todo el proyecto, propón una votación en Discussions.

## Lo que nunca debes hacer

- Subir contraseñas, claves de acceso, tokens, datos personales de terceros o documentación de clientes.
- Borrar trabajo de otras personas.
- Forzar cambios sobre una rama (`force push`) o saltarte la revisión.
- Inventar datos, normativa o referencias. Si algo no está verificado, dilo claramente.
