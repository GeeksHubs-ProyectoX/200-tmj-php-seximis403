
<p align="center">
    <img src="https://github.com/GeeksHubsAcademy/2020-geekshubs-media/blob/master/image/logo.png" >	
</p>


    Considere el siguiente problema:

    Escriba un programa corto que permita calcular el número de un factorial con valores ultra grandes.
    
    Se atiente al siguiente ejemplo:


   | N | Resultado | Resultado final  |
   | -- | -- | -- |
   |  0 |  0  |  0  |
   |  1 | 1 | 1 |
   |  2 | 2 |2 |
   |  3 | 6 | 6 |
   |  10 | 3628800 | 3628800 |
   |  30 | 2.6525285981219E+32 | 265252859812191058636308480000000 |
   |  40 | 8.159152832479E+47 | 815915283247897734345611269596115894......0 |
   |  50 |3.0414093201713E+64 | 30414093201713378043612608166064768844......0 |
   |  100 | 9.3326215443944E+157| 9332621544394415268169923885626670049......0 |
   |  500 | INF  | 1220136825991110068701238785423046926......0 |


    Fijese que el resultado que se quiere para esta kata es el 'Resultado final' siendo una representación
    aproximada por el desbordamiento del número.
    
    Exactamente para despejar dudas :
    
   | N | Resultado | Resultado final  |
   | -- | -- | -- |
   |  40 | 8.159152832479E+47 | 815915283247897734345611269596115894272000000000 |

    En la carpeta 'src/Reina.php' se encuentra el fichero con la definición de nuestro método vacío.
    En la carpeta 'test/ReinaTest.php' se encuentra el fichero con la suite de test.

    El modus operandi de trabajo es el siguiente:
    
    Debes 'forkear' el proyecto a tu cuenta.
    Puedes hacer PR's ilimitadas e ir validando poco a poco la solución contra nuestro respositorio con CI.
    Puedes trabajar en local y subir la solución haciendo un PR a nuestro repositorio.
    Cuando se envíe la PR final, debes indicar el tiempo de dedicación y los intentos que has hecho.
    También puedes añadir un comentario para dar cualquier tipo de feedback.
    
    En caso de duda, revisa en el apartado de 'Referencias'.

    Runtime:       PHP 7.2
    Configuration: ./303-ts-php/phpunit.xml

    Time: 00:15.000, Memory: 02.35 MB

    .............                                                                   13 / 13 (100%)
   
    OK (13 tests, 13 assertions)
    Process finished with exit code 0
