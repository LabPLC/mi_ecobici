Mi Ecobici
==========

Sitio web para que usuarios de [Ecobici](https://www.ecobici.df.gob.mx/)
(sistema de transporte urbano individual en bicicletas) conozcan sus
estadísticas de uso del sistema, como impactan positivamente el medio
ambiente y visualicen en un mapa interactivo sus viajes.

Mi Ecobici es posible gracias a los datos y API del [Laboratorio de
Datos](http://datos.labplc.mx), especificamente el [API de
Ecobici](http://datos.labplc.mx/movilidad/ecobici.info).

Agradecemos al programa **Ecobici** de la [Secretaria de Medio
Ambiente](http://www.sedema.df.gob.mx) por su colaboración en la
apertura de datos que hacen posible a este proyecto.

Capturas de pantalla
--------------------

### Versión estándar

#### Página de inicio

![Página de inicio](/doc/img/desktop-1.png?raw=true "Página de inicio")

#### Mapa de viajes

![Mapa de viajes](/doc/img/desktop-2.png?raw=true "Mapa de viajes")

#### Estadísticas

![Estadísticas](/doc/img/desktop-3.png?raw=true "Estadísticas")

### Versión tableta

#### Página de inicio

![Página de inicio](/doc/img/tablet-1.png?raw=true "Página de inicio")

#### Mapa de viajes

![Mapa de viajes](/doc/img/tablet-2.png?raw=true "Mapa de viajes")

#### Estadísticas

![Estadísticas](/doc/img/tablet-3.png?raw=true "Estadísticas")

### Versión móvil

#### Página de inicio

![Página de inicio](/doc/img/mobile-1.png?raw=true "Página de inicio")

#### Mapa de viajes

![Mapa de viajes](/doc/img/mobile-2.png?raw=true "Mapa de viajes")

#### Estadísticas

![Estadísticas](/doc/img/mobile-3.png?raw=true "Estadísticas")

Instalación
-----------

1. Es necesario un servidor web con PHP.

2. La raíz del sitio web debe apuntar a `web/htdocs`

3. El servidor debe soportar URLs limpias en la raíz del sitio web. Por
   ejemplo la configuración para nginx sería:

        location / {
          try_files $uri $uri/ /index.php?$args;
        }

Autores
-------

- [Corina Olicon](http://twitter.com/c0rysi)
- [Virgilio Pasotti](http://twitter.com/pasotti_)
- [Manuel Rábade](http://twitter.com/manuelrabade)

Licencia
--------

Esta obra está bajo una [Licencia Pública General de GNU](LICENSE.txt).
