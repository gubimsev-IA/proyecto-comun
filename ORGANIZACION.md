# Cómo nos organizamos

Las reglas del juego, en una página. Si algo no funciona, se cambia: estas reglas también se proponen y se aprueban con un pull request.

---

## Principios

1. **Voluntario.** Cada persona aporta lo que puede, cuando puede. Nadie debe nada a nadie.
2. **A largo plazo.** No hay prisa. Preferimos avanzar poco y bien.
3. **Todos los niveles suman.** El criterio profesional, las pruebas y la documentación valen tanto como el código.
4. **Todo a la vista.** Lo que se decide y se hace queda en GitHub, para que cualquiera pueda incorporarse en cualquier momento.
5. **Pasos pequeños.** Muchos cambios pequeños son mejores que uno enorme: se revisan antes y se rompen menos cosas.
6. **Es un experimento.** Si sale algo útil, perfecto. Si no, habremos aprendido a construir juntos con IA.

---

## Quién es quién

```
                    PROYECTO COMÚN
                  Coordina: una IA
             Deciden: todas las personas
                          │
        ┌─────────────┬───┴─────────┬─────────────┐
     Equipo A      Equipo B      Equipo C      Equipo D
   (responsable) (responsable) (responsable) (responsable)
        │             │             │             │
     personas      personas      personas      personas
```

### La IA coordinadora

No hay jefe de proyecto: nadie tiene por qué cargar con la gestión. La coordinación la hace una IA que trabaja sobre este repositorio (por ejemplo, Claude Code o Codex con acceso a GitHub). Sus normas están en `AGENTS.md`, apartado «Si actúas como IA coordinadora».

- Mantiene el plan del proyecto al día (`PLAN.md`).
- Crea las tareas (issues) a partir del plan, con su equipo y su nivel.
- Antes de cada reunión, resume lo que se ha hecho y lo que está bloqueado.
- Revisa los pull requests y avisa de problemas, pero **no aprueba ni fusiona nada**: eso lo hacen siempre personas.

**La IA propone; las personas deciden.** Cualquier persona del grupo puede pedirle a la IA coordinadora que haga su trabajo; lo que produce entra, como todo, por pull request.

### Administración del repositorio

Paco mantiene la configuración técnica del repositorio (permisos, protección de `main`, invitaciones). No decide sobre el proyecto: eso es de todos.

### Responsable de equipo

- Organiza las tareas de su equipo: las crea, las reparte y las mantiene al día.
- Revisa y aprueba los cambios de su carpeta.
- Habla con los demás responsables cuando su trabajo afecta a otro equipo.
- Cuenta el avance de su equipo en las reuniones de seguimiento.

No hace falta ser quien más sabe. Hace falta tener ganas de organizar. El puesto se puede pasar a otra persona en cualquier momento.

### Participantes

Cada persona tiene un equipo principal y puede ayudar en otros. Según su experiencia, puede aportar como:

| Perfil | Para quién | Qué aporta |
|---|---|---|
| **Explorador** | Empiezo con la IA o con GitHub | Ideas, pruebas ("esto no funciona"), casos reales, revisión de textos |
| **Creador** | Uso la IA, pero no programo | Instrucciones, documentación y prototipos hechos con IA |
| **Desarrollador** | Programo o me atrevo | Código, revisión técnica y ayuda a los demás |

El perfil no es fijo: se sube solo, con el uso.

---

## Cómo se reparte el trabajo

### Equipos = carpetas

Cada equipo trabaja en su carpeta, dentro de `equipos/`. Así los equipos no se pisan entre ellos.

```
equipos/
├── nombre-equipo-a/
│   ├── README.md      ← qué hace el equipo, quién está y en qué anda
│   └── ...            ← su trabajo
└── nombre-equipo-b/
    └── ...
```

Si un cambio necesita tocar la carpeta de otro equipo, se avisa antes en un issue y se pide que lo revise su responsable.

### Tareas = issues

Todo trabajo empieza como un issue (pestaña **Issues**), con la plantilla **Tarea**. Así sabemos qué hay pendiente, quién lo hace y qué está terminado. Normalmente las crea la IA coordinadora a partir del plan; cualquiera puede proponer más.

- **Etiquetas:** cada tarea lleva la etiqueta de su equipo y, si es sencilla, `primera-tarea` para que la pueda coger alguien que empieza.
- **Coger una tarea:** se comenta "Me la pido" (botón **Comment**, no «Close») y el responsable la asigna.
- **Soltarla:** si no puedes seguir, avisa en el issue. No pasa nada.

### Cambios = ramas cortas + pull requests

1. **Una rama por cambio**, con nombre `equipo/que-hace`. Ejemplo: `visor/boton-inicio`.
2. La rama **dura poco**: días, no meses. Cuanto más dura, más difícil es juntarla después.
3. Al terminar, se abre un **pull request** que explica qué cambia y por qué.
4. El **responsable del equipo** (o quien designe) lo revisa y lo aprueba.
5. Una vez aprobado, se incorpora a `main` y **se borra la rama**.

**No hay ramas permanentes por equipo.** Es la tentación habitual y es un error: cada rama se va alejando de las demás y juntarlas al final es como coordinar modelos que nadie ha cruzado en meses.

**Nadie escribe directamente en `main`.** Está protegida: todo entra por pull request con al menos una aprobación.

---

## Reuniones

- **Reuniones de seguimiento:** alternadas con las sesiones habituales del grupo, en el FabLab de la ETSAS. Cada responsable cuenta en pocos minutos qué ha hecho su equipo, qué viene ahora y si está bloqueado en algo.
- **Entre reuniones:** cada equipo se organiza como quiera. Lo importante es que lo que se haga quede en GitHub.

## Comunicación

| Para… | Usa… |
|---|---|
| Avisos generales y convocatorias | El grupo de siempre |
| Hablar de una tarea concreta | Los comentarios del issue |
| Comentar un cambio | Los comentarios del pull request |
| Debates abiertos, dudas, ideas sueltas | La pestaña **Discussions** del repositorio |

Las conversaciones de trabajo van en GitHub, no en el grupo de mensajería, para que no se pierdan y le sirvan a quien llegue después.

## Cómo se decide

1. **Dentro de un equipo**, decide el equipo. Si no hay acuerdo, decide su responsable.
2. **Entre equipos**, deciden los responsables implicados. Si no hay acuerdo, se vota en la siguiente reunión.
3. **Lo que afecta a todo el proyecto** (cambiar la idea, crear o cerrar equipos, cambiar estas reglas) se propone en Discussions o en una reunión, y se vota con 👍.

La IA coordinadora puede proponer, resumir y avisar, pero nunca decide.

---

## Uso de la IA

- Usa la IA que quieras: Claude, ChatGPT, Codex, Gemini…
- Las normas comunes para las IA están en [`AGENTS.md`](AGENTS.md). La mayoría de herramientas lo leen solas.
- **Tú respondes de lo que envías**, aunque lo haya escrito la IA. Léelo y entiéndelo antes de mandarlo a revisión.
- En el pull request, di si has usado IA y para qué. No es para juzgar, sino para aprender entre todos qué funciona.
- **Nunca subas** contraseñas, claves de acceso, datos personales de terceros ni documentación de clientes.

## Convivencia

- Trata a los demás como te gustaría que te trataran a ti. Aquí hay gente que empieza y gente con mucha experiencia, y todos aprendemos de todos.
- Al revisar, critica el trabajo, nunca a la persona. Explica el porqué y propón cómo mejorarlo.
- Ninguna pregunta es tonta.
