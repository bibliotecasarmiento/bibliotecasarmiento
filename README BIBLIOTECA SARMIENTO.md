# Sitio web de la Biblioteca Popular Domingo F. Sarmiento

Versión estática del sitio de la Biblioteca Popular Domingo F. Sarmiento (Río Cuarto, Córdoba), desarrollado como trabajo práctico de la Licenciatura en Diseño, Producción y Realización Audiovisual de la Universidad Nacional de Río Cuarto y publicado en GitHub Pages.

## Enlaces

| Qué | Dirección |
| :---- | :---- |
| Sitio editable (Multisite) | [https\://tcir.comunicampus.org/bibliotecasarmiento/](https://tcir.comunicampus.org/bibliotecasarmiento/) (visualización)&nbsp; |
| Repositorio | [https\://github.com/bibliotecasarmiento/bibliotecasarmiento.git](https://github.com/bibliotecasarmiento/bibliotecasarmiento.git)&nbsp; |
| Versión pública (GitHub Pages) | [https\://bibliotecasarmiento.github.io/bibliotecasarmiento/](https://bibliotecasarmiento.github.io/bibliotecasarmiento/)&nbsp; |
| Respaldo editable institucional | [https\://drive.google.com/file/d/1evuWAXUYR3kPyN2LBGlwplKeEdamgH9T/view?usp=sharing](https://drive.google.com/file/d/1evuWAXUYR3kPyN2LBGlwplKeEdamgH9T/view?usp=sharing) (Drive de la biblioteca) |

&nbsp;

## 1\. Contexto

La Biblioteca Popular Domingo F. Sarmiento es una institución cultural de Río Cuarto, fundada en 1915 por iniciativa de vecinos del barrio Alberdi. Es una organización sin fines de lucro que ofrece espacio de lectura, talleres, capacitaciones y alquiler de salón.

El proyecto consistió en diseñar y publicar su sitio web para que la comunidad pueda conocer la institución, informarse sobre las novedades, asociarse y consultar los servicios. Tiene cinco secciones principales:

- **Inicio:** accesos rápidos (Cómo asociarse, Alquiler del salón, Inscripción a talleres) y novedades.  
- **Servicios:** talleres y alquiler de salón.  
- **Socios:** información y formulario para asociarse.  
- **Quiénes somos:** historia y propuesta de la biblioteca.  
- **Contacto:** datos para comunicarse.

El pie de página reúne el menú, las migas de pan, los íconos de contacto (WhatsApp, correo, Instagram y Facebook) y los créditos.

Materia / cátedra: Taller de Producción Interactiva Para Redes (259). Año: 2026\.

&nbsp;

## 2\. Decisiones de diseño

- **Paleta basada en el escudo.** Marrón de la marca `#7F4D17`, con `#653C10` y `#4A2A0A` como variantes oscuras, beige `#EFE3D0` para las migas de pan y `#D8A557` para las tipografías de los banners. Se eligió el marrón del escudo de la biblioteca para dar unidad al sitio.  
- **Encabezado en tres niveles:** escudo y nombre, barra de menú de borde a borde y migas de pan, para que la persona sepa siempre dónde está.  
- **Menú adaptado a pantallas chicas.** En celular y tablet se reemplaza por un botón de tres rayitas que abre un panel pequeño, y no una pantalla completa.  
- **Pie de página en marrón**, con el mismo menú y los datos de contacto.  
- **Imágenes destacadas con alto limitado** (entradas, páginas y portada), con recorte centrado, para que la información no quede tan abajo.  
- **Novedades en columnas**, con imagen, título y resumen en cada nota, y márgenes laterales en celular.  
- **Enlaces sin subrayados innecesarios:** el título del sitio (que lleva al inicio) cambia de color al pasar el cursor en lugar de subrayarse.  
- **Accesibilidad:** contraste de color entre texto y fondo, textos alternativos en las imágenes necesarias y enlaces identificables.

El diseño se probó en computadora, celular y tablet.&nbsp;

&nbsp;

## 3\. Herramientas

| Herramienta | Uso |
| :---- | :---- |
| WordPress (Multisite de Comunicampus) | Gestor de contenidos y edición del sitio |
| Tema Twenty Twenty-Three | Tema de bloques que se usó como base |
| Editor de bloques / Editor del sitio | Armado de páginas, encabezado, pie y estilos |
| CSS adicional | Personalización del diseño (colores, menú, imágenes, versión móvil) |
| WPForms | Formulario de socios, inscripción a talleres y contacto de la biblioteca |
| Simply Static | Exportación del sitio a HTML, CSS y JavaScript |
| GitHub y GitHub Pages | Repositorio y publicación de la versión estática |
| Claude (Anthropic), asistente de IA | Ayuda para escribir y corregir el CSS adicional. El código se probó y ajustó sobre el sitio real |

&nbsp;

## 4\. Integrantes

- Ana Dama  
- Sofía Bonillas  
- Milagros Santone

Docentes: Sebastián Thüer, Carlos Esteban Pascual, Elias Claudio Asaad. Organización: Biblioteca Popular Domingo Faustino Sarmiento. Contacto institucional: Fiorela Bustos (administradora económica de la biblioteca).

&nbsp;

## 5\. Créditos y licencias

- **WordPress** y el tema **Twenty Twenty-Three** se distribuyen bajo la licencia GPL v2 o posterior.  
- **Escudo y textos institucionales:** pertenecen a la Biblioteca Popular Domingo F. Sarmiento y se usan con su autorización.&nbsp;  
- **Fotografías e ilustraciones:** las fotografías de los libros y los espacios de la biblioteca son de autoría propia.&nbsp;  
- **Tipografías:** Por defecto y Source Serif Pro.&nbsp;  
- **Plugins:** Simply Static y WPForms, con sus respectivas licencias.

&nbsp;

## 6\. Limitaciones

- **Es una copia estática.** La versión de GitHub Pages no tiene panel de administración: los cambios se hacen en WordPress y después hay que volver a exportar y publicar.  
- **Formulario de socios (WPForms).** Los formularios necesitan un servidor, por lo que no funciona en la versión estática.&nbsp;  
- **Comentarios y buscador** no funciona en la versión estática.  
- **Accesibilidad:** se revisaron aspectos básicos, pero no se hizo una auditoría completa.&nbsp;  
- **Dependencia del Multisite.** El sitio editable vive en Comunicampus; si esa plataforma cambia, hay que restaurarlo desde el respaldo.

&nbsp;

## 7\. Continuidad

### Cómo actualizar el sitio

1. Entrar al panel de WordPress del subsitio en Comunicampus y hacer los cambios.  
2. Revisarlos en la página real (con Ctrl \+ F5 para evitar la copia guardada del navegador).  
3. Exportar con **Simply Static** y enviar los archivos al repositorio.  
4. Esperar la publicación en GitHub Pages (entre 1 y 10 minutos, aproximadamente) y verificar.

### Respaldo editable institucional

Se conserva **por separado** de este repositorio, en \[lugar\], e incluye:

- Archivo de contenido exportado desde *Herramientas → Exportar* (`.xml`).  
- Imágenes y archivos de la biblioteca de medios.  
- CSS adicional en un archivo de texto con fecha.  
- Copia de la exportación estática.

### Cómo restaurar el sitio

1. En un WordPress nuevo, instalar el tema Twenty Twenty-Three.  
2. *Herramientas → Importar → WordPress* y subir el archivo `.xml`.  
3. Subir las imágenes a *Medios*.  
4. Pegar el CSS adicional en *Apariencia → Editor → Estilos → CSS adicional*.  
5. Reinstalar los plugins (Simply Static, WPForms).  
6. Revisar menús, encabezado y pie, que dependen del orden de sus bloques.

### Responsables

- Administración del sitio: Sebastián Thüer&nbsp;  
- Referente institucional: Fiorela Bustos&nbsp;

&nbsp;

*Última actualización: 12/11/2026.*