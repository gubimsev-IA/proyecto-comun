# Retos para quien ya domina GitHub

¿Ya has hecho tu ficha y has ayudado a los de tu alrededor? Estos retos son tareas reales: lo que hagas se queda en el proyecto.

**Cómo funciona:**

1. Elige un reto y comenta en la pestaña **Issues** que lo coges (si no existe el issue, créalo con la plantilla "Tarea" y el título del reto), para que no lo haga otra persona a la vez.
2. Trabaja como quieras: en la web, con GitHub Desktop o con tu agente de IA (Claude Code, Codex…). El archivo `AGENTS.md` tiene las normas del proyecto para la IA.
3. Abre un pull request. Si está listo antes de las 18:35, lo enseñamos y lo aprobamos en directo.

Respeta las normas de `ORGANIZACION.md`: ramas cortas, cambios pequeños y explicados en lenguaje sencillo.

---

## ⭐ Reto 1 · Revisor de fichas

Revisa las fichas que van llegando (pestaña **Pull requests**) y deja comentarios amables si algo falla: nombre del archivo con tildes o mayúsculas, plantilla sin rellenar, archivo fuera de la carpeta `participantes`.

No hace falta tocar código. Es el reto más útil durante la sesión.

## ⭐⭐ Reto 2 · Comprobación automática de fichas

Crea una GitHub Action (`.github/workflows/`) que, en cada pull request, compruebe que los archivos nuevos de `participantes/`:

- Tienen un nombre en minúsculas, sin tildes ni espacios, terminado en `.md`.
- Contienen los apartados de la plantilla.

Si algo falla, que deje un comentario en el pull request explicando **en español sencillo** cómo arreglarlo.

## ⭐⭐ Reto 3 · Mapa del repositorio para principiantes

Crea `equipos/README.md` más visual o un diagrama (Mermaid, que GitHub dibuja solo) que explique cómo se organiza el repositorio y el ciclo de trabajo. Piensa en alguien que llega nuevo dentro de seis meses.

## ⭐⭐⭐ Reto 4 · Web de la galería de participantes

Publica con GitHub Pages una página sencilla que muestre a todos los participantes a partir de sus fichas, agrupados por equipo. Debe actualizarse sola cada vez que se aprueba una ficha nueva.

Pista: una Action que lea `participantes/*.md` y genere una página HTML estática. Deja en el pull request los pasos para activar Pages (lo tendrá que activar un administrador en **Settings → Pages**).

## ⭐⭐⭐ Reto 5 · De la lluvia de ideas al repositorio

Cuando termine la votación, exporta las ideas del Padlet (menú de los tres puntos → Exportar → CSV o PDF) y crea `ideas/sesion-2026-11-27/README.md` con todas las ideas ordenadas por votos y agrupadas por temas. Usar la IA para agruparlas está permitido, y es justo la gracia.

## ⭐⭐⭐⭐ Reto 6 · Estructura técnica del proyecto ganador

Con la idea ganadora y las partes del bloque 4, propón en un pull request:

- Qué tecnología usar (lo más sencilla y gratuita posible) y por qué.
- La estructura de carpetas de cada equipo.
- Un "hola mundo" mínimo que funcione y que cualquiera pueda abrir.

No hace falta que sea definitivo: es una propuesta para debatir en la próxima reunión.
