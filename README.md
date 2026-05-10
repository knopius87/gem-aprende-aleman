# gem-aprende-aleman
# GemDeutsch 💎
### Aprende alemán — A1 a A2 — desde el español

GemDeutsch es una app de aprendizaje de alemán para hispanohablantes, inspirada en la mecánica de juegos como Duolingo y Candy Crush. Cada respuesta correcta rompe una gema. Sin registro, sin publicidad, sin datos en la nube — todo ocurre en tu dispositivo.

---

## ¿Para quién es?

Para cualquier hispanohablante que quiera aprender alemán desde cero o consolidar los niveles A1–A2 del Marco Común Europeo. La interfaz, las explicaciones gramaticales y el feedback están completamente en español.

---

## Qué incluye

### Vocabulario
180 palabras organizadas en 9 unidades temáticas. Cada sustantivo incluye siempre su artículo (`das Haus`, `die Mutter`, `der Bahnhof`) — desde el primer momento, porque en alemán el artículo es parte inseparable de la palabra.

| Unidad | Tema |
|--------|------|
| 0 | Begrüßung — Saludos y presentación |
| 1 | Familie — Familia y personas |
| 2 | Zahlen & Zeit — Números, horas y fechas |
| 3 | Essen & Trinken — Comida y bebida |
| 4 | Wohnen & Stadt — Vivienda y ciudad |
| 5 | Arbeit & Schule — Trabajo y escuela |
| 6 | Freizeit — Tiempo libre y hobbies |
| 7 | Reisen — Viajes y transporte |
| 8 | Gesundheit — Salud y cuerpo |

### Gramática — 14 temas A1–A2
- Artículos `der / die / das` con los 4 casos (Nominativ, Akkusativ, Dativ, Genitiv)
- `sein` y `haben` — conjugación completa
- Verbos modales: `können`, `müssen`, `wollen`, `dürfen`, `sollen`, `möchten`
- Verbos separables: `aufstehen`, `anrufen`, `abfahren`…
- Preposiciones con caso: `nach`, `bei`, `zu`, `aus`, `in`, `auf`…
- Plural de sustantivos
- Adjetivos declinados
- Orden de palabras — verbo en 2ª posición, inversión, subordinadas con `weil`
- Perfecto (`habe/bin + Partizip II`)
- Pretérito (`Präteritum`): `war`, `hatte`, `ging`…
- Futuro (`Futur I`): `werden + Infinitivo`
- Negación: `nicht`, `kein/keine`, `nie`
- Preguntas con W-Wörter: `Wer`, `Was`, `Wo`, `Wann`, `Wie`, `Woher`, `Wohin`…

### Conjugación
Ejercicios de llenado de huecos en cuatro tiempos verbales: Präsens, Perfekt, Präteritum y Futur I.

### Orden de palabras
Ejercicio interactivo de arrastrar chips para construir frases correctas — el tipo de ejercicio más útil para hispanohablantes, ya que el orden alemán difiere completamente del español.

### Diálogos con IA
7 escenarios de conversación (presentarse, restaurante, pedir direcciones, tienda, hotel, médico, entrevista de trabajo) generados por IA con feedback personalizado. Requiere conexión a internet. Si no hay conexión, la app usa diálogos de respaldo integrados y funciona igualmente.

---

## Cómo funciona el aprendizaje adaptativo

La app lleva un registro silencioso de cada respuesta. Las palabras que fallas más veces reciben un peso mayor y aparecen con más frecuencia. Los temas gramaticales con menor tasa de acierto se priorizan en las rondas mixtas. En la pantalla de resultado aparece un consejo personalizado basado en tu historial real, y en el perfil hay un informe semanal con tus puntos débiles.

---

## Modos de práctica

- **Vocabulario** — elige una unidad temática
- **Gramática** — elige uno de los 14 temas
- **Conjugación** — elige un tiempo verbal
- **Orden de palabras** — arma frases moviendo chips
- **Diálogo IA** — conversación con feedback en español
- **Repasar** — solo tus palabras más difíciles
- **Ronda rápida** — 3 preguntas, menos de 3 minutos

---

## Diseño e identidad visual

Cada unidad está representada por una gema SVG propia (rubí, amatista, zafiro, esmeralda, topacio, diamante, coral, hielo) dibujada con degradado de luz y facetas. Las gemas aparecen en los chips de navegación, en el feedback de respuestas, en las insignias y en la pantalla de resultado. Al acertar, los fragmentos de la gema explotan visualmente con una animación CSS.

Paleta: fondo negro profundo, amatista, topacio dorado, rubí, esmeralda. Sin modo claro — diseño OLED que ahorra batería en pantallas modernas.

---

## Motivación y progresión

- **Racha diaria** con contador visible
- **Objetivo diario** (5 ejercicios por defecto) con barra de progreso
- **Palabra del día** — una entrada nueva cada 24 horas
- **21 insignias** desbloqueables por racha, XP, unidades completadas y modos usados
- **Sistema de XP** con niveles (Anfänger → Lernender → Fortgeschrittener → Experte → Meister)
- **Confetti** al completar el objetivo diario o sacar 100%
- **Vibración háptica** — patrón corto al acertar, doble al fallar
- **Pronunciación** con Web Speech API — botón 🔊 en cada ejercicio, voz alemana nativa del dispositivo

---

## Tecnología y privacidad

La app es un único archivo HTML sin dependencias externas salvo dos fuentes de Google Fonts. No hay servidor, no hay base de datos, no hay cookies de seguimiento.

Todo el progreso se guarda exclusivamente en el `localStorage` del navegador, en el dispositivo del usuario. Nadie más tiene acceso a esos datos. Si el usuario borra el historial del navegador, los datos se borran — eso es todo.

Los diálogos con IA llaman a la API de Anthropic (Claude) con el texto de la respuesta del usuario. No se envía ningún dato de identificación personal.

**Compatible con:** Chrome, Firefox, Safari, Edge — escritorio y móvil. Funciona como app instalable en iOS (Compartir → Añadir a pantalla de inicio) y Android (Menú → Añadir a pantalla de inicio).

---

## Cómo publicar tu propia copia

1. Crea un repositorio público en GitHub
2. Sube el archivo `GemDeutsch_v3.html` renombrado como `index.html`
3. Ve a **Settings → Pages → Branch: main / root → Save**
4. La app estará disponible en `https://TU_USUARIO.github.io/NOMBRE_REPO/`

---

*Creado con [Claude](https://claude.ai) · Diseño de gemas, sistema adaptativo y diálogos IA generados mediante IA · Sin afiliación con ningún editorial ni método de enseñanza comercial*
