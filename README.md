#  La Bajona — Sistema web de pedidos

Aplicación web desarrollada para La Bajona, pollería y broastería ubicada en Matarani, Islay.

El proyecto permite a los clientes consultar el menú, personalizar sus productos, gestionar un carrito de compras y enviar su pedido directamente por WhatsApp.

---

##  Descripción

La Bajona es una aplicación web orientada a digitalizar el proceso de pedidos de una pollería/broastería.

La aplicación permite al usuario:

* Explorar el menú por categorías.
* Seleccionar productos.
* Gestionar cantidades.
* Personalizar productos.
* Seleccionar acompañamientos y bebidas.
* Agregar adicionales.
* Elegir entre delivery y recojo en local.
* Seleccionar método de pago.
* Ingresar dirección y observaciones.
* Revisar el total del pedido.
* Enviar el pedido directamente por WhatsApp.

---

##  Funcionalidades

###  Carrito de compras

* Agregar productos.
* Modificar cantidades.
* Eliminar productos.
* Cálculo automático del subtotal.
* Cálculo del costo de delivery.
* Cálculo del total.
* Resumen detallado del pedido.

###  Personalización

Los productos pueden contar con diferentes opciones de personalización, como:

* Acompañamientos.
* Tipo de papa.
* Sabor de bebida.
* Bebidas.
* Adicionales.
* Opciones personalizadas.

El sistema valida las opciones obligatorias antes de permitir enviar el pedido.

###  Integración con WhatsApp

El sistema genera automáticamente un mensaje estructurado con:

* Productos.
* Cantidades.
* Personalizaciones.
* Adicionales.
* Subtotal.
* Delivery.
* Total.
* Modalidad del pedido.
* Método de pago.
* Dirección.
* Notas adicionales.

El pedido se envía mediante WhatsApp.

### Control de productos agotados

El proyecto incorpora una integración con **Google Apps Script** para consultar y actualizar el estado de disponibilidad de determinados productos.

Esto permite marcar productos como agotados sin modificar directamente el menú principal.

###  Diseño responsive

La interfaz está orientada principalmente a dispositivos móviles e incorpora:

* Navegación inferior.
* Tarjetas de productos.
* Carrito flotante.
* Pantallas dinámicas.
* Animaciones y transiciones.
* Pantalla de bienvenida.
* Interfaz adaptada a diferentes tamaños de pantalla.

---

##  Tecnologías

* HTML5
* CSS3
* JavaScript
* Google Fonts
* WhatsApp
* Google Apps Script

---

##  Estructura

Actualmente el proyecto está desarrollado como una aplicación frontend de archivo único:

la-bajona/
│
├── index.html
└── README.md


La interfaz, estilos y lógica principal de la aplicación se encuentran dentro de `index.html`.

---

##  Flujo de usuario

Inicio
  ↓
Menú
  ↓
Selección de productos
  ↓
Personalización
  ↓
Carrito
  ↓
Delivery / Recojo
  ↓
Método de pago
  ↓
Validación
  ↓
Resumen del pedido
  ↓
WhatsApp


---

##  Aspectos técnicos

Durante el desarrollo se trabajó con:

* Manipulación dinámica del DOM.
* Manejo del estado del carrito.
* Funciones JavaScript para gestión de productos.
* Validación de opciones obligatorias.
* Cálculo dinámico de precios.
* Generación dinámica de mensajes.
* Integración mediante enlaces de WhatsApp.
* Consumo de servicios externos mediante `fetch`.
* Actualización dinámica de disponibilidad.
* Diseño responsive.
* Interacciones y animaciones mediante CSS.

---

## 🌐 Demo

Versión publicada de la aplicación:

https://labajonaislay.pages.dev/

---


## Objetivo

Desarrollar una solución web funcional para facilitar la recepción de pedidos de una pollería/broastería y ofrecer una experiencia de compra sencilla desde dispositivos móviles.

El proyecto representa un caso práctico de desarrollo frontend aplicado a un negocio real.

---

##  Desarrollador

Luis Diego Navarro Sacramento

Desarrollador del proyecto La Bajona — Sistema web de pedidos.

---

##  Licencia

Este proyecto se presenta con fines de demostración y portafolio.

