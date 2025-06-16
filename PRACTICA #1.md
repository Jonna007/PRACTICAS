# Practica Comandos de Linux
## 1. Titulo
**Practica No 1**: Comandos Linux en la Terminal
## 2. Tiempo de duración
La práctica se realizón aproximandamente en unas 2 horas
## 3. Fundamentos:

Esta práctica se centra en los comandos básicos de Linux orientados a la gestión de archivos y directorios. Dominar estos comandos permite al usuario realizar operaciones fundamentales como crear, mover, copiar, eliminar archivos, y estructurar carpetas de manera eficiente desde la terminal.

Entre los comandos utilizados destacan:

mkdir: crea directorios.

touch: crea archivos vacíos.

echo: escribe texto y permite redirecciones.

cat: muestra el contenido de archivos.

cp, mv: copian o mueven archivos.

rm, rmdir: eliminan archivos y carpetas.

history: muestra los comandos ejecutados.

La eliminación de archivos y carpetas se lleva a cabo con los comandos `rm` y `rmdir`.Estos  comandos permiten borrar archivos y carpetas de manera controlada

Además, se emplea la redirección de contenido con > (sobrescribir) y >> (añadir), permitiendo generar nuevos archivos a partir de otros.

Este conocimiento es esencial en administración de servidores, automatización con scripts y uso de contenedores como Docker, donde muchas operaciones requieren terminal.


## 4. Conocimientos previos.
   
Para realizar esta practica es necesario conocer sobre Linux, que se define según **Richardson, D.** (2019) como un sistema operativo (SO) open source que creó Linus Torvalds en 1991. y que gracias a su comunidad internacional de aficionados, hoy podemos encontrarlo en todo tipo de dispositivos, desde sistemas de puntos de venta hasta las supercomputadoras más potentes del mundo. 

Un comando Linux es un programa o utilidad que se ejecuta en la CLI, una consola que interactúa con el sistema a través de textos y procesos. Es similar al Símbolo del sistema en Windows, algunos comandos básicos de Linux como `cd`, `ls`, `cp`, y `mv`, según Sánchez Anguix, V. (2021).

Los comandos de Linux se ejecutan en el terminal pulsando "Enter" al final de la línea. Puedes ejecutar comandos para realizar diversas tareas, desde la instalación de paquetes hasta la gestión de usuarios y la manipulación de archivos.

También se usara la terminal de Warp que es un terminal moderno para desarrolladores, afirma Khattab, A., Camp, J., Hunter, C., Murphy, P., Sabharwal, A., & Knightly, E. W. (2008).

## 5. Objetivos a alcanzar
   
- Crear una estructura de carpetas en un directorio.
- Manipular los archivos como crear, copiar, mover, eliminar.
- Aplicar redirección y concatenación de archivos.
- Eliminar archivos y directorios de manera controlada.
- Volcar el historial de comandos a un archivo y presentarlo como parte de la entrega.
  
## 6. Equipo necesario:
  
- Computador con Windows 11 Home
- **Procesador:** AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx     2.10 GHz
- **Memoria:** 8 GB 
- Conexión a Internet para el material de apoyo
- Terminal en Warp

## 7. Material de apoyo.
   
- **Guía oficial de comandos Linux**: Linux Command Cheat Sheet
- **Documentación de Warp** para windows.
- **Cheat sheet de Linux**: Para recordar comandos rápidos.
- Guía de asignatura proporcionada por el docente
- Video Material de Apoyo
- Sitio oficial de Docker
  
## 8. Procedimiento

**Paso 1:** Verificación de la ruta completa del directorio actual en la que se esta trabajando, a través de pwd .

Figura 1. Comando **"pwd"**.

