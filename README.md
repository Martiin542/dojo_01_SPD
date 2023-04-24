# Dojo 01 Grupo B :fire::fire:
![image](https://media.es.wired.com/photos/63e55ba0bc755c9a2a93f629/3:2/pass/semaforo%2520cuarto%2520color%2520inteligencia%2520artificial.jpg)

## Integrantes 
- Tomás Sassone
- Martin Simone
- Federico Rossello
- Maria Schiaffino
- Matías Villalba

## Proyecto: Dojo 01 - Parte 1.
![image](https://user-images.githubusercontent.com/116306654/234059811-a743b0f1-f8c7-4ee9-ac40-73fbbc97f6da.png)

## Descripción
El gobierno de la ciudad quiere actualizar los semáforos que tiene instalados. La empresa “UTNFRA Robotics” ganó la licitación y ahora les toca a los desarrolladores de la empresa generar un proyecto low cost que cumpla con las especificaciones que el gobierno de la ciudad nos impone, a saber las especificaciones son las siguientes.

### Primer consigna:
1. El semáforo tiene que tener 2 leds de cada color como mínimo, en caso de que uno se rompa.
2. Tiene que implementar los tiempos correctos como se detallan a continuación.
3. El verde dura 5 segundos.
4. El amarillo dura 3 segundos.
5. El rojo dura 5 segundos.
6. Tiene que tener señalización para personas no videntes como se detalla a continuación. (Buzzer o piezo)
7. Durante el rojo: Tiene que sonar 2 vez por segundo en un tono FUERTE.


## Función principal
La función empieza encendiendo el LED rojo por 5 segundos, al mismo tiempo que hace sonar el Buzzer con intervalos de medio segundo por la misma cantidad de tiempo. Luego ambos se apagan para encenderse el LED amarillo por 3 segundos, y por último éste se apaga y se enciende el LED verde por otros 5 segundos, cuando el LED verde se apaga, la función vuelve a comenzar.

(Breve explicación de la función)

~~~ C (lenguaje en el que esta escrito)
void loop()
{
  Serial.println("Prende led verde");
  secuencia(ledGreen, 5000, 1000);
  Serial.println("Prende led amarillo");
  secuencia(ledYellow, 3000, 1000);
  Serial.println("Prende led rojo");
  secuencia(ledRed, 5000, 0);
  secuenciaBuzzer(buzzer);
  Serial.println("Vuelve a empezar");
}
~~~

## :robot: Link al proyecto
- [proyecto Schiaffino] (https://www.tinkercad.com/things/10qGufkSAB1-brilliant-densor/editel?sharecode=oEnLGT-2U7SThnIi5KY-WkN-3ZVpxC7Ybp-m8PfOIUA)
- [proyecto Simone] (https://www.tinkercad.com/things/59JFMMUNXJy-smashing-hango-elzing/editel?sharecode=RyhmHt8iyIxD6rXJl_Qejh3F6JswjkwmnDtfDBG48AQ)
- [proyecto Villalba] (https://www.tinkercad.com/things/lNCvABa1HKT-copy-of-matias-villalba-ejercicio-2-4-div-d/editelsharecode=EJFfDO2ZyNUy4bPHWqmhLceneGhBtowOyD50hmNN1Sg)
- [proyecto Sassone] (https://www.tinkercad.com/things/5eB6TfLInHc-ingenious-kup-wolt/editel?sharecode=g73MXUOwZ1ez2ICqHsApRXK4MoKPoOfsh-24o9ul6yE)
- [proyecto Rossello] (https://www.tinkercad.com/things/apowO6ruCgk-ingenious-turing-bojo/editel?sharecode=BHMXS_B8_SMPxHeZN1rOwnd0Dvywdt7wrqlUDBAfrkk)
