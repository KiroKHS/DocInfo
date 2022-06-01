# Herramientas de terminal

Hay muchas herramientas en las terminales que se pueden instalar en linux y algunas otra en windows, por ejemplo youtube-dl y muchos otros.

## Descargar videos de youtube 

Aqui usaremos la herramientas [**youtube-dl**](https://github.com/ytdl-org/youtube-dl/blob/master/README.md#installation)

Una forma facil de instalar es con [python](https:www.python.org/) usando el instalador pip

Linux: `sudo -H pip install --upgrade youtube-dl`

Windows: `pip install --upgrade youtube-dl`

La sintaxis segun la documentacion oficial es la siguiente: `youtube-dl [OPTIONS] URL [URL]`

Pero la forma mas simple de usarlo es: `youtube-dl [URL]`

Despues de iniciara la descarga del video

## Descargar archivos torrent

Si quieres descargar archivos de forma **torrent** desde la terminal o en un entorno que no tienes terminal esta es una gran herramienta, [rTorrent](https://github.com/rakshasa/rtorrent/wiki#installation) funciona en la terminal. 

siempre puedes elegir herramietnas de entornos Gui como [qBittorent](https://www.qbittorrent.org), pero siempre es bueno conocer herramientas que pueden ayudarte en entornos no graficos.

### Configurar
primero lo configuraremos hay un ajustes de ejemplo que tienes al momento de instalarlo
pero no puedes solo copiarlo por lo que entraremos al archivo con **vim** eso si es solo cuando el archivo esta comprimido si no lo esta es solo copiarlo

`cd /usr/share/doc/rTorrent/examples/`
tambien puede ser que exista el archivo sin comprimir 

una vez adentro del archivo lo guardaremos en una direcion especifica (aremos un guardar como)

en vim ejecutas `:w /home/[user]/.rtorrent.rc`

una vez ejecutado ya puedes cerrar el vim con `:q`

despues donde esta el archivo usaras `sudo chown user[:group] .rTorrent.rc`

una vez hecho esto puedes ir al archivo y configurarlo

- `directory.default.set ` La carpeta por defaut que asignas de descarga
- `session.path.set ` para que recuerde donde quedo la descarga o algo asi, re comiendo solo crear la carpeta que nesesita y descomentarlo

recomiendo mirar el [video](https://www.youtube.com/watch?v=2n93ioqHf-U) en el que esta basado esta pequeña guia

### Guia de uso
|teclas|funcion|
--|--
`<ctrl>+q`|Cerrar Programa
`<up> <ctrl>+s`|iniciar descarga