**EJERCICIO 14**

*ESCRIBA UN DFD QUE GENERE NUMEROS PARES DEL 1 AL 10*

[![diagramas-de-flujo-para-git-hub-14.jpg](https://i.postimg.cc/yxmCFZk5/diagramas-de-flujo-para-git-hub-14.jpg)](https://postimg.cc/8fzYGsdB)

|CORRIDA|CONT=CONT+2|S=S+C|C<=10|
|-|-|-|-|-|
|1|2|2+0|NO|
|2|4|4+0|NO|
|3|6|6+0|NO|
|4|8|8+0|NO|
|5|10|10+0|SI|

**ENTRADAS**

NINGUNA

**SALIDAS**

S

**EJERCICIO 15**

*CAPTURE N NUMEROS E IMPRIMA SOLO LA SUMA DE LOS PARES*

[![diagramas-de-flujo-para-git-hub-15.jpg](https://i.postimg.cc/B6xSJ6xq/diagramas-de-flujo-para-git-hub-15.jpg)](https://postimg.cc/r0wXJqnb)

|CORRIDAS|N|V|V>0|V%2 (SI) SP=SP+V|C=C+1|N==V (SI) IMP "V"|
|-|-|-|-|-|-|-|
|1|8|1|SI|--|0+1=1|--|
|2| |2|SI|0+2=2|1+1=2|--|
|3| |4| SI|2+4=6|2+1=3|--|
|4| |6|SI|6+6=12|3+1=4|--|
|5| |9|SI|--|4+1=5|--|
|6| |8|SI|12+8=20|5+1=6|--|
|7| |5|SI|--|6+1=7|--|
|8| |10|SI|20+10=30|7+1=8|30|

**EJERCICIO 16**

*DIGITE SI UN NUMERO ES PAR O IMPAR*

[![diagramas-de-flujo-para-git-hub-16.jpg](https://i.postimg.cc/dVh3CJ2Y/diagramas-de-flujo-para-git-hub-16.jpg)](https://postimg.cc/sMR3ddH6)

|CORRIDAS|N|N>0|N%2|MSJ IM|MSJ P|
|-|-|-|-|-|-|
|1|2|SI|SI|--|ES PAR|
|2|7|SI|NO|ES IMPAR|--|
|3|-3|NO, ERROR ES NEGATIVO|--|--|

**ENTRADAS**

numer

**salidas**

"digita un numero"||"es negativo"||"es par"||"es impar"
