**EJERCICIO 11**

[![diagramas-de-flujo-para-git-hub-11.jpg](https://i.postimg.cc/gJnLgYpm/diagramas-de-flujo-para-git-hub-11.jpg)](https://postimg.cc/njfLzfMP)

|A_NAC|A_NAC>0|A_ACT|A_ACT>0|A_ACT>A_NAC|A_ACT-A_NAC|
|-|-|-|-|-|-|
|2004|SI|2022|SI|SI|2022-2004|

**ENTRADA**

A_NAC||A_ACT

**SALIDA**

"AÑO DE NACIMIENTO"||"AÑO ACTUAL"||"NO PUEDE SER MENOR O IGUAL QUE 0"||"EL AÑO DEBE SER MAYOR A 0"||"EL AÑO DE NACIMIENTO NO PUEDE SER MAYOR AL ACTUAL"||A_ACT-A_NAC

**EJERCICIO 12**

*ESCRBE UN DFD QUE CUENTE DEL 1 AL 10 Y LO ESCRIBA*

[![diagramas-de-flujo-para-git-hub-12.jpg](https://i.postimg.cc/Dyq6rc55/diagramas-de-flujo-para-git-hub-12.jpg)](https://postimg.cc/7fZSD0FT)

|CONT|CONT<=10|CONT=CONT+1|
|-|-|-|
|1|SI|2|
|2|SI|3|
|3|SI|4|
|4|SI|5|
|5|SI|6|
|6|SI|7|
|7|SI|8|
|8|SI|9|
|9|SI|10|
|10|S|11|
|11|NO||

**ENTRADA**

NINGUNA

**SALIDA**

CONT

**EJERCICIO 13**

*EL RESULTADO DE LA SUMA DE LOS NUMEROS NATURALES DEL 1 AL 10*

[![diagramas-de-flujo-para-git-hub-13.jpg](https://i.postimg.cc/85x86bwN/diagramas-de-flujo-para-git-hub-13.jpg)](https://postimg.cc/LYk0dLrb)

|C|S|S=S+C|C<=10|C=C+1|
|-|-|-|-|-|
|1|0|1|SI|2|
|2|0|2|SI|3|
|3|0|3|SI|4|
|4|0|4|SI|5|
|5|0|5|SI|6|
|6|0|6|SI|7|
|7|0|7|SI|8|
|8|0|8|SI|9|
|9|0|9|SI|10|
|10|0|10|SI|11|
|11|0|11|NO||

**ENTRADA**

NINGUNA

**SALIDA**

S
