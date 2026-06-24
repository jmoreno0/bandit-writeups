## Nivel 6

**Objetivo:** The password for the next level is stored somewhere on the server and has all of the following properties:

    owned by user bandit7
    owned by group bandit6
    33 bytes in size                                                                                   

**Comandos recomendados:** ls , cd , cat , file , du , find

**Comandos usados:**

find / -size 33c -user bandit7 -group bandit6 2>/dev/null

**Notas:** find / indica una busqueda en todo sistema desde el directorio principal, usar 2>/dev/null para descartar los errores

**Contraseña:** Bmnnvf82KzQlfxgAI2d1zYbr1u9pr3E3
