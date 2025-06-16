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

También se usara la terminal de Warp que es un terminal moderno para desarrolladores, diseñado especialmente para sistemas macOS, afirma Khattab, A., Camp, J., Hunter, C., Murphy, P., Sabharwal, A., & Knightly, E. W. (2008).

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

https://github.com/Jonna007/PRACTICAS/blob/main/imagenes/1.png

**Paso 2:** Se creo  una carpeta denominada `proyecto_comandos` y dentro de ella, tres subcarpetas denominadas `documentos`, `imagenes` y `scripts`.

Figura 2. Comando **"mkdir"**.

<img width="348" alt="paso2" src="https://github.com/user-attachments/assets/98302bf7-d92f-475d-9b11-0bee37adee06" />


**Paso 3:** Dentro de la carpeta `documentos`, se creó un archivo llamado `notas.txt` y se  añadieron  tres líneas de texto usando el comando `nano`

Figura 3. Comando **"touch"**..

<img width="318" alt="paso3" src="https://github.com/user-attachments/assets/847ca34a-e873-4d23-b11f-6fc13e9b0949" />
<img width="113" alt="paso3 1" src="https://github.com/user-attachments/assets/473db2c7-f1a9-4c42-b31f-15678896dc51" />


**Paso 4:** Se copio `notas.txt` a la carpeta `scripts` y se modifico su nombre a `backup_notas.txt`.

Figura 4. Comando **"mv"**..

<img width="320" alt="paso4" src="https://github.com/user-attachments/assets/2359749a-8033-4251-8ec6-d0e182857bd0" />


**Paso 5:** Se envió el archivo`backup_notas.txt` a la carpeta `imagenes`.

Figura 5. Comando **"mv"**.

<img width="290" alt="paso5" src="https://github.com/user-attachments/assets/2e21442a-9cb7-4a3a-96fa-b9df29868c28" />


**Paso 6:** Se creó un nuevo archivo llamado `resumen.txt` dentro de la carpeta `documentos` y se redirecionó el contenido de `notas.txt` a este archivo.

Figura 6. Comando **"cat"**.

<img width="308" alt="paso6" src="https://github.com/user-attachments/assets/97b54b30-f484-439b-819d-157a2795c449" />

**Paso 7:** Se añadió una nueva línea de texto sin sobrescribir lo que ya estaba en `resumen.txt`

Figura 7. Comando **"echo"**.

<img width="385" alt="paso7" src="https://github.com/user-attachments/assets/7f2c9a6f-5b9a-4c99-968b-fd461ca9e542" />


**Paso 8:** Se eliminó el archivo `backup_notas.txt` de la carpeta `imagenes` usando el comando `rm`, y luego eliminé la carpeta `imagenes` con `rmdir`estando vacía.

Figura 8. Comando **"rm"**.

<img width="330" alt="paso8" src="https://github.com/user-attachments/assets/a8a842fe-ccf0-4753-a2ab-344119850375" />
<img width="310" alt="paso8 1" src="https://github.com/user-attachments/assets/1adc8340-15f9-47f7-b647-e6acc2dd07d3" />

**Paso 9:** Se extrajo el historial de todos los comandos que se ejecutaron  en un archivo llamado `tarea-s1-nombre_apellido.txt` usando el comando `history`

Figura 9. Comando **"history"**.

<img width="420" alt="paso9" src="https://github.com/user-attachments/assets/a1aca633-03af-409d-8a19-d33915008a35" />

**Paso 10:** Se sustituyó el nombre_apellido" por mi nombre y apellido correspondiente.

Figura 10. Comando **"mv"**.

<img width="522" alt="paso10" src="https://github.com/user-attachments/assets/4beb0ff5-0355-4409-ac25-f3dc162a22ed" />


## 9. Resultados esperados:
    
La práctica no solo permitió aplicar comandos esenciales en la terminal, sino que también fortaleció la lógica de navegación, organización y control de archivos y carpetas en entornos Unix/Linux.

Después de completar todos los pasos, pude manejar mejor la terminal. Logré crear carpetas organizadas y moverme entre ellas sin problema. Practiqué cómo crear archivos, copiar, mover, renombrar y también cómo borrar cosas sin afectar lo demás.

También entendí cómo funciona la redirección y cómo combinar contenido de un archivo a otro, lo cual fue súper útil para automatizar tareas básicas. Finalmente, guardé todo mi historial de comandos en un archivo, lo que me ayudó a revisar qué hice paso a paso. 

El uso de **Warp** en macOS brindó una experiencia más fluida, moderna y visual al trabajar con la terminal, pero sin alterar la esencia de los comandos tradicionales.

En resumen, fue una buena práctica para comprender y dominar de mejor manera los comandos de Linux y aprender a organizarme mejor desde la terminal.

<img width="723" alt="resultado" src="https://github.com/user-attachments/assets/67fae6c3-a389-4a53-866a-7eda54ecea81" />


## 10. Bibliografía

- Khattab, A., Camp, J., Hunter, C., Murphy, P., Sabharwal, A., & Knightly, E. W. (2008). WARP: A flexible platform for clean-slate wireless medium access protocol design. _ACM SIGMOBILE Mobile Computing and Communications Review_, _12_(1), 56-58.

- **Richardson, D.** (2019). _Introducción a la Terminal de Linux_. Linux Foundation.

- Sánchez Anguix, V. (2021). Comandos básicos de Linux para trabajar con el sistema de ficheros.
