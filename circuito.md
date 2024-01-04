# Circuito Limitador de Corriente

Se diseña tarjeta electrónica que limita la corriente que entrega la fuente de corriente ajustable (laser driver) por 2 motivos.

1.- Limitar potencia óptica de láser a 500 mW correspondiente a **class 3B** según norma internacional [ANSI Z136.1](docu/2019120664752977.pdf) "*Safe Use Of Lasers*", tal que se disminuyan los riesgos de manipulación con lásers de mayor potencia óptica. 

2.- Evitar dañar láser cuya corriente máxima de operación sea menor a la que entrega la fuente de corriente ajustable (láser driver)

La topología que se utilizo es la siguiente:

![](images/current limiter.png)

* Vin corresponde a pin + de la salida LD que alimenta al láser desde la fuente de corriente ajustable (láser driver) 
* Iout se conecta al cátodo del láser  
* La tierra del láser driver (pin - LD) se conecta directamente al ánodo del láser 
* R1 se calcula de acuerdo a la corriente que se desea limitar. 