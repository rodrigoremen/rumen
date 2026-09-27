# Design

<!-- impeccable:design-schema 1 -->

## World

Brasa nocturna: negro matte profundo como pizarra de cocina, dorado bronce como luz de fuego, crema hueso como texto. Fotografía real dramática con grano fílmico, resplandor ámbar radial y marquesina dorada. Todo CTA respira WhatsApp.

## Tokens

- `coal #0D0D0D` fondo · `coal-2 #141414` superficies · `coal-3 #1C1A17` tiles sin foto
- `gold #C18C4E` acento/CTAs/badges · `gold-soft #D9A961` hover/énfasis · `gold-deep #8F6530`
- `cream #F4EDE1` texto principal · `cream-dim #CBBFA9` descripciones · `smoke #8E867A` microcopy
- Display: Bodoni Moda (Didone, eco del wordmark del logo) — títulos y nombres de platillos. Nunca para `@`, `¿` decorativo aislado ni cifras de precio.
- Body/funcional: Montserrat — descripciones, precios (`font-extrabold tabular-nums`), botones, formularios.

## Components

- Header fijo con blur: isotipo + RUMEN + tagline, nav en tracking amplio, CTA borde dorado que se rellena en hover con barrido de luz (`btn-gold`).
- Hero 100svh: foto real a bleed con degradados a coal, badge pulsante, H1 Didone con itálica dorada, doble CTA, fila de credenciales con rombos.
- Marquesina dorada con loop de claims.
- Cards de menú: foto con zoom lento en hover + grano, número serif, badges (Búfalo sólido / Insignia outline / Límite sutil), precio dorado sans, botón Elegir outline→fill.
- Bottom-sheet de modificadores: presentación (Sola/Combo), término solo en no-smash (nota de técnica smash en el resto), extras demo, stepper, total en vivo, backdrop blur; Escape cierra.
- Drawer de pedido: líneas con detalle, total, mensaje pre-redactado a `wa.me/525565366128`, vaciar; FAB aparece solo con ítems.
- Cobertura: input CP con mapa de rangos Morelos demo + mensaje de éxito/error; tarjetas de zonas; panel "Así funciona".
- IG: mosaico 4 fotos reales con overlay de icono en hover + nota de integración API.
- Detalles de navegador: selección dorada, scrollbar bronce, foco visible dorado, reveal con `cubic-bezier(0.22,1,0.36,1)`.

## Motion

Un momento autoral: el barrido de luz en botones dorados + reveals escalonados por sección. Sin entradas idénticas en cascada global; marquee lineal 28s.
