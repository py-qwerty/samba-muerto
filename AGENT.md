# Instrucciones persistentes

- No ejecutar tests de desarrollo salvo petición explícita del usuario.
- Leer AGENT.md al trabajar en el proyecto y actualizarlo con nuevas instrucciones persistentes.
- Explicar las cosas complejas de forma didáctica, desde ejemplos sencillos hasta conceptos más avanzados, para alguien sin conocimientos previos del proyecto o del código.
- La interfaz vigente es una tier list clásica: filas horizontales S, A, B, C, D y F con colores y un banco de fotos sin clasificar. Sustituye la ruleta.
- Mantener un estilo minimalista y priorizar el funcionamiento en móvil. Incluir arrastre con ratón/dedo y alternativa de tocar foto y fila; permitir teclado.
- Conservar los 24 integrantes y sus 22 fotos originales. El usuario ha autorizado avatares ilustrados aleatorios para quienes no tengan foto; son mascotas ficticias, no retratos reales. No inventar clasificaciones salvo la broma de exportación solicitada expresamente: Pablo aparece en S en la imagen. No incluir teléfonos completos, estados, conversaciones ni credenciales.
- No incluir paneles ni lectura de datos del navegador. La clasificación pertenece a cada visitante y no se envía a un servidor.
- Repositorio público autorizado: py-qwerty/samba-muerto. Web pública: https://py-qwerty.github.io/samba-muerto/. Metadatos sociales e imagen en ese mismo alojamiento público.
- El alojamiento anterior de Sites conserva su acceso privado salvo instrucción posterior. El destino solicitado para esta versión es GitHub Pages.

- Título exacto: «Prioridad de opiniones». Referencia visual del usuario: lienzo blanco redondeado, título grande centrado, tablero oscuro enmarcado, etiquetas S/A/B/C/D/F en rojo/naranja/amarillo/verde lima/cian/gris, tarjetas blancas con foto y nombre y banco «Sin clasificar» separado. Mantener la adaptación móvil.

- Avatares generados autorizados: gato astronauta para Rafa y rana maga para el integrante 5508. Conservar los originales generados dentro de assets/ y señalar su origen en integrantes.json y etiquetas accesibles.

- En móvil, priorizar la versión compacta de fotos cuadradas sin nombres visibles; mantener nombre accesible y mostrarlo al seleccionar. Filas de unos 64 px y sin márgenes exteriores grandes.
- Texto de orientación: «Ordena según cuánto respetas la opinión de cada persona. Te escucho.».
- Botón Crear imagen: generar un PNG local de la clasificación actual, con título, filas, fotos y nombres. Permitir compartir mediante el menú nativo (el usuario elige WhatsApp) o descargar como alternativa. No enviar mensajes automáticamente. Invalidar la imagen al cambiar el ranking.

- El integrante que figuraba como «Tú» se llama «Pablo» en toda la interfaz y metadatos. Al pulsar Crear imagen, mover a Pablo a S únicamente en la copia que se dibuja en el PNG, sin duplicarlo ni modificar el tablero. Si ya está en S, conservar su orden.
