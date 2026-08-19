# MV Constructores — Sitio web

## Qué es
Landing page de una sola página (`index.html`, HTML/CSS/JS estático, sin dependencias)
para MV Constructores, negocio de servicios de elaboración de planos, diseño
arquitectónico, remodelaciones y ampliaciones, con zona de servicio en Ciudad de
México y Estado de México.

Concepto de diseño: estética de "plano arquitectónico" (blueprint) — el hero tiene
un plano de casa que se dibuja con animación de trazo, y las secciones están
numeradas como hojas de un juego de planos (Hoja A-2 Servicios, A-3 Proceso, etc.),
con un "cuadro de datos" tipo título de plano en el header y footer.

## Estado actual
- Sitio completo de una sola página: Hero, Servicios (4: planos, diseño
  arquitectónico, remodelaciones, ampliaciones), Proceso (3 pasos), Portafolio,
  Nosotros, Contacto, Footer.
- Portafolio: incluye un proyecto real, "Remodelación Bosques de Aragón"
  ("Modelo Aragón"), con 3 fotos (`img/aragon-cocina.jpg`, `img/aragon-sala-1.jpg`,
  `img/aragon-sala-2.jpg`) en un visor con miniaturas clicleables. Quedan 2
  espacios marcados "Próximamente" para futuros proyectos.
- Correo de contacto ya configurado: mvconstructores0309@gmail.com (aparece en
  la sección de contacto y en el footer).
- Repositorio en GitHub: `mv-constructores-web`, conectado a Vercel (deploy
  automático en cada cambio al repo).

## Pendientes / siguientes pasos
1. **Conectar el formulario de contacto de verdad.** Ahora mismo el formulario
   (nombre, teléfono, correo, tipo de servicio, mensaje) solo muestra un mensaje
   de confirmación en pantalla, pero NO envía nada realmente. Falta conectarlo
   a algo como Formspree, o a una función serverless de Vercel que mande el
   correo a mvconstructores0309@gmail.com.
2. **Agregar más proyectos al portafolio** conforme el usuario organice más
   fotos de trabajos anteriores.
3. **Agregar la URL pública del sitio** (una vez que el usuario la tenga en
   Vercel) en el propio sitio si aplica.

## Preferencias del usuario para este proyecto
- Comunicación en español.
- Respuestas directas, basadas en datos, sin agregar cosas no solicitadas.
- Le gusta ir construyendo el sitio de forma iterativa, complementando poco a poco.
