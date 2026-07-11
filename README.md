# Turno Seguro 🦺

**Juego formativo de Seguridad y Salud en el Trabajo (SST)** — Misión: cero accidentes.

Un serious game de decisiones donde el trabajador vive un turno completo (planta → oficina) tomando decisiones seguras o inseguras, con consecuencias pedagógicas, puntaje, insignias y constancia de participación. Pensado para inducciones, reinducciones y campañas de cultura preventiva.

## 🎮 Jugar

**https://amdavil.github.io/turno-seguro/**

Funciona en celular y computador, sin instalación. Una partida completa toma 15–25 minutos; los modos por mundo, unos 10.

## Qué incluye

- **20 escenarios**: 10 del mundo operativo (EPP, caída de objetos, alturas, químicos, ruido, montacargas, herramientas, riesgo eléctrico, evacuación) y 10 de oficina (ergonomía, pausas activas, salud visual, orden, cargas, carga mental, escaleras, líquidos y equipos, reuniones, cierre de jornada).
- **3 modos**: turno completo, solo operativo, solo oficina.
- Mentor virtual **PREVI**, barra de bienestar, racha segura, mini-reto de EPP, preguntas rápidas y 10 insignias.
- **Consecuencias pedagógicas, nunca gráficas**: las escenas graves se congelan antes del impacto.
- Constancia de participación imprimible (anexo para el plan de formación del SG-SST).
- **Panel administrador** (botón 🔐, PIN demo: `2026`): estadísticas, mapa de calor de errores por escenario, personalización de marca (nombre, color, logo) y exportación CSV.

## Notas técnicas

- Un solo archivo `index.html`: HTML + CSS + JavaScript vanilla, sin dependencias ni build.
- Motor de escenas dirigido por datos: todo el contenido vive en el objeto `PACK` — agregar un escenario es agregar un objeto JSON.
- Los resultados se guardan en `localStorage` del dispositivo (prototipo). La versión multi-empresa con backend está en el roadmap.
- Personalización rápida por empresa: edita `PACK.empresa` (nombre, color de acento, logo) o usa el panel administrador.

---

Prototipo MVP · 2026 · Proyecto de [Projectability](https://projectability.net)
