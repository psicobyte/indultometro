El indultometro 
============

#### Instalación del front-end

 * [Instalar Jekyll][1]
        
 * Arrancar Jekyll: `jekyll --serve --auto`
 
 * Opcionalmente, copiar los ficheros generados por Jekyll (`_site`) a Dropbox y hacer público con site44 por ejemplo

[1]: http://jekyllbootstrap.com/usage/jekyll-quick-start.html

#### Despliegue del front-end

 * Github Pages: no está permitido usar plugins, pero necesito de i18n de Jekyll
 
 * Heroku: se puede, pero quiero tener dos apps Heroku para esto?
 
 * Dropbox/Site44: podría llegar a alcanzar el límite de ancho de banda
 
 * Amazon S3

 * Slice

#### Instalación del back-end

 * `bundle install`
 
 * Crear base de datos Postgres, 'indultometro': `createdb indultometro`
 
 * Cargar datos: TO DO
 
 * Arrancar el servidor: `./server`