## FileEasy - Biblioteca para el Manejo de Archivos 


FileEasy es una biblioteca de Java que proporciona operaciones sencillas para el manejo de archivos, como copiar, leer, escribir, crear, mover y eliminar archivos.

## Uso

Para usar FileEasy en tu proyecto Java, sigue estos pasos:

1. **Descarga y Agrega FileEasy a tu Proyecto:**

    Puedes descargar la última versión de FileEasy desde [enlace_de_descarga](https://github.com/ACOSTA03/FileEasy/blob/main/FileEasy.jar). Luego, agrega la biblioteca JAR a tu proyecto.

2. **Importa la Clase `fileEasy` en tu Código:**

    Importa la clase `fileEasy` en tus archivos Java donde desees utilizarla.

    ```java
    import com.fileEasy.fileEasy;
    ```

3. **Crea una Instancia de FileEasy:**

    Para utilizar las funciones de FileEasy, primero crea una instancia de la clase `fileEasy` proporcionando una ruta de archivo o carpeta como parámetro.

    ```java
    fileEasy archivo = new fileEasy("ruta/al/archivo.txt");
    ```

4. **Utiliza las Funciones de FileEasy:**

    A continuación, puedes usar las funciones de FileEasy según tus necesidades, como copiar, leer, escribir, crear, mover o eliminar archivos.

    ```java
    String contenido = archivo.leerArchivo();
    archivo.escribirArchivo("Nuevo contenido del archivo");
    archivo.crearArchivo("nueva_ruta/nuevo_archivo.txt");
    archivo.copiarArchivo("nueva_ruta/otro_archivo.txt");
    archivo.moverArchivo("nueva_ruta/otro_archivo.txt");
    archivo.eliminarArchivo();
    ```

## Ejemplos

Aquí hay algunos ejemplos de cómo utilizar FileEasy en tu proyecto:

```java
fileEasy archivo = new fileEasy("ruta/al/archivo.txt");
String contenido = archivo.leerArchivo();
archivo.escribirArchivo("Nuevo contenido del archivo");
archivo.crearArchivo("nueva_ruta/nuevo_archivo.txt");
archivo.copiarArchivo("nueva_ruta/otro_archivo.txt");
archivo.moverArchivo("nueva_ruta/otro_archivo.txt");
archivo.eliminarArchivo();
```
Estos son ejemplos simples para las funciones disponibles en FileEasy. Puedes adaptarlos a tus necesidades específicas.

## Documentación Javadoc

La documentación Javadoc detallada de FileEasy se encuentra disponible en línea. Puedes acceder a ella para obtener información detallada sobre cómo utilizar la biblioteca y sus métodos. A continuación, se proporciona el enlace:

[Documentación Javadoc de FileEasy](https://github.com/ACOSTA03/FileEasy/tree/main/docs)
