# linux

## Distros Recomendadas

- [Debian](https://www.debian.org): mejor distro para personalizar y usar en el trabajo
- [Ubuntu](https://ubuntu.com/download): si es la primera vez que usa linux bueno para uso de usuario y trabajo.
- [linux lite](https://www.linuxliteos.com): en caso de que quieras un linux que consuma poco pero basado en DEBIAN.
- [Kali](https://www.kali.org): para haking y petesting para uso de usuario no es recomendado
- [parrot](https://www.parrotsec.org): para haking o uso de usuario, tiene una version para uso de escritorio o trabajo.
- [Axyl os](https://axyl-os.github.io): Mejor distro de tiling que he visto para trabajo y otros (contruido en arch linux).

## Comandos basicos
Aqui miraras comandos mas simples pero utiles.
### Comandos para Moverte en terminal
Estos comandos son los mas utilizados al momento de moverte en la terminal.

Comando| Nota
---|---
`pwd`|Retorna la direcion donde estas en la terminal
`cd [direccion]`| Para moverte de carpeta
`ls` | Archivos dentro de la carpeta
`ll` | Igual que el **ls** pero te retorna como lista, que es igual a `ls -l` 


### copiar archivo o carpeta
Sintaxis: `cp [archivo a copiar] [ruta a pegar] `

Ejemplo: `cp ~/texto.txt ~/Documents/` 

Con esto se copia el **texto.txt** ala carpeta **Documents**
### Mover archivo o carpeta
Sintaxis: `mv [direcion archivo] [ruta nueva]`
### Eliminar
**Cuidado con el siguiente comando borrar en terminal es permanente**, no existe papelera en terminal, mucho cuidado.

La logica es la misma que muchos otros comandos empiesas con llamarlo y darle el nombre o hubicacion del archivo.

Sintaxis: `rm [archivo]` esta sintaxi borra archivos simples pero no carpetas para borrar una carpeta nesesitas agregar el parametro **-R** para borrar directorios o carpetas, pero te preguntara por cada archivo.
Si quieres borrar sin que te pregunte usa **-Rf** que fuerza o ignora la pregunta de ¿estas seguro?, Quedaria asi `rm -Rf [archivo]`

## Archivos comprimidos
Para descomprimir archivos necesitas algunas herramientas como unzip o unrar como tambien el comando ``tar``, estos tendras que intalarlos si esque no estan. la instalacion depende de tu distro
### Descomprimir
Una recomendacion es usar lo mas posible archivos zip ya que estos se pueden extraer de forma facil tanto en windows como en linux.

Archivo|Paquete |Normal| Con Clave
--|--|--|--
.zip| unzip| `unzip [archivo]`| `unzip -p [password] [archivo]`
.rar| unrar| `unrar x [archivo] [extraer en]` | `unzip -p [password] [archivo] [extraer en]`
.tar.bz2| tar| `tar -xvf [archivo]`| No encontrado aun

