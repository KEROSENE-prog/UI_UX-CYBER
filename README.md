# Instituto Universitario Jesús Obrero (IUJO)
## CyberPOS - Sistema de Monitoreo y Punto de Venta para Cyber Gaming

Sistema integral de interfaz web UI/UX adaptado a la identidad visual de **Laneros Gamer**. Combina un módulo de Punto de Venta (POS) para la gestión e inventario de productos (snacks y bebidas) con un sistema centralizado para el monitoreo en tiempo real del tiempo de uso de computadoras y consolas de videojuegos.


##  Tecnologías Utilizadas
* **HTML5 Semántico:** Maquetación modular basada en estándares HTML5 con (`<main>`, `<section>`, `<article>`, `<aside>`, `<header>`, `<nav>`, `<fieldset>`, `<dialog>`).
* **CSS3 Puro:** Diseño "Mobile-First", arquitectura con variables nativas en `:root`, CSS Grid, Flexbox y animaciones de transición sin necesidad de frameworks externos.
* **Vanilla JavaScript (ES6+):** Lógica ligera para el control interactivo de modales nativos, menú hamburguesa en dispositivos móviles, pestañas de roles y notificaciones temporizadas (Toasts).


##  Identidad Visual y Sistema de Diseño
El prototipo está construido siguiendo una guía de estilo estilo *Living Style Guide* (`sistema_diseno.html`):

* **Paleta de Colores (Modo Oscuro / Gaming):**
  * `Obsidian Black (#0a0a0a)`: Fondo principal y contenedores base.
  * `Laneros Green (#35c029)`: Acento primario, botones, resaltado de horas y estados activos.
  * `Laneros Hover (#2da323)` y `Laneros Active (#227d1a)`: Respuestas visuales para interacción y clic táctil.
  * `Laneros Dark (#144a0f)`: Sombras y matices de profundidad.
  * `Success (#16a34a)` y `Danger (#991b1b)`: Confirmaciones, alertas y errores de validación.
* **Tipografías:**
  * **Títulos y Relojes:** `Outfit` (700 / 800) para un acabado geométrico, tecnológico y legible.
  * **Cuerpo y Formularios:** `Inter` (400 / 600) para máxima claridad en tablas, etiquetas e inventario.


##  Vistas del Sistema

1. **Monitoreo de Equipos (`dashboard.html`):**
   * Panel de 4 tarjetas KPI en la parte superior (Ingresos del día, PCs activas, Consolas activas y Pedidos pendientes)[cite: 13].
   * Cuadrícula responsiva de tarjetas (`<article>`) que muestra cada equipo, estado (Activo/Inactivo), contador de tiempo restante (`<time>`) y botón para sumar horas.

2. **Inventario de Snacks (`crud.html`):**
   * Catálogo tipo POS con tarjetas de productos, fotos corporativas, precio y stock disponible.
   * Barra de búsqueda rápida por nombre y filtro por categorías (`<select>`).
   * Modal unificado (`<dialog>`) nativo para "Crear / Editar" productos.
   * Modal secundario para confirmación antes de eliminar registros.

3. **Autenticación (`login.html` / `registro.html`):**
   * Pantallas centradas mediante Flexbox sobre fondo inmersivo eSports con gradiente lineal.
   * Selector de pestañas (*Tabs*) para cambiar dinámicamente entre el rol de **Cliente** y **Administrador**.
   * Botón flotante exclusivo (`.floating-design-btn`) en el Login para la revisión rápida del Sistema de Diseño (`sistema_diseno.html`).

4. **Guía de Estilo Viva (`sistema_diseno.html`):**
   * Galería interactiva con la paleta de colores, jerarquía tipográfica, formulario de prueba con estados `:focus` y `:error`, catálogo de botones en sus 5 estados (`Normal`, `:hover`, `:focus`, `:active` y `:disabled`) y demostración de Toasts temporizados.


## 👥 Integrantes del Equipo
* **Luis Colmenarez** — C.I. V-30.178.822
* **Kelvin Nieto** — C.I. V-31.596.682
* **Jhonny Barrios** — C.I. V-30.621.847
* **Axel Dorante** — C.I. V-32.023.436