![screenshot bfhmail](/screenshots/bfhmail.png)
Autor      | cleanet
------------|----------
Website  |  https://www.cleanet.alwaysdata.net
Email      |  cleannet29@gmail.com

Script para hacer ataques de fuerza bruta a Hotmail, Gmail y sitios web (sin captchas)

El archivo 'main' te permite elegir, que quieres hacer: Generar a diccionario y después con ese diccionario hacer fuerza bruta o directamente fuerza bruta.

El archivo 'dictionary' genera diccionarios de contraseñas
El archivo 'attack' se encarga de atacar a servicios
### DICTIONARY
Si generas diccionarios, es importante que, si el diccionario es grande. Te aconsejo que lo guardes en un archivo

Si la longitud mínima de la password es 2 y la máxima es 5, o más. Esto generará un diccionario grande.

Después de generar the contraseñas, el script te permite continuar con el script 'attack' with the diccionario generado incluido. (Esto no siempre funciona)
### ATTACK
Mientras el script ataca, tú puedes pararlo con Ctrl+C y guardar el progreso, para más tarde continuar.




Script for do brute force's attacks to Hotmail, Gmail and websites (without captchas)

The 'main' file allow you choose, what you want do: Generate a dictionary and after do brute force or directly brute force.

The 'dictionary' file generate passwords' dictionaries
The 'attack' file order of attack to services.
<hr style="border:2px solid; background:black;color:black;">
### DICTIONARY
If you generates dictionaries, is important, that, if the dictionary is big, I suggest you that, you keep these dictionary in a file.

If the minium length password is 2 and maxium length password is 5, or more. This will generate a big dictionary

After of genrate the passwords, it allow you continue with the 'attack' file, with dictionary included. (It doesn't always work)
### ATTACK
While this script has brute force, you can stop it, with Ctrl+C, and storage the progress. For later, continue.
# LIBRARIES
* lib
* smtplib
* random
* mechanize
* os
* sys
* readline
* subprocess
* time
