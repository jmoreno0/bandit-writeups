## Nivel 8

**Objetivo:** The password for the next level is stored in the file data.txt and is the only line of text that occurs only once     

**Comandos recomendados:** man, grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd

**Comandos usados:**

sort data.txt | uniq -u

**Notas:** Usar | permite redirigir la salida de un comando hacia el siguiente, en este caso, con sort se agrupan las lineas iguales, luego sort comprueba cuales se repiten entre las contiguas y con -u muestra solo las que no se repiten

**Contraseña:** EjmOSvuAu7sGAHqHVcBDPirRe9T03kxl
