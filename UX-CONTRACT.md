# Contrato de interacción

Fuente: instrucciones del usuario del 26 de octubre de 2026. Tier list clásica con las fotos existentes, funcional en móvil y estilo minimalista.

| Capacidad | Propietario | Comportamiento |
|---|---|---|
| Clasificación y orden | positions + move en index.html | Cada integrante aparece exactamente una vez. Filas S/A/B/C/D/F y banco sin clasificar. |
| Arrastre | startDrag/endDrag | Pointer Events; alternativa táctil y de teclado mediante selección y destino. |
| Selección | select | Botones con aria-pressed. Escape deselecciona. |
| Estado | #status | Región viva única; confirma movimientos y operaciones. |
| Reinicio | reset + undoState | Devuelve todas las fotos y permite deshacer. |
| Scrollbar | :root/html CSS | Estándares scrollbar-color/width; scroll vertical normal fuera de las fotos. |

No formularios, diálogos, listas desplegables, acceso a datos del navegador ni persistencia. Nunca ejecutar tests sin petición expresa.
