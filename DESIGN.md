# Samba · Tier list

## Propósito
Clasificar las fotos de los 24 integrantes en una tier list clásica. La clasificación empieza vacía y la decide cada visitante. Sustituye la ruleta.

## Dirección visual
Referencia suministrada por el usuario: tarjeta blanca grande, esquinas redondeadas, título «Prioridad de opiniones» centrado y destacado. Tablero oscuro enmarcado con filas S/A/B/C/D/F; tarjetas individuales blancas con fotografía y nombre. Banco «Sin clasificar» independiente, borde sutil y bandeja gris. Empezar con todos sin clasificar; no inventar rankings.

## Tokens y propiedad
Fuente de verdad: variables CSS de index.html. Fondo #f2f3f7, tinta #10182b, tablero #2b3544, marco #202b3b. Filas S #ff8080, A #ffc382, B #ffe184, C #bbff78, D #80def7, F #cbd5e2. Tarjetas 118 × 140 px en escritorio, 76 × 106 px en móvil; fotos 76/55 px. Tipografía Segoe UI. Las filas crecen y envuelven las tarjetas en móvil, sin scroll horizontal.

## Interacción canónica
Un único estado positions guarda el orden de cada fila y del banco. move mueve una foto sin duplicarla; render actualiza todos los destinos. Se puede arrastrar con ratón/dedo o seleccionar una foto y tocar una fila. En teclado, Tab y Enter seleccionan, las flechas arriba/abajo cambian de fila y Escape cancela. Las fotos vuelven al banco tocando Sin clasificar. Reiniciar admite Deshacer. No se guardan ni envían rankings.

## Móvil y accesibilidad
Filas que crecen con las fotos, sin ancho fijo ni desplazamiento horizontal. El gesto de arrastrar se limita a las fotos; el resto de la página permite scroll normal. Botones nativos, nombres accesibles de los integrantes, foco visible y mensajes de estado. El gesto táctil tiene alternativa de dos toques. Respeta movimiento reducido.

## Verificación
No ejecutar tests salvo petición expresa del usuario. La publicación y el estado de GitHub Pages no equivalen a validación funcional en un dispositivo.

## Avatares sin foto
Dos mascotas ficticias generadas con IA: gato astronauta naranja (Rafa) y rana maga turquesa (integrante 5508). Usar como imagen de su tarjeta; conservar las 22 fotografías originales. El nombre de la persona no cambia. Origen generado indicado en datos, tooltip y nombre accesible.
