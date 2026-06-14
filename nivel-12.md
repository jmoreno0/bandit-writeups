## Nivel 12

**Objetivo:**  The password for the next level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed. For this level it may be useful to create a directory under /tmp in which you can work. Use mkdir with a hard to guess directory name. Or better, use the command “mktemp -d”. Then copy the datafile using cp, and rename it using mv (read the manpages!)

**Comandos recomendados:** grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd, mkdir, cp, mv, file

**Comandos usados:**

pwd
cd /tmp
mkdir "carpetapruebas"
cd carpetapruebas
cp /home/bandit12/data.txt .
xxd -r data.txt hexdump
file hexdump
mv hexdump hexdump.gz
gzip -d hexdump.gz
file hexdump
mv hexdump hexdump.bz
bzip2 -d hexdump.bz
file hexdump
mv hexdump hexdump.gz
file hexdump
tar -xf hexdump
file data5.bin
tar -xf data5.bin
file data6.bin
mv data6.bin data6.bz
file data6
tar -xf data6
file data8.bin
mv data8.bin data8.gz
gzip -d data8.gz
file data8
cat data8

**Notas:** El principio es usar file para sacar el tipo de archivo, renombrarlos con mv para poder decodificar la compresion e ir haciendo esto varias veces hasta llegar al ASCII

**Contraseña:** FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
