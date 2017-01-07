# php7
Docker container para PHP7 con phpunit.

Basado en el trabajo de Chris Fidao:
https://github.com/shipping-docker/php-app/tree/master/build/php

Incluye:

* phpunit
* gulp
* sqlite

## Notas

### Problemas con Gulp

Si al ejecutar Gulp aparece un mensaje similar a éste:

Node Sass could not find a binding for your current environment:...

puede ser un problema de versiones. Debería solucionarse con:

$ npm rebuild

Si aparece el mensaje:

"notify-send must be installed on the system."

basta con ejecutar:

$ export DISABLE_NOTIFIER=true

De esta forma no se realizan las notificaciones.
