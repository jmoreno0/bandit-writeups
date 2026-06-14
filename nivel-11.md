## Nivel 11

**Objetivo:** The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions 

**Comandos recomendados:** man, grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd

**Comandos usados:**

cat data.txt | tr "a-zA-Z" "n-za-mN-ZA-M"

**Notas:** En este caso, el man tr es un poco confuso, me ha sido mas util buscar por otro lado
Es importante hacer la traduccion de las mayusculas de forma explícita, ya que si no no se traducen

**Contraseña:** 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
