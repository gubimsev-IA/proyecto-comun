# Cómo participar — GitHub desde cero

Esta guía es para quien no ha usado nunca GitHub. No hace falta instalar nada: todo se hace desde el navegador.

Si te atascas en cualquier paso, pregunta. Nadie nace sabiendo y aquí nadie se queda atrás.

---

## 1. Qué es GitHub, en un minuto

GitHub es **el entorno común de datos (CDE) de nuestro proyecto**. Si has trabajado con un CDE en BIM, ya entiendes la idea:

- Hay una **versión buena** del proyecto, que es la que vale.
- Nadie la modifica directamente: cada uno trabaja en lo suyo y lo **envía a revisión**.
- Alguien lo **revisa y lo aprueba**, y entonces pasa a la versión buena.
- **Todo queda registrado:** quién cambió qué, cuándo y por qué. Y todo se puede deshacer.

### Las palabras que vas a oír

| En GitHub se llama | En BIM sería | Qué es |
|---|---|---|
| **Repositorio** (repo) | El CDE del proyecto | La carpeta compartida con todo el proyecto y su historial |
| **main** | Estado "Publicado" | La versión buena del proyecto |
| **Rama** (branch) | Estado "En curso" | Una copia donde haces tus cambios sin tocar la versión buena |
| **Commit** | Guardar una revisión | Un cambio guardado, con un mensaje que explica qué hiciste |
| **Pull request** (PR) | Enviar a revisión | "He terminado esto, ¿lo revisas y lo incorporamos?" |
| **Merge** | Aprobar y publicar | Aceptar el cambio: pasa a la versión buena |
| **Issue** | Incidencia BCF | Una tarea, una idea o un problema, con su conversación |
| **Fork** | Copia de trabajo propia | Tu copia personal del proyecto, si aún no eres miembro |

### El ciclo de cualquier aportación

```
  1. Abro el archivo        2. Hago mi cambio         3. Lo envío a revisión
     en la web          →      en una rama        →      (pull request)
                                                              │
  6. Ya está publicado  ←   5. El responsable lo   ←   4. Alguien lo revisa
     en main                   aprueba (merge)            y comenta
```

Da igual que cambies una coma o que añadas una aplicación entera: el ciclo es siempre el mismo.

---

## 2. Crear tu cuenta

1. Entra en **https://github.com/signup**.
2. Pon tu correo, una contraseña y un nombre de usuario. **Elige un nombre de usuario reconocible** (por ejemplo `mariagarcia-arq`), porque es como te verá el resto del grupo.
3. GitHub te mandará un código al correo para confirmar la cuenta.
4. Te preguntará cosas como para qué lo vas a usar: puedes saltártelas.

Es gratis y no necesitas ningún plan de pago.

---

## 3. Tu primera aportación: tu ficha de participante

Vas a crear un archivo con tu presentación. Es la mejor forma de aprender el ciclo, porque **cada persona crea su propio archivo**, así que es imposible chocar con los cambios de otra persona.

### Opción rápida: con el enlace directo

Si en la sesión te han dado un enlace o un QR para la ficha, ábrelo: te lleva directamente al paso 4 de abajo, con la plantilla ya escrita. Solo tienes que cambiar el nombre del archivo y rellenarla.

### Opción paso a paso

1. **Entra en el repositorio** del proyecto (la dirección está en el grupo y en el QR de la sesión). Comprueba que has iniciado sesión: tu foto debe salir arriba a la derecha.

2. **Abre la plantilla.** Entra en la carpeta `participantes` y haz clic en `_plantilla.md`. Verás algo así:

   ```
   # Nombre Apellido
   - **Usuario de GitHub:** @...
   ...
   ```

   Pulsa el botón de **copiar** (icono de dos cuadraditos, arriba a la derecha del contenido) para copiarla entera.

3. **Crea tu archivo.** Vuelve a la carpeta `participantes` (pulsa su nombre en la ruta de arriba) → botón **Add file** → **Create new file**.

4. **Ponle nombre y contenido.**
   - En el cuadro del nombre escribe `nombre-apellido.md`, en minúsculas, sin tildes ni espacios. Por ejemplo: `maria-garcia.md`.
   - En el cuadro grande pega la plantilla y rellénala con tus datos. Lo que va entre `<!--` y `-->` son notas de ayuda: puedes borrarlas.

