## Nivel 5 

**Objetivo:** The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

    human-readable
    1033 bytes in size
    not executable                                                                                                                    

**Comandos recomendados:** ls , cd , cat , file , du , find

**Comandos usados:**

ls
cd inhere
ls
man find
find -size 1033c ! -executable
cd ./maybehere07
cat ./.file2

**Notas:** Se usa find con la flag size para filtrar el tamaño, con ! indico que lo siguiente es lo contrario, en este caso, no ejecutable
usar tab 2 veces muestra posibles opciones, como autocompletar el comando con varias opciones 

**Contraseña:** HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
