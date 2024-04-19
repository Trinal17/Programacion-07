# Ejercicios para practicar con los conceptos teóricos aprendidos


## Ejercicio 1: POKEDEX

## Ejercicio 2: PlagioQuijote

## Ejercicio 3: FIND FILE WEB. Buscando a Wally

![alt text](image.png)

1. Vas a crear un proyecto web que encuentre un archivo en una estructura de directorios. Debe hacerlo usando recursividad.

2. Vamos a esconder tres archivos en la estructura de subdirectorios del directorio home del usuario.
Llama a los archivos:
- WALLY.TXT
- NEMO.TXT
- CHENCHO.TXT
- NO_EXISTE.TXT

Guárdalos en diferentes subdirectorios.

3. En la página index.html contendrá un formulario con una lista desplegable donde saldrán esos tres nombres para que el usuario elija uno y se realice la llamada al Servlet **FindServlet.java**

4. Dicho Servlet devolverá una página HTML indicando según los diferentes casos:
- El archivo no se ha encontrado.
- El archivo XXXX se ha encontrado en la siguiente ruta absoluta YYYYYYYYYYYYYYYYYYY


## Ejercicio 4: Buffer en binario

Escribe un programa en Java que utilice BufferedInputStream y BufferedOutputStream para copiar un archivo JPG desde la tarjeta SD (simulada como un archivo en el sistema de archivos) a la unidad de disco duro externo (también simulada como un archivo en el sistema de archivos).

Usa estas clases:

```
    Path pathBase = Paths.get(System.getProperty("user.home"),"BUFFER");
    Path tarjetaSD = Paths.get("tarjeta_sd","archivo_original.jpg");
    Path discoDuroExterno = Paths.get("disco_externo","archivo_copia.jpg");
```

El tamaño del buffer será 4 KB:
```
byte[] buffer = new byte[4096];
```

Copia una imagen cualquiera en el subdirectorio tarjet_sd y prueba que se realiza correctamente la copia.

Puedes ver el ejemplo del GitHub: https://github.com/profeMelola/Programacion-07-2023-24/blob/main/EJEMPLOS_FlujoEntrada/src/es/daw/bytes/buffered/CopyBytes.java


## Ejercicio 5: Serializar

