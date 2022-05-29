# linux

##Distros Recomendadas

- [Debian](https://www.debian.org): mejor distro para personalizar y usar en el trabajo
- [Ubuntu](https://ubuntu.com/download): si es la primera vez que usa linux bueno para uso de usuario y trabajo.
- [linux lite](https://www.linuxliteos.com): en caso de que quieras un linux que consuma poco pero basado en DEBIAN
- [Kali](https://www.kali.org): para haking y petesting para uso de usuario no es recomendado
- [parrot](https://www.parrotsec.org): para haking o uso de usuario, tiene una version para uso de escritorio o trabajo
- [Axyl os](https://axyl-os.github.io): Mejor distro de tiling que he visto para trabajo y otros (contruido en arch linux)

## Comandos basicos
Aqui miraras comandos mas simples pero utiles
### Comandos para Moverte en terminal
estos comandos son los mas utilizados al momento de moverte en la terminal.

comando| nota
---|---
`pwd`|retorna la direcion donde estas en la terminal
`cd [direccion]`| para moverte de carpeta
`ls` | archivos dentro de la carpeta
`ll` | igual que el **ls** pero te retorna como lista, que es igual a `ls -l` 


### copiar archivo o carpeta
sintaxy: `cp [archivo a copiar] [ruta a pegar] `

ejemplo: `cp ~/texto.txt ~/Documents/` 

con esto se copia el **texto.txt** ala carpeta **Documents**
### Mover archivo o carpeta
Sintaxy: `mv [direcion archivo] [ruta nueva]`
### Eliminar
**Cuidado con el siguiente comando borrar en terminal es permanente**, no existe papelera en terminal,
mucho cuidado.

la logica es la misma que muchos otros comandos empiesas con llamarlo y darle el nombre o hubicacion del archivo.

sintaxy: `rm [archivo]` esta sintaxy borra archivos simples pero no carpetas para borrar una carpeta nesesitas agregar el parametro **-R** para borrar directorios o carpetas, pero te preguntara por cada archivo.
si quieres borrar sin que te pregunte usa **-Rf** que fuerza o ignora la pregunta de ¿estas seguro?, Quedaria asi `rm -Rf [archivo]`

## Archivoz comprimidos
para descomprimir archivos necesitas algunas herramientas como unzip o unrar como tambien el comando tar, estos tendras que intalarlos si esque no estan. la instalacion depende de tu distro
### descomprimir
una recomendacion es usar lo mas posible archivos zip ya que estos se pueden extraer de forma facil tanto en windows como en linux.

archivo|paquete |normal| con clave
--|--|--|--
.zip| unzip| `unzip [archivo]`| `unzip -p [password] [archivo]`
.rar| unrar| `unrar x [archivo] [extraer en]` | `unzip -p [password] [archivo] [extraer en]`
.tar.bz2| tar| `tar -xvf [archivo]`| no encontrado aun

