# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

delegated: Astro 7 + Tailwind CSS v4 (vía @tailwindcss/vite), sin framework JS — interactividad con vanilla JS en isla única. Deploy estático (Netlify-compatible).

## Users

Habitantes de Cuernavaca y alrededores (Jiutepec, Temixco, Emiliano Zapata) que piden comida a domicilio por WhatsApp; foodies curiosos 20-40 años y familias que buscan una hamburguesa premium distinta.

## Product Purpose

Landing de conversión para RUMEN, Dark Kitchen de carne de búfalo: convertir visitas en pedidos de WhatsApp, educar sobre el búfalo (más proteína, menos grasa, sabor intenso) y proyectar marca premium más allá de un menú estático.

## Positioning

La única Dark Kitchen de la zona especializada en búfalo de rancho: smash burgers y la insignia Rumeante Búfalo, con storytelling de origen ("Búfalo de origen") y fotografía dramática propia.

## Operating Context

Solo delivery/take-out, sin local físico. Pedido real por WhatsApp +52 5565366128. Menú interactivo canónico vive en https://menurumen.netlify.app/ (esta landing lo presenta y enlaza). Cobertura: Cuernavaca, Jiutepec, Temixco y alrededores. Fotos reales en `public/img/`. Precios y platillos confirmados por el dueño (11 ítems, ver HTML de menú provisto).

## Capabilities and Constraints

- Paleta estricta del logo: Negro Profundo Matte #0D0D0D base, Dorado Búfalo #C18C4E acento, crema hueso para texto display.
- Logo real: `public/img/logo-completo.png` (RUMEN + cuernos + BÚFALO DE ORIGEN), isotipo `public/img/logo-cabeza.png`.
- Tipografía: Serif clásica para títulos/nombres de platillos (eco del wordmark Didone del logo), Sans moderna (Montserrat) para cuerpo/precios/funcional.
- Carrito demo en memoria → compone mensaje y abre `wa.me/525565366128`. Sin pagos en línea.
- Extras con precio (+$ tocino/queso/etc.) son demo de la casa, etiquetados como tales hasta confirmación del dueño.

## Brand Commitments

Nombre RUMEN, tagline "BÚFALO DE ORIGEN", handle @Rumen.mx, voz directa y de brasa nocturna. Estética "Rich, Moody and Textured": fondos negros, iluminación enfocada, madera oscura/pizarra.

## Evidence on Hand

Fotos reales: `public/img/rancho.jpg` (La del rancho), `public/img/clasica.jpg` (La Clásica), `public/img/papas.jpg` (Papas Rumeantes en empaque con sticker). Menús físicos: `Menu Rumen Fisico.pdf`, `Rumen Menú.pdf`. Datos reales: menú de 11 ítems con precios Sola/Combo, WhatsApp, zonas, link interactivo (ver Operating Context).

## Product Principles

1. Conversión primero: cada sección termina en un camino a WhatsApp o al menú.
2. El búfalo se demuestra, no se declara: foto, textura y origen antes que adjetivos.
3. Negro y dorado siempre: nada fuera de la paleta del logo.
4. Móvil es el comedor: legibilidad y pulgares antes que desktop.
5. Datos reales o nada: precios/platillos del dueño; lo inventado se etiqueta demo.

## Accessibility & Inclusion

Contraste AA (crema sobre negro, dorado solo para texto grande/acentos), foco visible dorado, modal y drawer con Escape y foco inicial, imágenes con alt en español.
