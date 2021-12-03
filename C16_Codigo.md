# Incremento de la velocidad de los obstaculos

Establecer dentro de la `function cactus`

`sprite.velocityX = -(6 + score/100);`

# Incremento de la velocidad del suelo, buscar en `function draw ()` 

`suelo.velocityX = -(4+3*score/100);`

# Generar saltos autonomos en trex

Establecer dentro de `function setup()`

`trex.setCollider ("rectangle",0,0,400,trex.heigth);`

Agregar en el codigo que condicion el contacto con los cactus y trex asi como cambio de estado de juego `if()`

`trex.velocityY = - 12;`

`jumpSpund.play();`