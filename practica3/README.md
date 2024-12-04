# Práctica 3 
En ésta práctica aseguraremos el *bootloader* de *Debian 12 Bookworm* en nuestra máquina virtual.

## Demostración de edición de los parametros del GRUB
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica3/imgs/Screenshot%20From%202024-12-03%2015-16-28.png?raw=true" alt="Instalado" />
</p>

Editamos los parametros del GRUB:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica3/imgs/Screenshot%20From%202024-12-03%2015-18-32.png?raw=true" alt="Desde hace rato" />
</p>

## Entorno en BASH
Confirmamos que hemos logrado obtener un entorno `bash` como `root` en el sistema:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica3/imgs/Screenshot%20From%202024-12-03%2015-21-07.png?raw=true" alt="Imagen" />
</p>

Ejecutamos `mount`, `mount -o remount,rw /` y cambiamos la contraseña del usuario:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica3/imgs/Screenshot%20From%202024-12-03%2015-21-57.png?raw=true" alt="Desde hace rato" />
</p>

## Asegurar *bootloader*
Verificamos que podemos acceder como `root` con la nueva contraseña y editamosla siguiente configuración:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica3/imgs/Screenshot%20From%202024-12-03%2015-37-02.png?raw=true" alt="Desde hace rato" />
</p>

<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica3/imgs/Screenshot%20From%202024-12-03%2015-39-10.png?raw=true" alt="Desde hace rato" />
</p>

<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica3/imgs/Screenshot%20From%202024-12-03%2015-39-25.png?raw=true" alt="Desde hace rato" />
</p>

Actualizamos la configuración del GRUB:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica3/imgs/Screenshot%20From%202024-12-03%2015-40-12.png?raw=true" alt="Desde hace rato" />
</p>

Obtenemos y guardamos el *hash* de nuestra contraseña:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica3/imgs/Screenshot%20From%202024-12-03%2019-07-38.png?raw=true" alt="Desde hace rato" />
</p>

Agregamos nuestra contraseña a la configuración:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica3/imgs/Screenshot%20From%202024-12-03%2019-09-54.png?raw=true" alt="Desde hace rato" />
</p>

## Confirmación
Verificamos que todavía podemos acceder como usuarios del sistema:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica3/imgs/Screenshot%20From%202024-12-03%2019-11-55.png?raw=true" alt="Desde hace rato" />
</p>

<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica3/imgs/Screenshot%20From%202024-12-03%2019-12-42.png?raw=true" alt="Desde hace rato" />
</p>

Observamos que, ahora, cuando intentamos editar los parametros del GRUB, ahora debemos ingresar la contraseña para hacerlo:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica3/imgs/Screenshot%20From%202024-12-03%2019-24-47.png?raw=true" alt="Desde hace rato" />
</p>
