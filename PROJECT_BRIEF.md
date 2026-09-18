# damy-store

E-commerce tops and Bikinis Store

## DAMY - Bikinis Crochet E-Commerce

Documento Maestro del Proyecto (PROJECT_BRIEF.md)
Fecha de creación: 18 de septiembre de 2026
Última actualización: 18 de septiembre de 2026 (v4 - Análisis Completo Consolidado)
Socio Técnico: Qwen (AI Assistant)
Desarrollador & Director Creativo: Ivan Byaneith am (Dev-Neith)
Marca: DAMY (@damystore)
Repositorio GitHub: [Enlace a tu repo]
Referencia Metodológica: The Odin Project (Foundations 76%)

1. VISIÓN Y PROPÓSITO DEL PROYECTO

Este no es un ejercicio académico; es un negocio real a largo plazo con impacto social. El objetivo es crear una plataforma de e-commerce funcional para la venta de bikinis de crochet tejidos a mano por artesanas colombianas, generando sustento para varias familias. Adicionalmente, este proyecto servirá como portafolio profesional y campo de entrenamiento práctico para el desarrollador.
Valores fundamentales:
Artesanía real y piezas únicas
Impacto social (sustento para familias artesanas)
Comunidad (clientas como embajadoras)
Transparencia (proceso de fabricación visible)
Calidad sobre cantidad

2. MODELO DE NEGOCIO Y REGLAS CLAVE