5. **Envíalo a revisión.** Pulsa el botón verde de arriba a la derecha, **Commit changes…**. Se abre una ventana llamada **Propose changes**:
   - Como aún no eres miembro del proyecto, GitHub te avisará de que va a crear **una copia propia (fork)** para ti. **Es lo normal**: acepta.
   - El mensaje ya viene escrito (`Create maria-garcia.md`). Puedes dejarlo así.
   - Pulsa el botón verde **Propose changes**.

6. **Crea el pull request.** Se abre la página **Open a pull request**. La descripción trae unas preguntas (Qué cambia, Por qué…): para la ficha no hace falta rellenarlas ni borrarlas. Pulsa el botón verde **Create pull request**.

   Si aparece algún aviso de GitHub encima (por ejemplo, «Try the Overview page»), ciérralo con **Not now** o **Dismiss**: no afecta a nada.

**¡Hecho!** Acabas de hacer tu primer pull request. Ahora un responsable lo revisará y lo aprobará. Recibirás un correo cuando pase.

### ¿Y si me equivoco?

No pasa nada. Mientras no esté aprobado, puedes entrar en tu pull request (pestaña **Pull requests** del repositorio), ir a la pestaña **Files changed**, pulsar los tres puntos del archivo → **Edit file** y corregirlo. Si es un desastre, ciérralo y empieza de nuevo: no deja rastro en la versión buena.

---

## 4. Pedirte una tarea (issues)

Los **issues** son como incidencias BCF: cada uno es una tarea, una idea o un problema, con su conversación debajo.

**Las tareas las crea la IA coordinadora** a partir del plan del proyecto. Tú no tienes que crearlas: solo elegir una y pedírtela.

1. En el repositorio, pestaña **Issues**. Cada línea es una tarea.
2. **Haz clic en la etiqueta de tu equipo** (las cápsulas de colores junto al título): solo verás las tareas de tu equipo. La etiqueta `primera-tarea` marca las más sencillas.
3. Abre la tarea que te apetezca y léela: qué hay que hacer y cómo sabremos que está terminada.
4. Baja hasta el cuadro **Add a comment**, escribe **Me la pido** y pulsa el botón verde **Comment**.
   - **Ojo:** el botón de al lado, **Close with comment** (o **Close issue**), **cierra la tarea**. No es el que buscas.
5. El responsable de tu equipo te la asignará. Si tienes dudas sobre la tarea, pregúntalas en ese mismo hilo: así quedan guardadas con ella.

**Para practicar** hay una tarea de práctica abierta: «[Tarea] Práctica: pídete esta tarea». Pídetela sin miedo, aunque otros ya lo hayan hecho.

### Si quieres crear tú una tarea, una idea o un problema

1. Pestaña **Issues** → botón **New issue**.
2. Elige el tipo: **Tarea** (algo concreto que hacer), **Idea** (una propuesta) o **Problema** (algo que no funciona).
3. El formulario se abre en una ventana. Rellena **todos los campos marcados con \***. En una tarea son: el título (completa el que empieza por `[Tarea]`), el **Equipo** (su nombre, tal como aparece en su carpeta, por ejemplo `visor`), **Qué hay que hacer**, **Cómo sabremos que está terminada** y el **Nivel necesario**.
4. Pulsa **Create**. La lista puede tardar unos segundos en mostrar el issue nuevo: no lo crees dos veces.

También puedes pedírselo a la IA: «Crea en el repositorio gubimsev-IA/proyecto-comun una tarea para el equipo visor que consista en…».

**Para apoyar** una idea sin escribir nada, pulsa el emoji 👍 de su primer mensaje: así votamos.

---

## 5. Cuando ya seas miembro del equipo

Cuando te invitemos a la organización (te llegará un correo: **acéptalo**), ya no necesitarás copia propia. El ciclo cambia muy poco:

1. Abres o creas el archivo en la web, como antes.
2. Al pulsar **Commit changes…**, GitHub te ofrece dos opciones. Elige siempre:
   **Create a new branch for this commit and start a pull request**
   (la otra, escribir directamente en `main`, está bloqueada para que nadie rompa nada sin querer).
3. Ponle a la rama un nombre que explique el cambio, por ejemplo `equipo-visor/boton-inicio`.
4. Crea el pull request como antes.

