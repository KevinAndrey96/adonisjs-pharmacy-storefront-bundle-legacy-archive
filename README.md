# Hiperpharma: tienda y panel AdonisJS con maquetas HTML (archivo histórico)

![Estado: archivo histórico](https://img.shields.io/badge/Estado-archivo%20hist%C3%B3rico-lightgrey) ![AdonisJS 4.1](https://img.shields.io/badge/AdonisJS%204.1-5A45FF) ![HTML5 | Sass](https://img.shields.io/badge/HTML5%20%7C%20Sass-E34F26) ![MySQL](https://img.shields.io/badge/MySQL-4479A1)

> [!NOTE]
> Paquete con la tienda en línea, el panel administrativo y las maquetas HTML de Hiperpharma (2020). El producto continúa en **[pharmacy-ecommerce-platform](https://github.com/KevinAndrey96/pharmacy-ecommerce-platform)**, que reúne todos sus componentes con documentación actualizada.

## Qué contiene

- `Store/`: tienda en AdonisJS con inicio, categorías, listado y detalle de productos, carrito, checkout y pedido completado.
- `Admin/`: versión del panel administrativo incluida en el paquete de entrega.
- `HIPERPHARMA TIENDA/`: maqueta HTML y Sass de la tienda antes de integrarla con Edge.
- `HIPERPHARMA ADMIN/`: maqueta HTML del panel con su configuración de Grunt y Bower.

## Stack original

| Componente | Tecnología |
| :--- | :--- |
| Framework | AdonisJS 4.1 con vistas Edge |
| Maquetas | HTML5, Sass, Bootstrap y Grunt |
| Base de datos | MySQL |

## Ejecutarlo localmente

Cada aplicación AdonisJS (`Store/` y `Admin/`) se ejecuta por separado desde su carpeta:

```bash
cd Store
cp .env.example .env    # si no existe, crea uno con APP_KEY y DB_*
npm install
npx adonis key:generate
npm start
```

Las maquetas HTML se abren directamente en el navegador. Requiere Node.js 14; AdonisJS 4.1 ya no recibe soporte.

## Estado del repositorio

- Se conserva sin cambios funcionales como referencia del código original (2020).
- No recibe actualizaciones de dependencias; el mantenimiento ocurre en [pharmacy-ecommerce-platform](https://github.com/KevinAndrey96/pharmacy-ecommerce-platform).
- En noviembre de 2026 se depuró el historial completo: se retiraron los binarios `nuget.exe` de librerías de terceros y un manual de comercio de una pasarela de pagos, que no era código del proyecto. Todos los commits conservan su fecha original.

## Autoría

Kevin Andrey Herrera Silva ([@KevinAndrey96](https://github.com/KevinAndrey96)).

## Licencia

Código desarrollado para un cliente y publicado como muestra de portafolio. No incluye licencia de código abierto: todos los derechos reservados.
