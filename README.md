# IdeaBridge 🎛️

**Puente creativo entre músicos y productores.**

Graba tu idea musical en capas — beatbox, melodías, armonías, lo que sea — y exporta stems separados listos para arrastrar a cualquier DAW.

---

## ¿Para qué sirve?

Los músicos tienen ideas. Los productores necesitan recibirlas con fidelidad.

IdeaBridge captura una idea musical completa antes de que se pierda: el creativo graba cada elemento por separado con un metrónomo de referencia, la app procesa el beatbox en un ritmo digital real, y empaqueta todo en un ZIP que el productor abre directamente en Ableton, Logic, Pro Tools o cualquier DAW.

Sin apps pagas. Sin instalación. Sin perder la idea en el camino.

---

## Cómo funciona

1. **Elige el BPM** — el metrónomo mantiene el tempo mientras grabas
2. **Graba el beat** — haz beatbox, la app detecta kick / snare / hi-hat y los sintetiza como audio real
3. **Agrega pistas libres** — melodías, armonías, bajo, vientos, letra, lo que quieras — con nombre o sin nombre
4. **Exporta** — descarga un ZIP con los stems separados + un README para el productor con el BPM y la estructura de la sesión

---

## Para el productor

Dentro del ZIP vas a encontrar:

- `Beat.wav` — el ritmo procesado (kick/snare/hihat sintetizados, no la voz)
- Una pista por cada idea grabada en audio original como referencia
- `LEEME.txt` con el BPM y la estructura de la sesión

Arrastra cada archivo a una pista de tu DAW. Listo.

---

## Stack

- HTML / CSS / JS — una sola página, sin dependencias externas
- Web Audio API — grabación, metrónomo, síntesis y procesamiento de señal en el browser
- JSZip (CDN) — empaquetado de stems
- GitHub Pages — deploy estático, sin backend, sin costo

---

## Uso local

```bash
git clone https://github.com/[usuario]/idea-bridge.git
cd idea-bridge
open index.html
```

No requiere servidor. Abre directo en Chrome o Safari.

> ⚠️ El navegador va a pedir permiso de micrófono. Es necesario para grabar.

---

## Roadmap

- [ ] Link de sesión compartible (el creativo graba, el productor accede por URL)
- [ ] Clasificación de beat con ML (TensorFlow.js) para mayor precisión
- [ ] Exportar beat como MIDI
- [ ] Modo colaborativo en tiempo real

---

Construido con [Claude](https://claude.ai) · Gravitas Solutions
