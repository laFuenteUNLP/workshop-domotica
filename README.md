# Workshop de domótica con Node.js, Raspberry Pi y Arduino

En este workshop vamos a construir las bases para una solución de domótica hecha por nosotros mismos.

Vamos a construir un hub central utilizando un Raspberry Pi para controlar con Node.js dispositivos basados en Arduino de forma inalámbrica. También vamos a implementar una interfaz web simple para monitorear y comunicarse con el hub de forma remota.

El objetivo principal es plantear la arquitectura y hacer una implementación simple.
Con esta base cada uno podrá después en sus casas implementar los sensores y actuadores que necesiten, como también mejorar el hub y la interfaz web para agregarles más funcionalidad.

## Prerequisitos

Antes de empezar el taller necesitás tener instalado en tu computadora:

* **Node.js**: Podés descargarlo y seguir las instrucciones desde https://nodejs.org/en/download/, o usar el [package manager](https://nodejs.org/en/download/package-manager/) de tu plataforma.

#### Ubuntu / Debian
* Build essentials: ``sudo apt-get install build-essential``

#### Windows
* VS Express [Download](https://www.visualstudio.com/en-us/products/visual-studio-express-vs.aspx)
* Python 2.7 [Download](https://www.python.org/downloads/release/python-2711/)
* ``node-gyp``: ``npm install -g node-gyp``
* PuTTY y PSCP [Download](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html)

#### OSX
* XCode [Download](https://developer.apple.com/xcode/download/)
* ``node-gyp``: ``npm install -g node-gyp``

## Ejercicios

**Nota** En el taller vamos a usar placas Arduino Uno [ya preparadas](firmata.md) para usar Johnny-five, y Raspberry Pis 2 con Raspbian [ya instalado](https://www.raspberrypi.org/documentation/installation/installing-images/README.md).

1. [Johnny-five hello world](ejercicios/01_hello-world)
1. [Sensor de temperatura](ejercicios/02_sensor-temperatura)
1. [Switch magnético](ejercicios/03_switch-magnetico)
1. [Conexión bluetooth con el módulo HC-06](ejercicios/04_conexion-hc-06)
1. [Node en Raspberry Pi](ejercicios/05_node-raspberrypi)
1. [Conexión bluetooth entre Raspberry Pi y HC-06](ejercicios/06_raspberrypi-bluetooth)
1. [Hub de dispositivos](ejercicios/07_hub)
1. [Acceso desde la web](ejercicios/08_acceso_web)
1. [Agregar lógica a la web](ejercicios/09_logica_web)
