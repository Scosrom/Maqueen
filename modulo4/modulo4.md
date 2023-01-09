En este apartado vamos a trabajar con nuestro maqueen, a través de señales de radio mediante otra placa microbit y con señales infrarrojas con un mando.

## Ejemplo1:

Hemos creado un código para que al pusar las distintas teclas de otro microbit, muestren colores distintos los Led del maqueen.
El primer paso sería ingresar a la microbit que utilizaremos como emisora, el código con las instrucciones para que el receptor interprete las diferentes señales que le llegan. El segundo paso crear e introducir el código en la microbit receptora con los distintos colores, y ya funcionaría todo.

### Código radio1
![radio1](https://user-images.githubusercontent.com/114906855/211269415-3d73167e-de1e-447f-b322-ba78d2bbd62c.png)
### Código radio2
![radio2](https://user-images.githubusercontent.com/114906855/211269424-23d10766-c2b6-40cf-a906-1804c8167dea.png)

[codigo_radio1](microbit-Radio1.hex)

[codigo_radio2](microbit-Radio2(1).hex)

## Ejemplo2:

En este otro ejercicio, a través de un mando con infrarrojos, haremos que nuestro maqueen entre en movimiento. Para ello primero tenemos que saber que frecuencia recibe la microbit con cada botón del mando. Para conseguir esto haremos un programa que al pulsar cualquier botón del mando, nos indique un número con la frecuencia que recibe la microbit. Despúes creamos un programa con los movimientos que va a realizar nuestro robot fijando el número de frecuencia de cada botón con el movimiento a realizar.

### Código radio1

![maqueen ir](https://user-images.githubusercontent.com/114906855/211272854-ea0b979f-6897-43c6-9b4b-7f03afdd8294.png)
