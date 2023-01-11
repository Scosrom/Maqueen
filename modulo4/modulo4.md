En este apartado vamos a trabajar con nuestro maqueen, a través de señales de radio mediante otra placa microbit y con señales infrarrojas con un mando.

## Ejemplo1:

Hemos creado un código para que al pusar las distintas teclas de otro microbit, muestren colores distintos los Led del maqueen.
El primer paso sería ingresar a la microbit que utilizaremos como emisora, el código con las instrucciones para que el receptor interprete las diferentes señales que le llegan. El segundo paso crear e introducir el código en la microbit receptora con los distintos colores, y ya funcionaría todo.

Video - https://youtube.com/shorts/NPK_Pm1mCQo?feature=share

### Código radio1
![radio1](https://user-images.githubusercontent.com/114906855/211269415-3d73167e-de1e-447f-b322-ba78d2bbd62c.png)
### Código radio2
![radio2](https://user-images.githubusercontent.com/114906855/211269424-23d10766-c2b6-40cf-a906-1804c8167dea.png)

[codigo_radio1](microbit-Radio1.hex)

[codigo_radio2](microbit-Radio2(1).hex)

## Ejemplo2:

En este otro ejercicio, a través de un mando con infrarrojos, haremos que nuestro maqueen entre en movimiento. Para ello primero tenemos que saber que frecuencia recibe la microbit con cada botón del mando. Para conseguir esto haremos un programa que al pulsar cualquier botón del mando, nos indique un número con la frecuencia que recibe la microbit. Despúes creamos un programa con los movimientos que va a realizar nuestro robot fijando el número de frecuencia de cada botón con el movimiento a realizar.

Video - https://youtu.be/YQOt2X005QA

### Código radio1

![maqueen ir](https://user-images.githubusercontent.com/114906855/211272854-ea0b979f-6897-43c6-9b4b-7f03afdd8294.png)

### Código Movimiento

![Sin título](https://user-images.githubusercontent.com/114906778/211274083-74495cde-28c4-4d43-9a5c-e4849a8c8b49.png)

[Código](codigo2.hex)

## Ejemplo3: 
Ahora vamos a comprobar como la microbit también es capaz de recibir un sonido e interpretarlo según su volumen. En este caso práctico, realizaremos un código con el cual al recibir el sonido de un aplauso el maqueen avance, pero cuando deje de recibir dicho sonido, procederá a pararse y se encenderán los Leds azules.

Vídeo - https://www.youtube.com/watch?v=DTXEfNbxD-Q

### Código de bloques
![Captura desde 2023-01-11 09-07-44](https://user-images.githubusercontent.com/114906855/211753295-8c239138-ac78-4313-8d30-357a6f39bd1b.png)

[Código](sonido.hex)

## Ejemplo4:
Otra funcionalidad que tiene el maqueen es la de detectar la distacia de los objetos. En este ejercicio vamos a hacer que nuestro robot evite obstáculos hasta encontrar una salida y continuar su camino. Cada obstáculo que se vuelva a encotrar lo volverá a esquivar.

Vídeo - https://www.youtube.com/shorts/MacQ5x26UEU

### Código de bloques
![Captura desde 2023-01-11 10-09-32](https://user-images.githubusercontent.com/114906855/211765637-8e93f4a4-f626-4bce-8159-0639d28d1ba2.png)

[Código](distancia.hex)

