# Pracrica4
Primero, para desenriptar las imágenes metemos un comando en bash para pasar de una imagen encriptada, que está en formato txt a una imagen en formato png (imágenes mystery_img1.txt y mystery_img2.txt)
Dicho comando es "base64 -d mystery_img1.txt > mistery_decode1.png" y así se podría desencriptar, para la imagen número 2 solo es necesario cambiar los 1 por 2.

Luego, necesitamos encriptar un archivo de formato C, para esto, metemos el siguiente comando en la terminal: "base64 hola_mundo.c > hola_mundo_encode.txt" y tendríamos el archivo C encriptado y en formato txt, si lo desencriptamos tendremos el mismo contenido del archivo.
