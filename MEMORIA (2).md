# Memoria — Mi primera app Android con Kotlin y Compose

**Alumno/a:** Kenneth E. Salmerón Rodríguez
**Fecha:** 23/9/2026

## Tareas completadas

### Bloque 1 — Exploración guiada
- [x] Abre Android Studio y el proyecto MiPrimerAplicacion.
- [x] Localiza en el panel Project (vista Android): MainActivity.kt, strings.xml, build.gradle.kts (Module :app) y AndroidManifest.xml.
- [x] Abre MainActivity.kt y responde las preguntas de abajo.
- [x] Ejecuta la app en el AVD y comprueba que se ve el saludo por defecto.

### Bloque 2 — Personalización del saludo
- [x] Cambia el texto del saludo en la función Greeting:
- [x] Ejecuta la app y comprueba el cambio.
- [x] Cambia el nombre que se pasa desde MainActivity:
- [ ] Observa que el texto ahora es dinámico (usa $name).
- [ ] Añade un segundo Text debajo del primero con un mensaje distinto. Pista: envuelve ambos en una Column.
- [ ] Cambia el color del texto usando color = Color.Blue en el Text.
- [ ] Cambia el color de fondo del tema en ui/theme/Color.kt.

### Bloque 3 — Previews y organización
- [ ] Añade una segunda @Preview con otro nombre:
- [ ] Comprueba que en el panel Design aparecen las dos previews.
- [ ] Añade una tercera preview con Modifier para ver el efecto del padding y el fondo:
- [ ] Investiga y responde la pregunta de abajo.
- [ ] Organiza el contenido en una Column con separación entre elementos:

### Bloque 4 — Interactividad: botón y contador
- [ ] Añade un botón debajo del saludo:
- [ ] Crea una variable de estado para contar pulsaciones:
- [ ] Muestra el contador en un Text y actualízalo al pulsar el botón:
- [ ] Ejecuta la app y comprueba que el contador aumenta.
- [ ] Añade un segundo botón que reinicie el contador a 0. RETO EXTRA
- [ ] Cambia el color del texto según el número de pulsaciones (rojo si es par, azul si es impar). RETO EXTRA

### Bloque 5 — Depuración con Logcat
- [ ] Introduce un error deliberado en el código (por ejemplo, escribe Text(text = 42)).
- [ ] Ejecuta la app y observa el error en el panel Build.
- [ ] Corrige el error y vuelve a ejecutar.
- [ ] Añade un log en el onCreate:
- [ ] Abre el panel Logcat, filtra por MiApp y comprueba que aparece el mensaje.
- [ ] Provoca un cierre inesperado (divide entre cero en un onClick) y busca FATAL EXCEPTION en Logcat.

### Bloque 6 — Documentación y entrega
- [x] Genera y descarga tu MEMORIA.md con el botón de abajo (incluye tus respuestas y el estado de las tareas).
- [ ] Añade a mano las capturas de pantalla de cada bloque al archivo descargado.
- [ ] Comprime el proyecto en un .zip (excluyendo build/ y .gradle/).

### Entregables
- [ ] Enlace github a la actividad (opcional).
- [ ] MEMORIA.md con capturas, respuestas y reflexión personal.

## Respuestas y reflexión

**B1 — Clase y herencia**

La clase MainActivity, la cual hereda de ComponentActivity

**B1 — Método sobrescrito**

Sobrescribe onCreate(savedInstanceState: Bundle?) el cual se llama cuando se crea la activity. Se llama antes a super.onCreate(savedInstanceState) activando enableEdgeToEdge() y luego es llamado setContent para la IU.

**B1 — Función en setContent**

MiPrimeraAplicacionTheme

**B1 — Para qué sirve @Preview**

Se abre una preview de la app sin ejecutarla

**B3 — padding vs background**

_(sin responder)_

**Reflexión 1 — val vs var**

val inmutable y var mutable

**Reflexión 2 — parámetro modifier**

Sirve para permitir que el elemento padre modifique el diseño del Greeting

**Reflexión 3 — remember/mutableStateOf**

_(sin responder)_

**Reflexión 4 — @Composable vs @Preview**

_(sin responder)_

**Reflexión 5 — Logcat vs Build**

_(sin responder)_

**Reflexión 6 — dificultad encontrada**

_(sin responder)_

## Capturas de pantalla

_(añade aquí tus capturas de cada bloque antes de entregar)_

## Dificultades encontradas y cómo se resolvieron

_(ya recogido en la pregunta de reflexión 6 de arriba, complétalo si quieres)_
