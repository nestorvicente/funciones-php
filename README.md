# funciones-php

Funciones trabajadas en la primera clase sobre funciones definidas por el usuario con php.

Observa como validamos el envío de la información del formulario.
También se validan los campos de entrada, algunos poniendo type number en el input del formulario, 
otros al recibir usando la función is_numeric() de php.

Observar que isset($_POST['enviar']) se puede usar si el envío se hace con button submit.
Si se usó <input type = "submit"> sólo se puede usar el booleano $_GET o $_POST para validar el envío.

En precio_sin_iva.php se usa round($variable,2) para que el resultado se redondee hasta centésimos.
