# Patrón de diseño Mediador
![alt text](https://github.com/serchfr890/Examen-Semana-2/blob/master/Mediador.jpg)

Con este patrón de diseño se puede definir un mediador, en este caso la disquera, quien es el que va a tener una comunicación y control entre los distintos componentes (sistemas de streaming tales como spotify, Apple Music, Amazon Music, You Tube).
El mediador (disquera) les va a poder notificar cuando exista una nueva canción, si alguno de ellos quiere el nuevo contenido en sus plataformas tendrán que pagar él, el mediador va a tener una función que va a estar verificando constantemente quién de ellos ya a realizado el pago para que les otorge el acceso, en dado caso que si los contenedores realizan el pago en el mismo tiempo, el mediador va a poder ser capaz de controlar el acceso al contenido nuevo, en dado caso que un contenedor no quiera el nuevo contenido, el mediador le negará el acceso al contenido. 
