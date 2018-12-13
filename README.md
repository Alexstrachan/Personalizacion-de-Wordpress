# practica08

# Personalización de Wordpress

Ahora vamos a realizar una guía de instalación de un ``theme`` de Wordpress y de algunos ``plugins``.

En la isntalación de los Plugins, escogeremos los más populares dentrode la comunidad:

* ContactForm7
* Beaver Builder
* GDPR
* Custom Post Type UI
* Easy WP SMTP
* WP Super Cache
* WooComerce
* JetPack

## Instalación del ``Theme`` 

### Instalación por FTP:

1. Accede a una página donde se puedan descargar theme de WP.
2. `` Leer los ficheros "readme.txt `` por si hay alguna instrucción a tener en cuenta a la hora de instalar dicho theme.
3. Sube por FTP la carpeta descomprimida con el theme a tu directorio ``/wp-content/themes/`` de modo que la ruta quede: ``/wp-content/themes/"theme"``.
4. Accede al panel de administración , en la pestaña de presentación, y encontraras en la lista de plantillas, la que acabas de subir. Para poder usarla tendrás que activarla.

### Instalación temas Oficiales de WP:

En el escritorio de WP tenemos un instalador que nos permite instalar sus propios temas. Desde este instalador podremos hacer una busquedo gracias a su buscador de palabras clave y directamente isntalarlos y activarlo.

## Instalación de Plugins:

La ruta para instalar Plugins sería la siguiente:

``  Plugins > añadir plugins > contact form 7 > instalar > activar > ¡listo! ``

Ahora vamos a hacer una lista con varios Plugins y su instalación:

### Contact Form 7

Con este Plugin podremos Crear un formulario de contacto para nuestro sitio web.

Te aparecerá un nuevo item en el menú principal de WordPress, generalmente debajo de “Comentarios”que se llamará Contacto.

El plugin ya incorpora un formulario básico predefinido y útil para cualquier web en el que se solicitan campos como Nombre, email, asunto, mensaje y el botón de enviar. La verdad es que estas son las necesidades del usuario medio. Un modo simple de mantener contacto desde la web.

Nos aparecerá 4 pestañas: ``Formulario`` , `` Correo Electronico `` , `` Mensajes`` y `` Ajustes Adicionales``.

#### Formulario

Es donde lo creamos mediante los campos que solicitaremos a nuestros usuarios.

#### Correo Electronico

Desde esta pestaña accedes a toda la configuración del correo electrónico que recibes y también (si lo activas) configuras la copia o acuse de recibo que recibe tu visitante.

#### Mensajes

La pestaña “Mensajes” personaliza los mensajes predefinidos.

#### Ajustes Adicionales

Permite ajustes avanzados (para casos muy concretos).

### GDPR

Este plugin sirve para ayudar al controlador, al procesador de datos y al oficial de protección de datos (OPD) en sus esfuerzos de cumplir las obligaciones y derechos emanados del RGPD.

En las opciones de los ajustes, puedes seleccionar la página de política de privacidad a rastrear y registrar el consentimiento.

Al iniciar sesión, el usuario debe aceptar la política de privacidad descrita en el sitio. Si el usuario no da su consentimiento, no se registrará ni iniciará sesión.

Si el administrador del sitio actualiza el contenido de la página de la política de privacidad, el cambio se registrará y se notificará al administrador que debe avisar a los usuarios en el próximo inicio de sesión para solicitar el nuevo consentimiento. Además, el mensaje de advertencia se puede desactivar en caso de pequeñas correcciones o errores.

### Beaver Builder.

Es el mejor Page Builder que hay ahora mismo en el mercado. 

#### Funcionalidades 

* Plugin: Se trata del plugin que viene con la licencia estandar, el cual se instalar en tu plantilla de WP por el método tradicional y lo configuras con un panel fácil y manejable.

* Beaver Theme: plantilla de WP.
* White label: Pensado para agencias que alojan webs de clientes. El cliente en ningún momento verá el logo, sino el de la agencia.
* Beaver theme: Extensión del plugin creado en 2017. 

#### Módulos Básicos. 

* Audio: te permite insertar un audio desde tu disco local o desde un link.
* Botón: puedes crear un botón y customizarlo a tu gusto.
* HTML: te permite insertar un código HTML, CSS, Javascript o lo que necesites a nivel de desarrollo.
* Título: crea un título y le da estilos.
* Foto: inserta una foto o imagen desde tu ordenador o desde una URL.
* Separador: separa un contenido de otro de una manera elegante.
* Editor de texto: te permite editar texto con el editor de textos de siempre.
* Vídeo: te permite subir un vídeo desde tu ordenador o insertarlo desde una URL o por código de embebido.

### Shortcodes Ultimate.

Shortcodes Ultimate es una colección completa de varios elementos visuales y funcionales, que puede utilizar en el editor de publicaciones, widgets de texto o incluso en archivos de plantillas. Con Shortcodes Ultimate puedes crear fácilmente pestañas, botones, cuadros, controles deslizantes y carruseles, videos.

#### shortcodes disponibles.
```
Heading       Tabs          Spoiler     Accordion
Divider       Spacer        Highlight   Label
Quote         Pullquote     Dropcap     Columns
List          Button        Service     Box
Note          Expand        Lightbox    Tooltip
Private       YouTube       Vimeo       Dailymotion
Audio         Video         Table       Permalink
Members       Guests        RSS         Menu
Sub pages     Siblings      Document    Google map
Slider        Carousel      Gallery     Posts
Dummy text    Dummy image   Animation   Meta data
User data     Post data     Template    QR code
Scheduler
```
### Disable comments

Este complemento permite a los administradores deshabilitar globalmente los comentarios en cualquier tipo de publicación (publicaciones, páginas, archivos adjuntos, etc.) para que esta configuración no pueda ser anulada para publicaciones individuales. También elimina todos los campos relacionados con comentarios de las pantallas de edición y edición rápida. En instalaciones de varios sitios, se puede usar para deshabilitar comentarios en toda la red.

### Fullwidth templates

Podremos intercalar este plugin con nuestro builder para poder remover la pagina de titulo, los comentarios, barra lateral, etc.

### Editor Clasico.

Tras la actualización de WP 5.0 tendremos que instalar este plugin si queremos tener el editor clasico para nuestras entradas.

### Advances Custom Fields.

Plugin super completo para poder crear grupos de campos que podremos insertar en nuestras entradas a modo de "plantilla" para facilitar y agilitar la elaboración de las mismas.
