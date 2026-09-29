# foro-html

Estación 3 — Rodaje / Preparación y tomas.
Mockup navegable en HTML estático (sin build, sin frameworks).

## Estructura

```
foro-html/
├── index.html                  → índice de navegación entre las 9 pantallas
├── 3.01-posicionamiento.html
├── 3.02-bienvenida.html        → bienvenida + pasos + Director IA
├── 3.03-guion-1.html           → Escena 1 · frase "Primero planeo, después gasto" · VILLANO
├── 3.04-cuenta-1.html          → 3 · 2 · 1 antes de toma 1
├── 3.05-grabacion-1.html       → REC activa con cronómetro
├── 3.06-clip-guardado.html     → ¡CORTE! + paso a escena 2
├── 3.07-guion-2.html           → Escena 2 · frase "Primero ahorro, luego gasto" · EMOCIONADO
├── 3.08-cuenta-2.html          → 3 · 2 · 1 antes de toma 2
├── 3.09-grabacion-2.html       → REC activa con cronómetro
└── assets/
    └── styles.css              → hoja de estilos compartida (header, footer, paleta)
```

## Cómo abrirlo

Cualquier opción sirve:

```bash
# Opción 1 — abrir directo
open index.html         # macOS
xdg-open index.html     # Linux

# Opción 2 — servidor local
python3 -m http.server 8080
# luego visita http://localhost:8080
```

## Identidad visual

| Token            | Valor                        |
| ---------------- | ---------------------------- |
| Azul corporativo | `#0a4d8c` → `#1a73c4`        |
| Amarillo acento  | `#ffd400`                    |
| Rojo grabación   | `#e53935`                    |
| Verde OK         | `#2ec27e`                    |
| Fondo            | `#f4f8fc`                    |
| Tipografía       | Inter (Google Fonts)         |

Todas las pantallas comparten el mismo header (BanCoppel · Atore Coppel · 🎬 RODAJE · 3) y el mismo footer (aviso de privacidad + tip del director).

## Flujo

```
3.01 → 3.02 → 3.03 → 3.04 → 3.05 → 3.06 → 3.07 → 3.08 → 3.09
 posicion  bienv  guion  cta    REC    corte  guion  cta    REC
```

Cada paso es enlazable con `Continuar`, `Siguiente escena` o `Repetir toma`.

## Marca

Branding y diseño: **AGUITECH** — Ingeniería + Diseño + Sistemas.
