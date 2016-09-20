En el sistema decimal se utiliza el caracter “-” para representar los números negativos. Entonces, ¿cómo es posible “simular” el signo en una computadora? Reservando un bit para eso! 
¿Y qué significado tiene ese bit?

* Si bit=0 entonces el número representado es mayor a cero
* Si bit=1 entonces el número representado es menor a cero

Por ejemplo, si se tiene cadenas de 8 bits, podría definirse que el signo está en el extremo derecho o el extremo izquierdo de la cadena. Supongamos lo siguiente:

| Sig | Magnitud |
|-----|-----|
| 1 bit | 7 bits |