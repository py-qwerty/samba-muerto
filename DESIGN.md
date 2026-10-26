# Samba · Tier list

## Propósito
Clasificar las fotos de los 24 integrantes en una tier list clásica. La clasificación empieza vacía y la decide cada visitante. Sustituye la ruleta.

## Dirección visual
Tablero clásico con filas horizontales S, A, B, C, D y F. Etiquetas cuadradas de colores, fondo oscuro y fotos cuadradas. Estilo minimalista, instrucciones breves y fondo azul claro heredado de Samba. Sin secciones decorativas.

## Tokens y propiedad
Fuente de verdad: variables CSS de index.html. Fondo #e6f0f8, tinta #173c60, tablero #232b36. Filas: S #fa8585, A #f7b27d, B #f6d47a, C #99d9bb, D #92c5ee, F #c2b0e7. Tipografía Segoe UI. Foto 66 px en escritorio y 53 px en móvil; etiqueta 76/50 px. Sin librerías externas.

## Interacción canónica
Un único estado positions guarda el orden de cada fila y del banco. move mueve una foto sin duplicarla; render actualiza todos los destinos. Se puede arrastrar con ratón/dedo o seleccionar una foto y tocar una fila. En teclado, Tab y Enter seleccionan, las flechas arriba/abajo cambian de fila y Escape cancela. Las fotos vuelven al banco tocando Sin clasificar. Reiniciar admite Deshacer. No se guardan ni envían rankings.

## Móvil y accesibilidad
Filas que crecen con las fotos, sin ancho fijo ni desplazamiento horizontal. El gesto de arrastrar se limita a las fotos; el resto de la página permite scroll normal. Botones nativos, nombres accesibles de los integrantes, foco visible y mensajes de estado. El gesto táctil tiene alternativa de dos toques. Respeta movimiento reducido.

## Verificación
No ejecutar tests salvo petición expresa del usuario. La publicación y el estado de GitHub Pages no equivalen a validación funcional en un dispositivo.