**Regla de oro:** una rama por cada cambio. La rama dura lo que dura ese cambio y se borra al aprobarse. No hay ramas permanentes por equipo: cada equipo tiene su **carpeta**.

---

## 6. Revisar y aprobar (para responsables)

1. Pestaña **Pull requests** → abre el que quieras revisar.
2. Pestaña **Files changed**: verás en verde lo añadido y en rojo lo quitado.
3. Si quieres comentar una línea concreta, pasa el ratón por encima y pulsa el **+** azul.
4. Arriba a la derecha → **Review changes** →
   - **Approve** si está bien.
   - **Request changes** si hay que corregir algo (explica qué, con amabilidad).
5. Con la aprobación, vuelve a la pestaña **Conversation** → **Merge pull request** → **Confirm merge**.
6. Pulsa **Delete branch** si aparece: la rama ya no hace falta.

Al revisar, piensa: ¿se entiende?, ¿está en la carpeta de su equipo?, ¿rompe algo de otro equipo? Si dudas, pregunta en el propio pull request.

---

## 7. El siguiente nivel: trabajar con IA

Cuando te sientas cómodo con la web, puedes trabajar desde tu ordenador con una IA que hace por ti la parte de GitHub:

- **Claude Code**, **Codex** u otras herramientas parecidas pueden descargar el proyecto, crear la rama, hacer los cambios y abrir el pull request. Basta con pedírselo en lenguaje normal:
  > "Crea una rama, añade en la carpeta de mi equipo una página que haga X y abre un pull request explicando el cambio".
- **GitHub Desktop** (https://desktop.github.com) es una aplicación gratuita que hace lo mismo con botones, si prefieres controlarlo tú.

En la raíz del proyecto hay un archivo `AGENTS.md` con las normas del grupo para las IA. Las herramientas lo leen solas, así que tu IA trabajará con las mismas reglas que la de los demás.

**Importante:** tú eres responsable de lo que envías, aunque lo haya escrito la IA. Antes de enviar algo a revisión, léelo y asegúrate de que lo entiendes.

---

## 8. Límites del plan gratuito de GitHub

Usamos el plan gratuito con un repositorio público. Datos de [github.com/pricing](https://github.com/pricing) y [docs.github.com](https://docs.github.com), consultados el 27-11-2026:

| Qué | Límite |
|---|---|
| Personas y repositorios | Ilimitados |
| GitHub Actions (automatizaciones) | Gratis en repositorios públicos con los runners estándar. En privados, 2.000 minutos al mes aproximadamente (12 $ de uso incluido) |
| Paquetes y artefactos | 500 MB |
| Subir un archivo desde el navegador | Máximo 25 MB por archivo |
| Tamaño de un archivo | Aviso a partir de 50 MB; GitHub rechaza los de más de 100 MB |
| Tamaño del repositorio | Lo ideal, menos de 1 GB; muy recomendable, menos de 5 GB |
| Web con GitHub Pages | Solo en repositorios públicos; sitio de hasta 1 GB y unos 100 GB de tráfico al mes |
| Codespaces (programar en la nube) | 120 horas y 15 GB al mes en cuentas personales; las organizaciones gratuitas no tienen cuota |

**Lo que más nos afecta:**

- **Los modelos BIM pesados (RVT, IFC grandes, nubes de puntos) no se suben a GitHub.** Se guardan en una carpeta compartida y en el repositorio se pone el enlace. Para pruebas, usad modelos pequeños.
- **El plan gratuito solo permite proteger ramas, CODEOWNERS y revisores en repositorios públicos.** Por eso el nuestro es público: nunca subáis nada confidencial.

## Preguntas frecuentes

**¿Puedo romper algo?**
No. La versión buena está protegida: nada entra sin revisión. Y cualquier cambio aprobado se puede deshacer.

**¿Tengo que saber programar?**
No. Ideas, pruebas, documentación, casos reales y criterio profesional valen tanto como el código.

**¿Cuánto tiempo tengo que dedicarle?**
El que quieras. Es voluntario. Una tarde al mes ya es mucho.

**¿Qué pasa si dejo una tarea a medias?**
Avisa en el issue ("No voy a poder seguir con esto") y otra persona la recoge. Sin dramas.

**¿Dónde pregunto?**
Las dudas de trabajo, en el issue o pull request correspondiente, para que la respuesta le sirva a todos. Las dudas generales, en la pestaña **Discussions** del repositorio o en el grupo de siempre.
