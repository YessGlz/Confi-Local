<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

### Configuración del Proyecto

## Paso 1: Crear un Fork del Repositorio
- Inicio sesión en mi cuenta de GitHub.
- Navego al repositorio original del proyecto Laravel que deseo forkar.
- En la esquina superior derecha de la página del repositorio, hago clic en el botón "Fork" para crear una copia del repositorio en mi cuenta de GitHub.

## Paso 2: Clonar el Repositorio en mi Máquina Local
- Abro Visual Studio Code.
- Accedo a la "Command Palette" mediante el menú View > Command Palette o utilizando el atajo Ctrl+Shift+P.
- En la "Command Palette", escribo Git: Clone y selecciono la opción correspondiente.
- Ingreso la URL del fork del repositorio que creé en GitHub.
- Elijo una ubicación en mi máquina local donde deseo clonar el repositorio.
- Una vez clonado, Visual Studio Code me pregunta si deseo abrir el repositorio. Acepto para abrir el proyecto en Visual Studio Code.
  
## Paso 3: Instalación de Dependencias
- Abro la terminal integrada en Visual Studio Code seleccionando View > Terminal.
- En la terminal, instalo las dependencias de PHP ejecutando el siguiente comando:
- composer update
- Luego, instalo las dependencias de JavaScript utilizando npm:
- npm install
  
## Paso 4: Configuración del Archivo .env
- En el Explorador de Archivos de Visual Studio Code, encuentro el archivo env.example.
- Hago clic derecho en el archivo y selecciono "Copy".
- Pego la copia en la carpeta raíz del proyecto y la renombro a .env.
- Abro el archivo .env y configuro los detalles de la conexión a la base de datos según mi entorno local.
  
## Paso 5: Ejecutar Migraciones y Seeders
- En la terminal integrada de Visual Studio Code, realizo las migraciones de la base de datos para crear las tablas necesarias:
- php artisan migrate:install
- php artisan migrate:fresh
  
## Paso 6: Generación de la Key de Laravel
- En la terminal integrada de Visual Studio Code, genero la clave de la aplicación Laravel ejecutando:
- php artisan key:generate
  
## Paso 7: Servir la Aplicación y Compilar Recursos
- Inicio el servidor de desarrollo de Laravel:
- php artisan serve
- Compilo los recursos front-end utilizando npm:
- npm run dev
  
## Paso 8: Verificar la Configuración
- Abro mi navegador web y voy a http://localhost:8000 para verificar que el servidor de desarrollo de Laravel esté funcionando correctamente.
- Me aseguro de que todos los recursos front-end se hayan compilado y cargado correctamente.
  
## Paso 9: Trabajar en mi Proyecto
- Con mi entorno de desarrollo configurado, puedo comenzar a trabajar en mi proyecto de Laravel.
- Realizo cambios en mi código y utilizo la terminal integrada en Visual Studio Code para ejecutar los comandos de Artisan, Composer y npm según sea necesario.
  
## Paso 10: Gestionar el Control de Versiones
- Utilizo Git para gestionar los cambios en mi proyecto. Puedo hacer commits, crear ramas y enviar mis cambios al fork en mi cuenta de GitHub.
- Cuando estoy listo para fusionar mis cambios con el repositorio original, puedo crear un pull request desde mi fork.
  
## Paso 11: Configuración de Usuarios en MySQL Workbench
- Abro MySQL Workbench y me conecto a la base de datos que está configurada en mi archivo .env.
- Navego a la base de datos correspondiente en el panel de la izquierda.
- Encuentro y selecciono la tabla users (o la tabla que almacena la información de los usuarios).
- Hago clic derecho sobre la tabla users y selecciono "Select Rows" para ver los registros de la tabla.
- Localizo el registro del usuario al que deseo asignar el tipo admin.
- En la columna usertype, cambio el valor a admin para el usuario seleccionado.
- Guardo los cambios y verifico que se hayan aplicado correctamente.

