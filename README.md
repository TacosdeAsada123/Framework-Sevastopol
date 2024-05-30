<h1>Framework Sevastopol <img src ="https://media.giphy.com/media/p3ZQzyUWBFWA8KtkYM/giphy.gif" width = "80px" height="35px"><h1>



![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/pandao/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg) ![](https://img.shields.io/github/issues/pandao/editor.md.svg) ![](https://img.shields.io/bower/v/editor.md.svg)
<hr style="border: 1px solid #333;">


<h2>Nuestro proyecto</h2>
<h4>Sevastopol es un Framework de codigo abierto basado en Laravel, diseñado para simplificar el desarrollo de paginas web u otras aplicaciones  ademas de acelerar procedimientos basicos como el orden en las carpetas y subcarpetas. Utiliando NODE JS lograra manejar de manera eficiente el MVC (Modelo, Vista, Controlador) y con composer lograras siempre estar acutalizado en cualquier depedencia ademas de comtrolar las clases.
</h4>
<hr style="border: 1px solid #333;">


<h2>Requisitos</h2>
<hr style="border: 1px solid #333;">


<ul>

<li>
PHP: Como minimo se requiere la version compatible con el framework que se elija, Laravel 8.x requiere PHP 7.3.0 o superior, verifica la documentacion del framework para conocer los requisitos especificos de php
</li>



<li>
Composer: Deberas tener composer instalado en tu sistema para instalar y administrar dependencias del framework y de tu aplicacion, la ultima version de composer requiere como minimo la version de PHP 7.1.3 en adelante, checa la documentacion
</li>



<li>
Node JS y npm: Algunos frameworks modernos requieren o pueden requerir Node JS y npm para administrar dependencias front-end como JS, CSS y sus recursos.
</li>



<li>
Conexion a internet: Para la descarga de dependencias y actualizaciones del framework necesitaras una conexion a internet estable.
Compatibilidad con versiones: asegurate de que el framework que esta utilizando sea compatibles con las versiones de PHP y Node JS que se tienen en su sistema
</li>



<li>
Herramientas de desarrollo: además de las herramientas necesitaras otras, como editor de código, un servidor web local (como Apache), una base de datos (como MySQL, PostgreSQL, etc.) al igual que herramientas de depuración y pruebas.
</li>
</ul>



<h5>
Recuerda utilizar la documentacion oficial de cada herrramienta de trabajo para obtener informacion detallada de los requerimientos minimos y maximos de cada herramienta de trabajo.
</h5>

<hr style="border: 1px solid #333;">



<h2>Instalacion</h2>



<h5>
Clona el repositorio de GitHub con el siguiente comando:
</h5>

 ```
git clone https://github.com/TacosdeAsada123/Proyecto-Final.git
  ```

<h5>
instala las dependencias requeridas con el siguiente comando:
</h5>




  ```
    npm install
  ```

<h5>para instalar composer y sus dependencias en tu proyecto escribe el siguiente comando</h5>




 ```
    composer install
```

<h5>
configura el archivo ".env" que se encuentra en la raiz del framework a las de tu conexion a BD
</h5>




 ```
PUERTO=3306
USER='root'
PASSWORD =''
HOST='localhost'
DBNAME=''
  ```
<h5>

Para generar una nueva vista agrega el siguiente codigo:

</h5>




```
node prueba view "nombre de la vista" 
 ```
Para generar un nuevo modelo agrega el siguiente codigo:

</h5>

```
node prueba model "nombre del modelo" 
 ```
Para generar un nuevo controlador agrega el siguiente codigo:

</h5>


```
node prueba controller "nombre del controlador" 
 ```

<h5>
Para correr o compilar el proyecto ejecuta el siguiente codigo:
</h5>


    npm run build 
    
    
<hr style="border: 1px solid #333;">

<h4>Estrcutura basica de archivos </h4>



```sh
project-root-folder/
├──app
├──├──config
├──├──├──Conexion
├──├──├──MyRoutes
├──├──├──ORM
├──├──├──Route
├──├──├──SecurityToken
├──├──├──View
├──controller
├──├──├──Document_validaciones.controller.js
├──node_modules
├──├──.bin
├──├──@ampproject
├──├──@babel
├──├──@Jridgewell
├──├──@nicolo-ribauno
├──├──...
├──src
├──├──Document_validaciones.controller.js
├──vendor
├──view
├──.babelrc
├──.env
├──.htaccess
├──composer.json
├──coposer.lock
├──index.php
├──package-lock.json
├──package.json
├──prueba.js
├──RADME.md
```
<h3>Autores</h3>
<img src="https://pa1.narvii.com/6909/c92d8f3b7babc938ab6686671f207a33c56e3e35r1-500-719_hq.gif" width = "65px" height="80px">
<h4>Autor Principal </h4>
<h5>Torres Flores Marlon @TacosdeAsado123</h5>