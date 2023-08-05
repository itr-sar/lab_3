# laboratorio No. 3 - Scripts #1

#### Instrucciones:
Siga paso a paso los comandos en este documento y grabe un video de su servidor mientras realiza el laboratorio, suba su video a Youtube y entregue el link vía GES.

### Creación de Scripts

1. Crear un nuevo script llamado ```myscript.sh```

  Ingrese las siguientes líneas al script
  
  ```#!/bin/bash```

  ```#mi primer script```
  
  ```#Este script despliega información general de mi sistema.```
 
  ```echo "Hoy es $(date)."```
  
  ```echo "Justo ahora estás en $(pwd) y tu host es $(hostname).```
  

2. Crear ```nano script.sh``` y escribir y lo siguiente

  ```#!/bin/sh```
  
  ```echo “Este es el laboratorio 3”```
  
  ```echo -n “la ruta actual es “```
  
  ```pwd```
  
Correrlo con ```./script.sh ``` (probablemente tenga que habilitar permisos de ejecución). 

3. Crear un script nuevo ```suma.sh```
   
  ```#!/bin/sh```
  
  ```((sum=1950+3400))```
  
  ```echo $sum```
  
  ```((div=2500/5))```
  
  ```echo $div```
  
  ```echo -n “la fecha de hoy es: “```
  
  ```date```
  
Correrlo con ```bash suma.sh```

4. Ahora realizará un ciclo que cuente de 1 a 5
   
Crear un archivo llamado ```while.sh```

Agregar lo siguiente:

  ```#!/bin/bash```
  
  ```condicion=true```
  
  ```contador=1```
  
  ```while [  $condicion  ]```
  
  ```do```
  
  ```echo $contador```
  
  ```if [  $contador -eq 5 ]```
  
  ```then```
  
  ```break```
  
  ```fi```
  
  ```((contador++))```
  
  ```done```

5. Crear un archivo llamado ```input.sh```
   
  ```#!/bin/bash```
  
  ```echo “ingrese su nombre “```
  
  ```read nombre```
  
  ```echo “bienvenido $nombre, la fecha de hoy es $(date)”.```

  Correr el script.

6. Realizar un script que cree un nuevo directorio.
   
7. Crear un script que despliegue el calendario del mes actual.
   
8. Correr ```nano /usr/sbin/adduser``` para ver el script con el que fue hecho el comando adduser.



