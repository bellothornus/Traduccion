

# Empiezo la pr imera traducción
**Primer intento de uso de GitHub**
1. Primero mi parte
2. Segundo, la parte del segundo 
3. y tercero la otra.
### Mi Parte


#### Remix
Remix (también conocido como Browser-Solidity) es un compilador de Solidity basado en navegador y el IDE.
Visite nuestra [página web](https://remix.ethereum.org) para usarlo; siempre entregará la última versión.


#### Uso fuera de línea
La rama de páginas fantasma siempre tiene la última versión estable de Remix. También contiene un archivo ZIP con toda la compilación. Descárgalo para usarlo offline.


Nota: Contiene la última versión de Solidez disponible en el momento del envasado. No se admiten otras versiones de compilador.
#### INSTALACIÓN:
Instala npm y node.js [ver](https://docs.npmjs.com/getting-started/installing-node), luego hazlo:
 - clon [git](https://github.com/ethereum/browser-solidity)
 - cd browser-solidez
 - npm install - npm install - busca dependencias y ejecuta npm run prepublish para construir la aplicación

## Parte Carlos

# DESARROLLO:

Ejecutar npm comienze y abra **http://127.0.0.1:8080** en su navegador. Luego abre tu editor de texto y comienza a desarrollar. El navegador se actualizará automáticamente cuando se guarden los archivos.

# Resolución de problemas de construcción.

Aquí hay algunas cosas a considerar si tiene problemas para construir el paquete. Here are some things to consider if you have trouble building the package.

Asegúrese de tener la versión correcta de node, npm y nvm. Puede encontrar la versión que se probo en Travis CI mirando el log en los resultados de compilación.


Ejecutar:

~~~
node --version
npm --version
nvm --version
En sistemas operativos basados en Debian como Ubuntu 14.04 LTS, puede que necesite ejecutar apt-get install build-essential. Después de instalar build-essential run npm reconstruction.
~~~


# Wifft's section
## Traducción
### PHP


PHP es un lenguaje de scripting del lado del servidor diseñado principalmente para el desarrollo web.
Fue creado en 1994 por Rasmus Lerdorf. Originalmente se llamaba **Personal Home Page** pero lo acabaron llamando **Hypertext** **Pre-Procesor**



# Parte de Mila
# Examen de la unidad

registrar nuevos archivo de prueba unitaria en test / index.js
Las pruebas están escritas usando "cinta"
Ejecuta  las pruebas unitarias a través de: prueba npm

Para pruebas locales de explorador sin cabeza ejecute npm run test-browser (Requiere selenio para instalarse - se puede hacer con npm run selenium-install) Ejecutar las pruebas unitarias a través de la prueba npm requiere al menos el nodo v7.0.0

## Pruebas del navegador

### Para ejecutar las pruebas de Selenium a través de Nightwatch, sirve la aplicación a través de un servidor web local:

**npm run serve # starts web server at localhost:8080**

## Entonce necesitarás: 

1. Tener un servidor Selenium ejecutándose localmente en el puerto 4444.

      * Ejecutar: npm ejecutar test-browser

2. O bien, instale y ejecute SauceConnect
      * o	Ejecutar: sc -u <USERNAME> -k <ACCESS_KEY> (see .travis.yml for values)
