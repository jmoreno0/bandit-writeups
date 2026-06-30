## Nivel 18

**Objetivo:** The password for the next level is stored in a file readme in the homedirectory. Unfortunately, someone has modified .bashrc to log you out when you log in with SSH.

**Comandos recomendados:** ssh, ls, cat

**Comandos usados:**

ssh bandit18@bandit.labs.overthewire.org -p 2220 "ls"
ssh bandit18@bandit.labs.overthewire.org -p 2220 "cat readme" 

**Notas:** Acabar el login con un comando entre "" ejecuta el comando al acceder, funcionando antes de que me expulse de la sesión

**Contraseña:** KpsOfPkcP7i1FlIExk2QEjyt6dw8dxZI
