# Laboratorio de Esteganografía

Este laboratorio consiste en ocultar un archivo comprimido con contraseña dentro de una imagen usando el comando 'copy /b'.

## Archivos incluidos
- foto.jpg (imagen original)
- mensaje.docx (mensaje original)
- mensaje.rar (archivo comprimido con contraseña)
- foto_con_mensaje.jpg (archivo final con el mensaje oculto)

## Cómo recuperar el archivo oculto
La imagen foto_con_mensaje.jpg se comporta como una imagen normal. Para extraer el archivo oculto, abre directamente el archivo foto_con_mensaje.jpg con la aplicación **7-Zip File Manager**.

1. Abre 7-Zip.
2. En 7-Zip, navega hasta el archivo foto_con_mensaje.jpg.
3. Ábrelo dentro de 7-Zip: verás el contenido oculto (mensaje.rar).
4. Al intentar extraerlo, 7-Zip pedirá la **contraseña** utilizada al comprimir el archivo.
