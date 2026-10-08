# La ruleta de San Batildo

Una mesa de juego amistosa: el giro y las caras son el centro de la experiencia.

## Tokens
Fuente de verdad: variables CSS en dist/index.html.
Azul tinta #173c60; azul mesa #e6f0f8; blanco #ffffff; coral #fc806b; amarillo #f9cf65; verde #a1c9b9.
Títulos: Georgia. Texto y controles: Segoe UI. Rueda circular con fotos en cada sector.

## Comportamiento
Botón nativo para girar, desactivado durante el giro. Resultado persistente con región viva. Sin exclusiones, eliminaciones ni efectos en WhatsApp. Movimiento reducido respetado. Fotografías incrustadas, sin dependencias remotas.

## Verificación
El usuario ha indicado no ejecutar tests sin petición expresa. No se han ejecutado pruebas funcionales ni automatizadas.

## Animación y móvil
Puntero y centro animados durante el giro, aparición del resultado y confeti temporal. Respetar movimiento reducido. Sin panel ni lectura de datos del visitante. En móvil: título, rueda, botón de ancho completo y resultado; áreas seguras y tarjetas de integrantes en tres columnas, dos en pantallas muy estrechas.

## Giro visible
Rotación del lienzo mediante Web Animations: seis vueltas y frenado normal; una vuelta suave en 1,8 segundos cuando se solicita movimiento reducido. El resultado aparece al finalizar. Las fotos se dibujan al cargar, no en cada fotograma.

## Dirección minimalista vigente
Solo una rueda centrada en la pantalla, fondo azul claro y botón circular con icono de reproducción en el centro. Sin textos visibles, nombres en sectores, cabecera, lista de integrantes ni confeti. La foto ganadora aparece en el centro; el nombre se anuncia únicamente a tecnologías de asistencia.
