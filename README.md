# bin

my scripts

## Explicacion

* clear_ntfs

Script que sirve para quitar la marca de hibernación puesta por Windows 8+
al momento de apagar el pc. recomendado cuando el sistema se niega
a montar la particion. simplemente hay que cambiar la ruta y el lugar
donde se quiere montar la particion. por defecto tengo una carpeta windows.
script muy basico. Si doy el salto a W10 es posible que haga un if para detectar
si la carpeta existe o no.

* hdmi-headphones-changer

Anteriormente usaba una pantalla y audifonos conectados por usb al pc.
basicamente fuerza a alsa a cambiar entre audifonos y el hdmi conectado al pc,
ya que usaba solo un tiling wm, necesitaba un script para hacer este trabajo.

* mpdsetup.sh

Basicamente un script que no es mio, pero lo tengo aqui para rapido acceso.
he aquí el link de donde fue sacado https://wiki.archlinux.org/index.php/Music_Player_Daemon#Scripted_configuration

* screenshot

Me he basado en el trabajo de https://github.com/copycat-killer/dots/blob/master/bin/screenshot
para hacer este script. basicamente saca una captura de pantalla usando
scrot y guarda en la carpeta screenshots... nada del otro mundo

* xrandr.sh

https://wiki.archlinux.org/index.php/xrandr#Example_3 script utilizado para
presentaciones en clase. rota entre monitores conectados, permitiendo solo
1 de ellos. revisar la wiki para mas variantes

## Licencia

GPL3 mothafakers!!
