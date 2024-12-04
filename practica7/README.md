# Práctica 7 
En ésta práctica instalaremos y configuraremos servicios adicionales para la seguridad de nuestro sistema.

## Fail2ban
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica7/imgs/Screenshot%20From%202024-12-03%2020-50-31.png?raw=true" alt="Instalado" />
</p>

<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica7/imgs/Screenshot%20From%202024-12-03%2020-51-56.png?raw=true" alt="Desde hace rato" />
</p>

Cambiamos la configuración para el uso de un *back-end* distinto:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica7/imgs/Screenshot%20From%202024-12-03%2020-52-32.png?raw=true" alt="Imagen" />
</p>

Reiniciamos y verificamos el estado de `fail2ban`:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica7/imgs/Screenshot%20From%202024-12-03%2020-53-24.png?raw=true" alt="Desde hace rato" />
</p>

## ClamAV
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica7/imgs/Screenshot%20From%202024-12-03%2020-54-22.png?raw=true" alt="Desde hace rato" />
</p>

Seguimos con la reconfiguración del servicio:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica7/imgs/Screenshot%20From%202024-12-03%2020-58-01.png?raw=true" alt="Desde hace rato" />
</p>

<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica7/imgs/Screenshot%20From%202024-12-03%2020-59-54.png?raw=true" alt="Desde hace rato" />
</p>

<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica7/imgs/Screenshot%20From%202024-12-03%2021-00-22.png?raw=true" alt="Desde hace rato" />
</p>

<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica7/imgs/Screenshot%20From%202024-12-03%2021-00-45.png?raw=true" alt="Desde hace rato" />
</p>

Confirmamos el estado de ClamAV:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica7/imgs/Screenshot%20From%202024-12-03%2021-01-45.png?raw=true" alt="Desde hace rato" />
</p>

## Postfix y Logwatch
Iniciamos con la instalación:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica7/imgs/Screenshot%20From%202024-12-03%2021-02-35.png?raw=true" alt="Desde hace rato" />
</p>

Configuramos `postfix`:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica7/imgs/Screenshot%20From%202024-12-03%2021-04-01.png?raw=true" alt="Desde hace rato" />
</p>

Configuramos `logwatch` para que funcione con correos:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica7/imgs/Screenshot%20From%202024-12-03%2021-10-27.png?raw=true" alt="Desde hace rato" />
</p>

<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica7/imgs/Screenshot%20From%202024-12-03%2021-11-10.png?raw=true" alt="Desde hace rato" />
</p>

Verificamos que el funcionamiento sea correcto:
<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica7/imgs/Screenshot%20From%202024-12-03%2021-12-40.png?raw=true" alt="Desde hace rato" />
</p>

<p align="center">
  <img src="https://github.com/MadPsychic/SysLinux/blob/main/practica7/imgs/Screenshot%20From%202024-12-03%2021-13-13.png?raw=true" alt="Desde hace rato" />
</p>
