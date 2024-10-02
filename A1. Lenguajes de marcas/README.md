1. **Indica qué es un lenguaje de marcas**
- Es un sistema de notación que utiliza etiquetas o marcas para estructurar y presentar información en un documento. Estas etiquetas proporcionan información adicional sobre la estructura del texto o su formato de presentación

2. **Características generales de los lenguajes de marcas.**
   - Uso de etiquetas: Utilizan etiquetas o marcas para definir la estructura y el formato del contenido. Estas etiquetas suelen estar delimitadas por corchetes angulares.
   - Jerarquía y anidamiento: Permiten la creación de estructuras jerárquicas mediante el anidamiento de etiquetas. Esto ayuda a organizar el contenido de manera lógica y coherente.
   - Separación de contenido y presentación: En muchos lenguajes de marcas, como HTML y XML, el contenido y su presentación están separados. Esto permite que el mismo contenido se presente de diferentes maneras según el contexto.
   - Extensibilidad: Son extensibles, lo que significa que se pueden crear nuevas etiquetas o atributos según las necesidades específicas del usuario o la aplicación.
   - Legibilidad: Están diseñados para ser legibles tanto por humanos como por máquinas, facilitando la edición y el procesamiento automatizado.
   - Interoperabilidad: Facilitan la interoperabilidad entre diferentes sistemas y plataformas, permitiendo que la información se comparta y reutilice fácilmente.

3. **Clasifica los lenguajes de marcas e identifica los más relevantes.**
Lenguajes de marcas estructurales:
HTML
XML
Markdown
Lenguajes de marcas de presentación:
CSS
Lenguajes de marcas semánticos:
RDF
JSON-LD
Otros lenguajes relevantes:
SVG
YAML
4. **Indica los distintos ámbitos de aplicación de los lenguajes de marcas.**
- Desarrollo web: HTML y CSS son fundamentales para crear y estilizar páginas web.
- Intercambio de datos: XML y JSON se utilizan para la transferencia de datos entre aplicaciones.
- Documentación técnica: LaTeX y Markdown son populares en la creación de documentos académicos y documentación técnica.
- Geolocalización: KML se usa para representar datos geográficos.
- Calendarios y contactos: iCalendar y vCard son usados para el intercambio de información de eventos y contactos.
5. **Inserta un trozo de código de cada uno de los lenguajes de marcas que se indican a continuación. Añadir a cada trozo de código un pequeño resumen sobre su estructura y la aplicación asociada que los procesa:**
 1.  HTML 
   Resumen: HTML (HyperText Markup Language) se utiliza para estructurar contenido en la web. Se compone de elementos definidos por etiquetas (como h1 para encabezados y p para párrafos). Los navegadores procesan HTML para renderizar páginas web.
  ```
   <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Ejemplo de HTML</title>
</head>
<body>
    <h1>Hola, mundo!</h1>
    <p>Este es un párrafo de ejemplo en HTML.</p>
</body>
</html>
```
2.  iCalendar
   Resumen: iCalendar es un formato para intercambiar información sobre eventos de calendario. Se estructura en bloques que definen el evento (BEGIN:VEVENT y END:VEVENT), con propiedades como SUMMARY, DTSTART y DTEND que indican el título y la duración del evento. Aplicaciones de calendario como Google Calendar pueden procesar este formato.
   ```
    BEGIN:VCALENDAR
    VERSION:2.0
    BEGIN:VEVENT
    SUMMARY:Reunión
    DTSTART:20240402T090000Z
    DTEND:20240402T100000Z
    END:VEVENT
    END:VCALENDAR
   ```
3.  vCard 
  Resumen: vCard es un formato para intercambiar información de contacto. Se compone de campos que definen detalles como el nombre (FN), correo electrónico (EMAIL) y teléfono (TEL). Los clientes de correo y aplicaciones de gestión de contactos pueden importar este formato.
  ```
BEGIN:VCARD
VERSION:3.0
FN:Juan Pérez
EMAIL:juan.perez@example.com
TEL:+34123456789
END:VCARD
```

4.  KML
   Resumen: KML (Keyhole Markup Language) se utiliza para representar datos geográficos y es procesado por aplicaciones como Google Earth. Utiliza una estructura basada en XML donde los elementos definen características geográficas, como puntos, líneas y polígonos.
   ```
   <kml xmlns="http://www.opengis.net/kml/2.2">
    <Placemark>
        <name>Parque Central</name>
        <Point>
            <coordinates>-73.968285,40.785091,0</coordinates>
        </Point>
    </Placemark>
</kml>
```
5. RSS
   Resumen: RSS (Really Simple Syndication) es un formato para syndicar contenido web. Se compone de un canal que incluye múltiples ítems (noticias). Los lectores de RSS procesan este formato para mostrar actualizaciones de contenido de manera ordenada y accesible.
   ```
   <rss version="2.0">
    <channel>
        <title>Noticias Ejemplo</title>
        <link>https://www.ejemplo.com</link>
        <description>Últimas noticias del mundo.</description>
        <item>
            <title>Título de la noticia</title>
            <link>https://www.ejemplo.com/noticia1</link>
            <description>Descripción breve de la noticia.</description>
        </item>
    </channel>
</rss>
```