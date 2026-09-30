---
name: ai-design-weekly
description: Genera un newsletter semanal (formato email) con las novedades de IA de los últimos 7 días aplicadas a diseño de producto, UX/UI y diseño visual. Usar SIEMPRE que la persona pida un resumen, digest, newsletter, "qué hay de nuevo", "novedades", "últimas noticias" o "qué pasó esta semana" sobre IA y diseño, UX, UI, Figma, herramientas de diseño, diseño de producto o diseño de interfaces con IA, aunque no diga "newsletter" ni "semanal".
---

# AI Design Weekly

Newsletter personal para una UX/UI Design Manager que lidera un equipo y trabaja embebida en un equipo de desarrollo de IA. Lo lee ella sola, para mantenerse al día y detectar qué vale la pena probar o llevar al equipo. Escribir en español rioplatense (voseo), tono informal de colega, sin relleno.

## 1. Período

Cubrir los **últimos 7 días** contados desde la fecha actual. Calcular el rango explícito (ej. "23–30 sep 2026") y ponerlo en el asunto. Descartar cualquier novedad fuera del rango; si algo relevante es un poco anterior pero se volvió noticia esta semana (lanzamiento general después de una beta), aclararlo.

## 2. Investigación

Hacer entre 8 y 15 búsquedas web, cada una sobre un frente distinto. No combinar temas en una sola query. Frentes a cubrir:

- **Herramientas de diseño con IA**: Figma (Make, AI features, Config), Adobe (Firefly, Photoshop/Illustrator IA), Framer, Canva, Penpot, Uizard, Galileo/Stitch, v0, Lovable, Bolt.
- **Modelos y labs con impacto en diseño**: lanzamientos de OpenAI, Anthropic, Google, Meta, Midjourney, etc. que cambien cómo se diseña o prototipa (generación de UI, imagen, video, agentes que operan interfaces).
- **Diseño de productos de IA**: patrones de UX para agentes, interfaces conversacionales, confianza/explicabilidad, artículos de NN/g, Smashing, UX Collective, Google PAIR, etc.
- **Design-to-code y design systems**: MCP de Figma, generación de código desde diseño, tokens, IA en design systems.
- **Industria y rol del diseñador**: estudios, encuestas, debates sobre el rol, contrataciones/despidos relevantes, opiniones influyentes.
- **Data viz + IA** (bonus, solo si aparece algo fuerte).

Ojo: la página de release notes de Figma no muestra fechas en el fetch; para fechar novedades de Figma, cruzar con el Help Center o trackers de changelog. Si algo es relevante pero no se puede fechar, va en una sección aparte "📌 En el radar" aclarando que no se confirmó la fecha exacta.

Usar `web_fetch` en las fuentes clave para confirmar fecha y detalles; los snippets no alcanzan. Priorizar fuentes primarias (blogs oficiales, changelogs) sobre agregadores.

## 3. Curaduría

Quedarse con 6–10 ítems. Criterio de selección, en orden:
1. ¿Cambia algo que ella o su equipo podrían hacer esta semana o este mes?
2. ¿Es relevante para diseñar productos de IA (su contexto de trabajo)?
3. ¿Es una señal de hacia dónde va la industria?

Descartar: rumores sin fuente, anuncios puramente de marketing sin sustancia, repeticiones de la misma noticia.

## 4. Formato del email

```
Asunto: AI × Design Weekly · [rango de fechas] — [titular de la noticia más fuerte]

Hola Nati 👋

[2–3 líneas: el pulso de la semana en una idea.]

🔥 LO MÁS IMPORTANTE
[1 ítem destacado, 4–6 líneas: qué pasó + por qué importa para ella.]

🛠️ HERRAMIENTAS
[ítems]

🤖 DISEÑAR PRODUCTOS DE IA
[ítems]

📡 INDUSTRIA Y SEÑALES
[ítems]

📌 EN EL RADAR (opcional)
[Cosas relevantes sin fecha confirmada o que llegan pronto.]

🧪 PARA PROBAR ESTA SEMANA
[1–3 acciones concretas: algo para testear o llevar a la próxima reunión de equipo.]

Hasta la próxima.
```

Cada ítem: **título corto en negrita**, 2–3 líneas (qué pasó + "por qué te importa"), fuente con link. Omitir una sección si no hubo nada relevante; no rellenar.

## 5. Reglas

- Parafrasear siempre; nada de copiar párrafos de las fuentes.
- Si no se pudo confirmar la fecha de una novedad, no incluirla.
- Si la semana viene floja, decirlo y hacer un newsletter más corto.
- Entregar el email en el chat, listo para leer o copiar.
