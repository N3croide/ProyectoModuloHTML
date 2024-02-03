structura de Carpetas y Archivos
index.html: Página principal del sitio web.
styles.css: Archivo principal de estilos CSS que se aplica a toda la aplicación.
images/: Carpeta que contiene las imágenes utilizadas en el proyecto.
resources/: Carpeta que contiene recursos, como fondos y flechas de navegación.
fonts/: Carpeta que podría contener fuentes personalizadas, aunque en este proyecto se utiliza principalmente fuentes del sistema y de Google Fonts.
Reglas Generales
*: Selector universal que aplica reglas a todos los elementos del documento.
margin, padding: Establece márgenes y rellenos en 0 para todos los elementos.
color, background-color: Configura colores de texto y fondo.
font-family: Define la fuente utilizada en el sitio web.
box-sizing: Establece el modelo de caja a border-box.
Estilos de la Página Principal (index.html)
Header (Cabecera)
.cabecera: Establece las reglas para el encabezado de la página.

padding, width: Ajusta el espaciado y el ancho.
display: flex, flex-direction: row: Utiliza flexbox para alinear elementos en fila.
position: relative: Establece posición relativa para algunos elementos.
.nav: Define las reglas para la barra de navegación.

--state-close, --state-open, --state-menu: Variables para animaciones.
grid-template-columns: Distribuye el contenido en dos columnas.
cursor: pointer: Hace que el cursor sea interactivo en elementos clicables.
Cuerpo (Body)
.imagenEmpresa: Aplica estilos a la sección de imágenes de la empresa.

position: relative: Permite posicionar elementos hijos con respecto a este contenedor.
overflow: hidden: Oculta el contenido que se desborda.
.controlR, .controlL: Estilos para los controles de desplazamiento de imágenes.

position: absolute: Posiciona los controles en la parte superior derecha/izquierda.
width: 4%: Define el ancho de los controles.
background-color: rgba(255, 255, 255, 0): Hace el fondo transparente.
label: Define estilos para las etiquetas de los controles.
.slide: Contenedor para las imágenes deslizantes.

display: flex, width: 300%: Alinea las imágenes en fila y permite el desplazamiento.
transition: Agrega una animación suave al cambio de imágenes.
Productos
.productos, .producto: Define reglas para la sección de productos.
background-color, box-shadow, border-radius: Agrega sombra y bordes redondeados.
margin, width, height: Ajusta márgenes, ancho y alto.
overflow: hidden: Oculta el contenido que se desborda.
Footer (Pie de Página)
.informacionFooter: Establece reglas para la sección de información en el pie de página.

border-radius: Agrega bordes redondeados a la parte superior del pie de página.
background-color: Configura el color de fondo.
.icons: Alinea e indica reglas para los íconos en el pie de página.

Estilos de Popup
.overlay, #popupBody: Configuraciones para el fondo del popup y el cuerpo del popup.

position: fixed: Fija la posición del fondo del popup.
z-index: Establece la capa de apilamiento para el popup.
visibility, opacity: Controla la visibilidad y la opacidad del popup.
backdrop-filter: Aplica un desenfoque al fondo del popup.
transition: Agrega animación de transición.
.popupContent, .imgProd: Estilos para el contenido y las imágenes del popup.

display: grid, grid-template-columns, grid-template-rows: Utiliza grid para organizar elementos.
Estilos de Galería
@keyframes galeria: Define una animación para la galería de imágenes.
.test:hover img: Aplica la animación a la imagen en hover.
Estilos de Catálogo de Productos
.prodCatalogo: Reglas para el catálogo de productos.
display: grid, grid-template-rows: Utiliza grid para organizar elementos.
Estilos de Botones
.botones a, .botones a:hover: Define reglas para los botones y su estado hover.
text-decoration, font-size, background-color: Ajusta el texto decorativo, el tamaño de la fuente y el color de fondo.
Fuentes
@import url('https://fonts.googleapis.com/css2?family=Roboto+Slab&display=swap'): Importa la fuente Roboto Slab desde Google Fonts.
Medios Responsivos
@media (min-width:768px): Define reglas específicas para pantallas más grandes.
