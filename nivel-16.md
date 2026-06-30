## Nivel 16

**Objetivo:** 

**Comandos recomendados:** ssh, telnet, nc, ncat, socat, openssl, s_client, nmap, netstat, ss

**Comandos usados:**

nmap -A -T3 -p 31000-32000 localhost
openssl s_client -quiet -connect localhost:31790
echo "kS0Hf0u5HiXFwKMKFqXvPdOTNGGa0X8V" | ncat --ssl localhost 31790 > /tmp/clave17.key 
scp -P 2220 bandit16@bandit.labs.overthewire.org:/tmp/clave17.key .
chmod 600 clave17.key

**Notas:** nmap facilita mucho la conexión.
hay que extraer la clave limpiando el ruido, guardarla en /tmp para luego guardarla con scp para usarla

**Contraseña:** clave17.key