Producción
Bajo demanda. Sin inventario físico. Se fabrica después del pago.
Tiempo fabricación
5 días hábiles
Envío
Tiempo adicional según ciudad. Inicial solo Colombia.
Cobertura actual
Todo Colombia
Cobertura futura
Internacional
Envío gratis
Compras superiores a $300.000 COP (equivalente a ~2 bikinis)
Flujo de compra
Selección → Pago anticipado → Cola de producción (5 días) → Envío
Imágenes iniciales
Generadas con IA (Google Flow / Nano Banana Pro). Sirven como guía para artesanas Y mockups web. Se reemplazan/combinan con fotos reales en fases posteriores.
Canal de atención principal
WhatsApp Business (canal #1 de ventas en Colombia)

3. STACK TECNOLÓGICO

Capa
Tecnología
Estado
Notas
Estructura
HTML5 Semántico
✅ Dominado
Base The Odin Project
Estilos
CSS3 (Flexbox/Grid/Variables)
✅ Dominado
Sin preprocesadores
Interactividad
JavaScript Vanilla
🔄 En progreso
Lógica UI, validaciones, manipulación DOM
Backend/API
Node.js
⏳ Pendiente
Se integrará tras dominar JS
Framework Frontend
React
⏳ Pendiente
Futuro, NO en fase inicial
Base de Datos
Firebase (Firestore + Auth)
⏳ Pendiente
Registro usuarios, pedidos, stories UGC
Pasarela de Pagos
Wompi (Colombia)
⏳ Pendiente
Widget/Link inicial → API server-side después
Pagos a Cuotas
Addi (Colombia)
⏳ Pendiente
Opcional, muy popular en Colombia
Hosting Principal
Firebase Hosting
⏳ Configurar
Plan Spark (gratis). SSL auto. Integrado con Auth/Firestore.
Hosting Secundario
GitHub Pages
✅ Configurado
Backup y prototipos rápidos
Formularios (Fase 1)
Formspree o Firebase
⏳ Pendiente
Para contacto/captura sin backend propio

4. DECISIONES CLAVE TOMADAS (Registro Histórico)

Decisión
Razón
Fecha
D1
Tienda primero, Landing Page al final
No capturar leads sin tienda funcional a donde dirigirlos
18/09/2026
D2
Formulario de Contacto = Landing Page de Captura
Un solo formulario cumple ambas funciones. Menos páginas, más foco
18/09/2026
D3
Firebase Hosting como hosting principal
Integración nativa con Auth/Firestore/Wompi futuro. SSL gratis.
18/09/2026
D4
Navegación simplificada: solo Bikinis y Tops
Menos fricción para comprar. Catálogo enfocado.
18/09/2026
D5
Imágenes IA iniciales como guía + mockup
Las artesanas se guían por la foto generada. Se reemplazan con reales después.
18/09/2026
D6
WhatsApp como canal principal de atención
Canal de ventas #1 en Colombia. Widget flotante en todas las páginas.
18/09/2026
D7
Nombre de la marca: DAMY (@damystore)
Identidad definida.
18/09/2026
D8
Stories = UGC de clientas + contenido de marca
Carrusel de historias muestra fotos/videos reales de clientas con @damystore. Actualización quincenal/mensual.
18/09/2026
D9
Cada story UGC incluye crédito a la clienta + Shop the Look
Incentiva participación. Genera confianza. Venta emocional.
18/09/2026
D10
Concurso mensual "DAMY Creator of the Month"
Clientas publican con @damystore + #DAMYStore. Jurado interno elige ganadora.
18/09/2026
D11
Premio concurso: 1 bikini a elección. Menciones honoríficas: 15% descuento
Costo real bajo (~$150k producción), valor percibido alto ($330k+). Genera recompra.
18/09/2026
D12
Jurado interno. Anuncio último día del mes. Reset mensual
Simple, controlable, escalable.
18/09/2026

5. ANÁLISIS COMPLETO DE REFERENCIAS VISUALES
   5.1 IMAGEN 1 - HOME PAGE (Vista Inicial)
   Elementos identificados (de arriba a abajo):
   A. Announcement Bar (Barra Superior)
   Texto: "Envío gratis por compras superiores a $300.000"
   Comportamiento: Sticky o estática en la parte superior
   Estilo: Fondo contrastante, texto centrado, tipografía pequeña
   B. Navbar (Barra de Navegación)
   Logo: DAMY + ícono (pendiente definir con logo real)
   Links de navegación: Bikinis | Tops (SOLO estos dos, decisión D4)
   Íconos derecha: Búsqueda 🔍 | Carrito 🛍️ (con contador) | Favoritos ❤️ | Cuenta 👤
   Comportamiento: Sticky al scroll. Responsive: menú hamburguesa en móvil.
   C. Stories Carousel (Carrusel de Historias)
   Formato: Rectángulos verticales (NO círculos), estilo portrait
   Cantidad: ~12 visibles con scroll horizontal
   Navegación: Flechas ← → en los extremos
   Contenido: Imágenes, videos y GIFs
   Fuentes de contenido:
   Tipo 1: Contenido de marca (colecciones, detrás de cámaras, promos)
   Tipo 2: UGC de clientas (fotos/videos con @damystore) — ver sección 7
   Al hacer clic: Abre modal "Shop the Look" (ver 5.3)
   D. Título de Sección + Tagline
   Título: Centrado, tipografía elegante/serif, mayúsculas (ej: "BIKINIS CROCHET")
   Tagline: Texto descriptivo centrado debajo del título
   Adaptación DAMY: "Piezas únicas tejidas a mano por artesanas colombianas. Cada bikini es exclusivo, hecho especialmente para ti bajo pedido."
   E. Toolbar del Catálogo
   Breadcrumb: "Inicio / Bikinis" (navegación jerárquica, SEO friendly)
   Ver (View toggle): Cambiar vista grid/lista/foto grande
   Ordenar por: Precio ↑↓, Más recientes, Popularidad
   Filtrar: Abre panel de filtros (talla, color, precio, estilo, reversible)
   F. Product Grid (Vitrina de Productos)
   Layout: 4 columnas desktop → 2 tablet → 1-2 móvil
   Cada card muestra: Imagen principal, nombre, precio, badges
   Badges: "REVERSIBLE" (cuando aplica), "HECHO A MANO" (siempre)
   Hover effect: Ver 5.4
   G. WhatsApp Floating Widget
   Ícono circular fijo en esquina inferior derecha
   position: fixed en CSS
   Link directo a WhatsApp Business con mensaje predeterminado

5.2 IMAGEN 2 - FOOTER + CONTENIDO SEO
A. Bloque de Texto SEO (sobre el footer)
Texto descriptivo largo sobre los productos
Función: Posicionamiento en Google (SEO)
Adaptación DAMY: Describir proceso artesanal, 5 días de fabricación, tipos de bikinis, palabras clave naturales

B. Footer - Columna 1: "Acerca de nosotros"
Link
Página destino
Prioridad
Nuestra Historia / El Arte del Crochet
Página info (imagen + texto)
🟡 P2
Sobre Nosotros
Página info (imagen + texto)
🟡 P2
Sostenibilidad
Incluir en "Sobre Nosotros" inicialmente
🟢 P3
Trabaja con Nosotros
Futuro

C. Footer - Columna 2: "Servicio al cliente"
Link
Página destino
Prioridad
Guía de Tallas
Página info (tabla + imagen)
🟡 P2
Preguntas Frecuentes (FAQ)
Página info
🟡 P2
Envíos y Entregas
Página info
🟡 P2
Cambios y Garantías
Página info
🟡 P2
Derecho de Retracto
Página legal
🟢 P3
Derecho de Reversión
Página legal
🟢 P3
Política de Privacidad
Página legal
🟢 P3
Términos y Condiciones
Página legal
🟢 P3
SAGRILAFT
Página legal
🟢 P3

D. Footer - Columna 3: "Contáctanos"
Elemento
Adaptación DAMY
Formulario de Contacto
Link a página Contacto/Captura (formulario unificado, decisión D2)
Email servicio al cliente
hola@damystore.com (o similar)
Teléfono / WhatsApp
Número de WhatsApp Business
Wholesale
⏳ Futuro
PR / Comunicaciones
⏳ Futuro

E. Footer - Columna 4: Newsletter + Social + Legal
Elemento
Adaptación DAMY
Newsletter
Campo email + botón "Suscríbete". Captura emails desde el día 1.
Localizador de tiendas
❌ No aplica (100% online)
Redes sociales
Instagram, Facebook, TikTok, WhatsApp (íconos con links a @damystore)
Superintendencia SIC
Logo/link requerido por ley colombiana para e-commerce
Copyright
© 2026 DAMY. Todos los derechos reservados.
NIT
NIT de la empresa cuando se tenga
Dirección
Dirección registrada del negocio
Crédito dev
"Hecho con ♡ por Byaneith am"

5.3 IMAGEN 3 - MODAL "SHOP THE LOOK" (Stories)
Se abre al hacer clic en cualquier historia del carrusel.
Estructura del Modal (2 columnas)
Columna Izquierda - Contenido Visual:
Media principal en formato vertical (imagen/video/GIF)
Botón info (ⓘ) opcional en esquina inferior
Responsive: en móvil ocupa ancho completo arriba

Columna Derecha - Info + Shop the Look:
Elemento
Detalle
Avatar + @usuario
Tu @ o el de la clienta (UGC)
Fecha
"Hace X días"
Caption
Descripción corta del look/colección
Likes + Comentarios
⏳ Fase 2 (requiere backend)
Botón Cerrar (X)
Esquina superior derecha. También cierra con ESC o clic fuera

Sección "Shop the Look" (dentro del modal):
Lista de productos asociados a esa historia
Cada producto: miniatura + nombre + precio + botón "Buy"
Botón "Buy" → agrega al carrito o lleva a detalle del producto
Típicamente 2-3 productos por historia
Navegación del Modal:
Flechas ← → para pasar a historia anterior/siguiente SIN cerrar el modal
Overlay oscuro detrás (clic cierra el modal)
Tecla ESC cierra el modal
Crédito: "Con tecnología de Flowbox" en referencia → En DAMY: omitir o "Hecho con ♡ por Byaneith am (Dev-Neith)

5.4 IMAGEN 4A - PRODUCT GRID + HOVER EFFECT
Cada tarjeta de producto tiene 2 estados:
Estado Normal (sin hover)
Imagen principal del producto
Nombre del producto
Precio en COP
Badge "REVERSIBLE" (cuando aplica)
Badge "HECHO A MANO" (siempre)
Estado Hover (al pasar el mouse)
Imagen cambia a segunda vista (espalda/detalle)
Aparece selector de tallas rápido (XS, S, M, L, XL)
Texto: "Selecciona una talla de [Nombre Producto]"
Link: "Visita nuestra Guía de tallas"
Botón: "AGREGAR A LA BOLSA" (se activa al seleccionar talla)
Ícono vista rápida (👁️) → abre modal de vista rápida

Nota UX crítica: El usuario puede agregar al carrito SIN entrar a la página del producto. Reduce fricción = más conversiones.

5.5 IMAGEN 4B - PÁGINA DE DETALLE DE PRODUCTO
La página con más información y más crítica para conversión.
A. Galería de Imágenes (Columna Izquierda)
Imagen principal grande con flechas ← →
Thumbnails verticales a la izquierda (scroll ↑↓)
Indicadores de puntos abajo (muestra posición actual)
6 fotos por producto (generadas con IA inicialmente)
En móvil: swipe horizontal
B. Información del Producto (Columna Derecha)
Header:
Nombre de la colección (ej: "Coral")
Nombre del producto (ej: "Bottom de Bikini Maisie")
Precio en COP
Selector de Tallas:
Botones: XS, S, M, L, XL
Talla no disponible: tachada/deshabilitada
Link: "Visita nuestra Guía de tallas"
Acciones:
Botón "SAVE" → Guardar en favoritos (localStorage inicialmente, Firebase Auth después)
Botón "AGREGAR A LA BOLSA" → Agrega al carrito
Widget de Pago:
"Paga con Wompi" o "Paga con Addi en hasta 6 cuotas" (Fase 2)
C. Tabs de Información (4 pestañas)

ESCRIPCIÓN
Párrafo descriptivo + bullet points (tejido a mano, hilo algodón, 5 días, pieza única) + "Modelo usa talla S"
CUIDADO Y COMPOSICIÓN
Cómo lavar (a mano, agua fría, no secadora) + materiales (hilo 100% algodón)
GUÍA DE TALLAS
Tabla de medidas embebida (misma info que página independiente)
ENVÍOS Y DEVOLUCIONES
"5 días fabricación + envío. Envío gratis >$300k. Política de cambios"

D. Info Legal del Producto
Comercializado por: DAMY
NIT: [tu NIT]
Código SIC: [tu código]
País de Origen: Colombia
E. Otros Colores
Círculos de colores disponibles para el mismo diseño
Al hacer clic → cambia todas las imágenes del producto a ese color
F. "Completa tu look" (Sección Inferior)
Sugiere productos complementarios (si ve bottom → mostrar top que hace juego)
Array de relatedProducts en datos del producto

6. ESTRUCTURA DE DATOS
   6.1 Producto

const product = {
id: "bottom-maisie-001",
name: "Bottom de Bikini Maisie",
collection: "Coral",
price: 180000,
category: "bikinis", // "bikinis" | "tops"
type: "bottom", // "top" | "bottom" | "completo"

images: {
main: "maisie-main.jpg",
hover: "maisie-hover.jpg",
gallery: [
"maisie-1.jpg", "maisie-2.jpg", "maisie-3.jpg",
"maisie-4.jpg", "maisie-5.jpg", "maisie-6.jpg"
]
},

sizes: ["XS", "S", "M", "L", "XL"],
sizesAvailable: ["S", "M", "L", "XL"],

colors: [
{ name: "Animal Print", hex: "#8B7355", images: {/*...*/} },
{ name: "Coral", hex: "#FF6F61", images: {/*...*/} },
{ name: "Negro", hex: "#000000", images: {/*...*/} }
],

reversible: false,
handmade: true,
fabricationDays: 5,

description: "El Bottom de Bikini Maisie tiene una silueta con corte alto...",
features: ["Corte alto", "Tiras trenzadas", "Detalles de aros", "Tejido a mano"],
modelSize: "S",

care: "Lavar a mano con agua fría. No usar secadora. No exprimir.",
composition: "Hilo 100% algodón orgánico",

shipping: "5 días hábiles de fabricación + tiempo de envío. Envío gratis en compras superiores a $300.000",

relatedProducts: ["top-lolita-001", "pareo-marine-003"],

legal: {
commercializedBy: "DAMY",
nit: "TU-NIT-AQUI",
sicCode: "TU-CODIGO-SIC",
origin: "Colombia"
}
};

6.2 Story (Carrusel de Historias)

const story = {
id: 1,
type: "ugc", // "brand" | "ugc"
mediaUrl: "imagenes/clienta-maria-playa.jpg",
mediaType: "image", // "image" | "video" | "gif"
user: "@maria_playa",
platform: "instagram", // "instagram" | "tiktok" | null
date: "Hace 5 días",
caption: "María luciendo su Top Coral en Santa Marta 🌊",
isWinner: false, // true si es ganadora del mes actual
products: [
{ name: "Top Coral Triángulo", price: 185000, img: "top-coral.jpg", link: "producto.html?id=1" },
{ name: "Bottom Coral Brasileño", price: 145000, img: "bottom-coral.jpg", link: "producto.html?id=2" }
]
};

6.3 Ganadora del Mes (DAMY Creator)

const monthlyWinner = {
month: "Septiembre 2026",
winner: {
user: "@maria_playa",
platform: "instagram",
postUrl: "https://instagram.com/p/xxx",
image: "maria-ganadora.jpg",
prize: "Top de Bikini a elección"
},
honorableMentions: [
{ user: "@clienta2", discount: "15%" },
{ user: "@clienta3", discount: "15%" }
]
};

7. PROGRAMA "DAMY CREATOR OF THE MONTH"
   7.1 Flujo Mensual

SEMANA 1-3: RECOLECCIÓN
├── Clientas compran y publican con @damystore + #DAMYStore
├── Monitoreo diario del tag
└── Selección preliminar de mejores publicaciones

SEMANA 4: SELECCIÓN
├── Jurado interno (equipo DAMY) elige ganadora
├── Criterios: creatividad, calidad, engagement, autenticidad
└── 2-3 menciones honoríficas seleccionadas

DÍA ÚLTIMO DEL MES: ANUNCIO
├── Publicación en @damystore anunciando ganadora
├── Ganadora destacada en carrusel de stories de la web
├── Mensaje directo a ganadora: "¡Ganaste! Elige tu premio"
└── Ganadora elige su premio de la tienda

INICIO DEL MES SIGUIENTE: RESET
├── Nueva ronda comienza
├── Ganadora anterior pasa al "Hall of Fame"
└── Ciclo se repite 🔄

7.2 Sistema de Premios

🥇 Ganadora del Mes
1 bikini completo a elección
~$150k producción
$330k+ retail
🥈 Mención Honorífica (2-3)
15% descuento próxima compra
$0 directo
Genera recompra
🌟 Todas las participantes
Aparecer en galería de la web
$0
Reconocimiento

7.3 Comunicación en la Web
Home: Sección/banner "¿Quieres ser DAMY Creator del Mes?" + mini-galería ganadoras
Post-compra: Email/página de confirmación incentivando participación
Footer: Link "DAMY Creator del Mes"
Redes: Post fijado explicando concurso + stories mensuales
Página dedicada: Cómo participar + premio actual + Hall of Fame + reglas

8. LISTA MAESTRA DE EJECUCIÓN
   🔴 PRIORIDAD 1 - Estructura Core

COMPONENTES GLOBALES (todas las páginas)
├── [ ] Announcement Bar ("Envío gratis > $300.000")
├── [ ] Navbar (Logo DAMY + Bikinis + Tops + Search + Cart + Favorites + Account)
│ └── Responsive: menú hamburguesa en móvil
├── [ ] Footer completo (4 columnas + copyright bar)
├── [ ] WhatsApp Floating Widget (position: fixed)
└── [ ] Newsletter mini-form en footer

PÁGINAS PRINCIPALES
├── [ ] HOME
│ ├── Stories Carousel + Modal Shop the Look
│ ├── Título + Tagline artesanal
│ ├── Toolbar (Breadcrumb + View + Sort + Filter)
│ ├── Product Grid con hover effect (selector talla rápido)
│ └── Sección "DAMY Creator del Mes" (mini-galería + CTA)
├── [ ] CATÁLOGO BIKINIS (grid + filtros + ordenar)
├── [ ] CATÁLOGO TOPS (grid + filtros + ordenar)
├── [ ] DETALLE DE PRODUCTO
│ ├── Galería 6 fotos (thumbnails + flechas + dots)
│ ├── Selector talla + color
│ ├── Botones Save + Agregar a la bolsa
│ ├── Tabs: Descripción | Cuidado | Guía Tallas | Envíos
│ ├── Info legal del producto
│ └── "Completa tu look" (productos relacionados)
├── [ ] CARRITO DE COMPRAS
│ ├── Items con cantidad editable
│ ├── Subtotal + cálculo envío
│ └── Barra progreso hacia envío gratis ($300k)
└── [ ] CHECKOUT / PAGO
├── Resumen pedido
├── Datos envío
└── Integración Wompi

    🟡 PRIORIDAD 2 - Páginas de Información

    ├── [ ] Sobre Nosotros / Nuestra Historia (imagen + texto)

├── [ ] Guía de Tallas (tabla medidas + imagen)
├── [ ] FAQ - Preguntas Frecuentes
├── [ ] Envíos y Entregas
├── [ ] Cambios y Garantías
├── [ ] Contacto / Captura (FORMULARIO UNIFICADO - decisión D2)
│ ├── Campos: Nombre, Email, Teléfono, Mensaje
│ └── Función dual: contacto + captura de leads
└── [ ] DAMY Creator del Mes
├── Cómo participar (3 pasos)
├── Premio del mes actual
├── Hall of Fame (ganadoras anteriores)
├── Reglas
└── CTA al catálogo

    🟢 PRIORIDAD 3 - Páginas Legales




    ├── [ ] Términos y Condiciones

├── [ ] Política de Privacidad
├── [ ] Derecho de Retracto
├── [ ] Derecho de Reversión
└── [ ] SAGRILAFT

🔵 PRIORIDAD 4 - Funcionalidades Avanzadas

├── [ ] Registro/Login (Firebase Auth)
├── [ ] Lista de Favoritos persistente (vinculada a cuenta)
├── [ ] Panel Admin (cola de producción, estados de pedido)
├── [ ] Newsletter backend (emails en Firestore)
├── [ ] Widget Addi (pagos a cuotas)
└── [ ] Escalamiento internacional (multiidioma, multimoneda)

9. MAPA DE NAVEGACIÓN (SITEMAP)

🏠 HOME
│
├── 👙 BIKINIS (catálogo)
│ └── 👙 Detalle Bikini
│
├── 👚 TOPS (catálogo)
│ └── 👚 Detalle Top
│
├── 🛒 CARRITO → 💳 CHECKOUT (Wompi)
│
├── ❤️ FAVORITOS (requiere login - Fase 2)
├── 👤 MI CUENTA (requiere login - Fase 2)
│
├── DAMY CREATOR DEL MES
│
├── 🧶 SOBRE NOSOTROS
├── 📏 GUÍA DE TALLAS
├── ❓ FAQ
├── 🚚 ENVÍOS Y ENTREGAS
├── 🔄 CAMBIOS Y GARANTÍAS
├── 📞 CONTACTO / CAPTURA
│
├── 📄 Términos y Condiciones
├── 📄 Política de Privacidad
├── 📄 Derecho de Retracto
├── 📄 Derecho de Reversión
└── 📄 SAGRILAFT

10. ORDEN DE CONSTRUCCIÓN

Paso
Qué construimos
Archivos
1
Estructura Global (Announcement Bar + Navbar + Footer + WhatsApp widget)
index.html, css/styles.css, js/main.js
2
Home (Stories carousel + Modal Shop the Look + Tagline + Product grid con hover + Sección Creator)
index.html, css/styles.css, js/main.js, js/stories.js, js/products.js
3
Catálogo con filtros funcionales
catalogo.html, css/styles.css, js/catalogo.js
4
Detalle de Producto (galería + tabs + selector talla/color + completa tu look)
producto.html, css/styles.css, js/producto.js
5
Carrito de Compras funcional
carrito.html, css/styles.css, js/carrito.js
6
Checkout + Wompi
checkout.html, css/styles.css, js/checkout.js
7
Páginas de información (7 páginas)
sobre-nosotros.html, guia-tallas.html, faq.html, envios.html, cambios.html, contacto.html, creator-del-mes.html
8
Páginas legales (5 páginas)
terminos.html, privacidad.html, retracto.html, reversion.html, sagrlaft.html
9
Firebase Auth + Favoritos + Panel Admin
js/auth.js, js/admin.js, Firebase config
10
Despliegue final en Firebase Hosting
firebase.json, .firebaserc

11. ESTRUCTURA DE CARPETAS DEL PROYECTO

damy-store/
├── index.html (Home)
├── catalogo.html (Catálogo Bikinis/Tops)
├── producto.html (Detalle de Producto)
├── carrito.html (Carrito de Compras)
├── checkout.html (Checkout/Pago)
├── sobre-nosotros.html (Info)
├── guia-tallas.html (Info)
├── faq.html (Info)
├── envios.html (Info)
├── cambios.html (Info)
├── contacto.html (Contacto/Captura)
├── creator-del-mes.html (Concurso)
├── terminos.html (Legal)
├── privacidad.html (Legal)
├── retracto.html (Legal)
├── reversion.html (Legal)
├── sagrlaft.html (Legal)
│
├── css/
│ ├── styles.css (Estilos globales + componentes)
│ ├── home.css (Estilos específicos del home)
│ ├── catalogo.css (Estilos específicos del catálogo)
│ ├── producto.css (Estilos específicos del producto)
│ └── responsive.css (Media queries centralizadas)
│
├── js/
│ ├── main.js (Lógica global: navbar, WhatsApp, newsletter)
│ ├── data.js (Datos hardcodeados: productos, stories)
│ ├── stories.js (Lógica del carrusel + modal)
│ ├── products.js (Lógica del grid + hover + filtros)
│ ├── producto.js (Lógica detalle: galería, tabs, selector)
│ ├── carrito.js (Lógica del carrito)
│ ├── checkout.js (Lógica del checkout + Wompi)
│ └── auth.js (Firebase Auth - Fase 2)
│
├── imagenes/
│ ├── productos/ (Fotos de productos)
│ ├── stories/ (Fotos/videos del carrusel)
│ ├── ugc/ (Fotos de clientas)
│ ├── ganadoras/ (Hall of Fame)
│ ├── iconos/ (SVGs: carrito, corazón, búsqueda, etc.)
│ └── logo/ (Logo DAMY)
│
├── PROJECT_BRIEF.md (ESTE DOCUMENTO)
├── .firebaserc (Config Firebase - Paso 10)
├── firebase.json (Config Firebase - Paso 10)
└── README.md (Descripción del repo para GitHub)

12. ACUERDO DE TRABAJO SOCIO-SOCIO

Qwen actúa como Socio Técnico Senior: genera código funcional, resuelve integraciones complejas, explica decisiones técnicas clave (no teoría básica).
[Tu Nombre] actúa como Director Creativo y Desarrollador Principal: define diseño, copia/adapta código, gestiona GitHub, toma decisiones de negocio.
Comunicación: Chat actual = canal principal. Si se pierde el chat, este documento (PROJECT_BRIEF.md) es la fuente única de verdad para retomar el proyecto.
Documentación: Este documento se actualiza con cada decisión importante. Reside en la carpeta raíz del repositorio.
Imágenes de referencia: Las 4 imágenes analizadas están documentadas en la sección 5 de este documento. No se necesitan las imágenes originales si este documento está presente.

13. PRÓXIMOS PASOS INMEDIATOS

✅ Análisis de 4 referencias visuales completado.
✅ Programa DAMY Creator of the Month definido.
✅ Estructura de datos diseñada.
✅ Lista maestra y orden de construcción definidos.
✅ Estructura de carpetas definida.
⏳ SIGUIENTE: Recibir logo de DAMY.
⏳ SIGUIENTE: Codificar Paso 1 - Estructura Global (Announcement Bar + Navbar + Footer + WhatsApp widget).
⏳ Configurar Firebase Hosting.
⏳ Primer despliegue.