![image](https://github.com/user-attachments/assets/28f32f6d-e289-4dfa-a43c-2b230a4e469b)


**Paso 2:** Se creo  una carpeta denominada `proyecto_comandos` y dentro de ella, tres subcarpetas denominadas `documentos`, `imagenes` y `scripts`.

Figura 2. Comando **"mkdir"**.

![image](https://github.com/user-attachments/assets/fdf8d50b-cbe7-4635-91b5-ce1b1c73d174)



**Paso 3:** Dentro de la carpeta `documentos`, se creó un archivo llamado `notas.txt` y se  añadieron  tres líneas de texto usando el comando `nano`

Figura 3. Comando **"notepad"**..

![image](https://github.com/user-attachments/assets/e47d8996-dfd0-410d-8205-d1dc65f63bd5)
![image](https://github.com/user-attachments/assets/9f8e0e7b-4306-4380-bf08-7b8a58058755)



**Paso 4:** Se copio `notas.txt` a la carpeta `scripts` y se modifico su nombre a `backup_notas.txt`.

Figura 4. Comando **"mv"**..

![image](https://github.com/user-attachments/assets/21d1a3ad-a903-4a66-bceb-8108053e1829)
![image](https://github.com/user-attachments/assets/cca94d20-ad98-4486-856a-fbcd5b10effa)


**Paso 5:** Se envió el archivo`backup_notas.txt` a la carpeta `imagenes`.

Figura 5. Comando **"mv"**.

![image](https://github.com/user-attachments/assets/4beb23e9-2f38-42a4-8bfc-31be97058dca)



**Paso 6:** Se creó un nuevo archivo llamado `resumen.txt` dentro de la carpeta `documentos` y se redirecionó el contenido de `notas.txt` a este archivo.

Figura 6. Comando **"cat"**.

![image](https://github.com/user-attachments/assets/8924f456-72f3-453c-9d62-61ea77af23d5)
![image](https://github.com/user-attachments/assets/98d4ab94-a1ae-4b9e-ab08-307c7963e0a9)


**Paso 7:** Se añadió una nueva línea de texto sin sobrescribir lo que ya estaba en `resumen.txt`

Figura 7. Comando **"echo"**.

![image](https://github.com/user-attachments/assets/cb2bf1d7-bea4-4dd1-9b97-22a91ed47d57)



**Paso 8:** Se eliminó el archivo `backup_notas.txt` de la carpeta `imagenes` usando el comando `rm`, y luego eliminé la carpeta `imagenes` con `rmdir`estando vacía.

Figura 8. Comando **"rm"**.

![image](https://github.com/user-attachments/assets/faf1acec-90a6-43c2-bd2a-deeab3ada77c)
![image](https://github.com/user-attachments/assets/a974d901-9976-43e6-8a1b-d9b2468561c2)


**Paso 9:** Se extrajo el historial de todos los comandos que se ejecutaron  en un archivo llamado `tarea-s1-nombre_apellido.txt` usando el comando `history`

Figura 9. Comando **"history"**.

![image](https://github.com/user-attachments/assets/22c187c3-9d5a-44d4-ad9b-21e911c2e805)


**Paso 10:** Se sustituyó el nombre_apellido" por mi nombre y apellido correspondiente.

Figura 10. Comando **"mv"**.

![image](https://github.com/user-attachments/assets/06a0dcd7-04fc-425a-bf41-990b5b7eb8fd)


## 9. Resultados esperados:
    
La práctica no solo permitió aplicar comandos esenciales en la terminal, sino que también fortaleció la lógica de navegación, organización y control de archivos y carpetas en entornos Unix/Linux.

Después de completar todos los pasos, pude manejar mejor la terminal. Logré crear carpetas organizadas y moverme entre ellas sin problema. Practiqué cómo crear archivos, copiar, mover, renombrar y también cómo borrar cosas sin afectar lo demás.

También entendí cómo funciona la redirección y cómo combinar contenido de un archivo a otro, lo cual fue súper útil para automatizar tareas básicas. Finalmente, guardé todo mi historial de comandos en un archivo, lo que me ayudó a revisar qué hice paso a paso. 

El uso de **Warp**  brindó una experiencia más fluida, moderna y visual al trabajar con la terminal, pero sin alterar la esencia de los comandos tradicionales.

En resumen, fue una buena práctica para comprender y dominar de mejor manera los comandos de Linux y aprender a organizarme mejor desde la terminal.


![image](https://github.com/user-attachments/assets/fa333449-0342-4be5-912c-99b8159d60e2)


## 10. Bibliografía

- Khattab, A., Camp, J., Hunter, C., Murphy, P., Sabharwal, A., & Knightly, E. W. (2008). WARP: A flexible platform for clean-slate wireless medium access protocol design. _ACM SIGMOBILE Mobile Computing and Communications Review_, _12_(1), 56-58.

- **Richardson, D.** (2019). _Introducción a la Terminal de Linux_. Linux Foundation.

- Sánchez Anguix, V. (2021). Comandos básicos de Linux para trabajar con el sistema de ficheros.
