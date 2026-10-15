# Magnolias · Carta (demo)

Carta online de **Magnolias**, panadería y pastelería sin TACC.

Es una página estática (un solo `index.html`) que permite:

- Ver los productos por categoría (panificados, dulces, tartas, pizzas, etc.).
- Filtrar por etiquetas: sin lactosa, vegano, congelado.
- Armar un pedido y enviarlo directamente por **WhatsApp** con el detalle ya escrito.
- Consultar los locales para retiro o envío.

## Estructura

```
index.html   # carta completa (HTML + CSS + JS inline)
README.md
```

## Uso local

No requiere instalación ni build. Abrí `index.html` en el navegador o serví la carpeta:

```bash
npx serve .
```

## Configuración

En el bloque `<script>` de `index.html`:

- `WHATSAPP`: número al que se envían los pedidos (en la demo es un número de prueba; reemplazarlo por el del local, formato internacional sin `+`).
- La lista de productos (nombre, descripción, precio, unidad, etiquetas e imagen) está definida en el mismo script.

## Deploy

El sitio está desplegado en **Vercel** como sitio estático (sin framework ni comando de build).
