# Parte de Mila

# Empiezo la pr imera traducción
**Primer intento de uso de GitHub**
1. Primero mi parte
2. Segundo, la parte del segundo 
3. y tercero la otra.

# I'm gay!
## última parte yo 

# Examen de la unidad

registrar nuevos archivo de prueba unitaria en test / index.js
Las pruebas están escritas usando "cinta"
Ejecuta  las pruebas unitarias a través de: prueba npm

#####  Para pruebas locales de explorador sin cabeza ejecute npm run test-browser (Requiere selenio para instalarse - se puede hacer con npm run selenium-install) Ejecutar las pruebas unitarias a través de la prueba npm requiere al menos el nodo v7.0.0

## Pruebas del navegador

### Para ejecutar las pruebas de Selenium a través de Nightwatch, sirve la aplicación a través de un servidor web local:

**npm run serve # starts web server at localhost:8080**

## Entonce necesitarás: 

1. Tener un servidor Selenium ejecutándose localmente en el puerto 4444.

      * Ejecutar: npm ejecutar test-browser

2. O bien, instale y ejecute SauceConnect
      * o	Ejecutar: sc -u <USERNAME> -k <ACCESS_KEY> (see .travis.yml for values)
