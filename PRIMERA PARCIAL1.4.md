**EJERCICIO 19**

*CAPTURE NUMEROS, AL FINAL INDIQUE CUANTOS SON "+" Y CUANTOS "-", ESCRIBA 0 PARA TERMINAR*

[![diagramas-de-flujo-para-git-hub-20.jpg](https://i.postimg.cc/xjyqLsB6/diagramas-de-flujo-para-git-hub-20.jpg)](https://postimg.cc/0rj8sCkS)

|CORRIDAS|N|N=0|N>0|(SI)CP=CP+1|(NO)CN=CN+1|MSJ|
|-|-|-|-|-|-|-|
|1|4|NO|SI|0+1=1|--|1
|2|-6|NO|NO|--|0+1=1|1|
|3|7|NO|SI|1+1=2|--|2|
|4|-9|NO|NO|--|1+1=2|2|
|5|0|SI|--|--|--|HAY DOS POSITIVOS Y DOS NEGATIVOS|

*EJERCICIO 20*

Capturar si un numero es negativo o positivo y contar del 0 a ese numero

[![0035fa1c-e227-4ec6-89f7-512d301cde88.jpg](https://i.postimg.cc/C5PRk5dj/0035fa1c-e227-4ec6-89f7-512d301cde88.jpg)](https://postimg.cc/GTD31cF2)

|corridas|num|num>=0|(si)cont=cont+1|(no)cont=cont-1|(si)cont=num?|(no)cont=num?|
|-|-|-|-|-|-|-|
|1|-1|no||0-1=-1||si|
|2|1|si|0+1=1||si||
|3|||||si|si|

*ENTRADAS*

1 |NUM|

*SALIDAS*

1|"DAME UN NUMERO POITIVO O NEGATICO, 0 PARA TERMINAR"|
