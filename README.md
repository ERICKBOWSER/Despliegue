# Despliegue


La mascara no puede empezar por 0 (ejemplo: 01000000)



Características de la LAN

A finales de los 60 se puso las reglas para crear un protocolo.

OSI no es una arquitectura de red, sino un modelo de referencia.

Puertos predefinidos: 0 a 1023

El socket es una combinación de TCP y puertos

---

Micoservicios: son un pequeño subconjunto de la propia aplicación 


## Apache 

Ficheros /etc/apache:

- apache2.conf -> Configuración global
- ports.conf -> Configuración de puertos
- envvars -> Variables de entorno

Directorios -> Mods, sites, conf (Ej: mods-available):
- available -> Ficherosisponibles, pero puede no ser utilizados
- enabled 

Aquí es donde se guardan todos los errores.

Ruta: ``/etc/apache2/sites-available/000-default.conf``

![imagen](https://github.com/ERICKBOWSER/Despliegue/assets/92431188/a1af26f0-96ec-4ed0-8c9e-b292712e482e)




























