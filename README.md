# SPD_PROYECTO1
Proyecto numero 1 para SPD, usando tinkercad y arduino (C++): CONTADOR CON DOS DISPLAY DE 7 SEGMENTOS.
## Integrantes
- Ramiro Bianucci
- German Canosa
## Proyecto: CONTADOR CON DISPLAY DE 7 SEGMENTOS.
El proyecto consiste en un display que cuenta hasta el numero 9.
El mismo tiene 3 BOTONES, SUMA, RESTA y PUESTA A CERO.

Con esos tres botones usted puede realizar la cuenta hacia adelante, atras y poner el contador en el numero 0.

## Función principal "contador":
Esta funcion se encarga de elegir segun el numero dado que pines prender para que el contador presente los numeros correctos.

~~~ C (lenguaje en el que esta escrito)
int contador(int cont){
  digitalWrite(A,LOW);
  digitalWrite(B,LOW);
  digitalWrite(C,LOW);
  digitalWrite(D,LOW);
  digitalWrite(E,LOW);
  digitalWrite(F,LOW);

  switch(cont) {
  case 0:
     	digitalWrite(A,HIGH);
     	digitalWrite(B,HIGH);
     	digitalWrite(C,HIGH);
     	digitalWrite(D,HIGH);
     	digitalWrite(E,HIGH);
     	digitalWrite(F,HIGH);
     	digitalWrite(G,LOW);
     break;
   case 1:
     	digitalWrite(A,LOW);
     	digitalWrite(B,HIGH);
     	digitalWrite(C,HIGH);
     	digitalWrite(D,LOW);
     	digitalWrite(E,LOW);
     	digitalWrite(F,LOW);
     	digitalWrite(G,LOW);
     break; 
   case 2:
     digitalWrite(A,HIGH);
     digitalWrite(B,HIGH);
     digitalWrite(C,LOW);
     digitalWrite(D,HIGH);
     digitalWrite(E,HIGH);
     digitalWrite(F,LOW);
     digitalWrite(G,HIGH);
     break;
   case 3:
     digitalWrite(A,HIGH);
     digitalWrite(B,HIGH);
     digitalWrite(C,HIGH);
     digitalWrite(D,HIGH);
     digitalWrite(E,LOW);
     digitalWrite(F,LOW);
     digitalWrite(G,HIGH);
     break;
   case 4:
     digitalWrite(A,LOW);
     digitalWrite(B,HIGH);
     digitalWrite(C,HIGH);
     digitalWrite(D,LOW);
     digitalWrite(E,LOW);
     digitalWrite(F,HIGH);
     digitalWrite(G,HIGH);
     break;
   case 5:
     digitalWrite(A,HIGH);
     digitalWrite(B,LOW);
     digitalWrite(C,HIGH);
     digitalWrite(D,HIGH);
     digitalWrite(E,LOW);
     digitalWrite(F,HIGH);
     digitalWrite(G,HIGH);
     break;
   case 6:
     digitalWrite(A,HIGH);
     digitalWrite(B,LOW);
     digitalWrite(C,HIGH);
     digitalWrite(D,HIGH);
     digitalWrite(E,HIGH);
     digitalWrite(F,HIGH);
     digitalWrite(G,HIGH);
     break;
   case 7:
     digitalWrite(A,HIGH);
     digitalWrite(B,HIGH);
     digitalWrite(C,HIGH);
     digitalWrite(D,LOW);
     digitalWrite(E,LOW);
     digitalWrite(F,LOW);
     digitalWrite(G,LOW);
     break;
   case 8:
     digitalWrite(A,HIGH);
     digitalWrite(B,HIGH);
     digitalWrite(C,HIGH);
     digitalWrite(D,HIGH);
     digitalWrite(E,HIGH);
     digitalWrite(F,HIGH);
     digitalWrite(G,HIGH);
     break;
   case 9:
     digitalWrite(A,HIGH);
     digitalWrite(B,HIGH);
     digitalWrite(C,HIGH);
     digitalWrite(D,LOW);
     digitalWrite(E,LOW);
     digitalWrite(F,HIGH);
     digitalWrite(G,HIGH);
     break;
   }
    
 }
~~~

## Link al proyecto
- [PROYECTO](https://www.tinkercad.com/things/3QPXpNRcHmx?sharecode=fDbfNxUnAKzV5K4AZFmJl1x2y8PPDzAVn96Re7XUGQg) 
