En el intento de encontrar algo mas barato y programable como alternativa al beebot, prové el escornabot y 2 bases de robot para Microbit. Os dejo mis impresiones aqui:

**Escornabot**
- Yo lo compré como kit en https://electronperdido.com/shop/robots/kits-robot/escornabot-singularis-2-12/
- Me imprimí las piezas yo, aunque quizás las hubiera comprado porque puse poco infill y el resultado final es un poco endeble.
- Los niños no saben donde está el delante y el detrás (yo tampoco) y esto hace que confundan las teclas de dirección.
- Se desvia mucho. A parte de que la distancia no siempre es la misma. Lo de los motores paso a paso no lo acabo de ver. Quizás hay alguna variable para corregir y calibrar. Molaria que tuviera un potenciómetro para ajustar/calibrar el rumbo.
- Lo de las 4 pilas AA es un poco rollo, además para meterlas y sacarlas hay que sacar un tornillo. Si diseñara la placa, miraria a ver si le puedo meter un booster. Aunque mi niño ha jugado bastante y aun duran las pilas.
- Los tornillos para atornillar la placa no tienen hembra, y hay que cambiarlos, porque si no la placa se acaba soldando.
- Aunque el nuestro sigue vivo, no se que tal aguantara mucho tute de niños pequeños.


**Maqueen (DF Robot) (https://www.dfrobot.com/product-1783.html)**
- Funciona con microbit.
- Los bloques de programación del makecode no estan tan bien como el Minibit, ya que tienes que arrancar motores, hacer un pause i pararlos. ESto complica un poco la programación. ESto creo que es porque ellos ya tiene su propia version de scratch que es mas potente, pero no la he probado.
- Solo tiene dos leds rojos muy sosos (para un niño)
- Le puedes comprar un mando, y leer comandos del mando.
- Expone casi todos los puertos (i2c, i/o, analog) en la misma PCB.
- Lleva un sensor seguidor de línea.
- Lleva booster, con lo que fuciona con rango de 3.5 a 5V. Le puedes poner un 3x AAA o una lipo.
- Tiene buzzer, con lo que puedes hacer que toque distintas notas, musica, etc ... Esto le da mucho juego.
- Tiene un puerto para un servo (se puede comprar un accesorio pala, tipo excavadora)
- Tiene unos leds molones debajo, pero no veo como encenderlos desde el MakeCode.



**Minibit (4tronix) (https://shop.4tronix.co.uk/products/minibit):**
- Funciona con Microbit
- Los bloques que ofrece para programar estan bien. Mejor que el maqueen, pero si pones misma velocidad y mismo tiempo en ambos motores, se acaba desviando igual.
- Se puede comprar un sensor de sonar para evitar obstaculos muy facil de usar.
- Tiene un agujero donde puedes poner un rotulador. Si juegas encima de una pizarra magnética de estas, puedes hacer formas divertidas y parece que les motiva bastante.
- No tiene ninguna interfaz de botones, con lo que para niños pequeños tienes que tu programar alguna actividad con sensores o inventarte algun juego con los botones A-B del microbit.
- No tiene ni booster ni nada, y necesita si o si 3 x AA. Esto lo hace bastante pesado pero a la vez bastante robusto.
- No tiene Buzzer. Pero los leds molan.
- No expone puertos. El accesorio de seguir linia no lo he probado, pero es de 3 leds en lugar de 2.
- Las ruedas molan mas que las del maqueen.
