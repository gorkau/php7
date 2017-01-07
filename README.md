# php7
Docker container para PHP7 con phpunit.

Basado en el trabajo de Chris Fidao:
https://github.com/shipping-docker/php-app/tree/master/build/php

Incluye:

* phpunit
* gulp
* sqlite

## Notas

Si aparece el mensaje:

"notify-send must be installed on the system."

basta con ejecutar:

$ export DISABLE_NOTIFIER=true

De esta forma no se realizan las notificaciones.
