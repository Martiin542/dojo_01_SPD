# Dojo 01 Grupo B :fire::fire:
![Tinkercad](./img/ArduinoTinkercad.jpg)


## Integrantes 
- Martin Simone


## Proyecto: Dojo 01 - Parte 1.
![image](https://user-images.githubusercontent.com/116306654/234027934-ffa33aff-e864-48b1-8ab2-55c574f65bb5.png)



## Descripción
Semaforo el cual prende y apaga sus luces en secuencia, al llegar a la luz roja un buzzer suena dos veces cada un segundo.

## Función principal
Esta funcion se encarga de encender y apagar los leds en seceuncia y activar el buzzer.

Esta funcion llama a la funcion "secuencia" que al dalrle un pin de led y los segundos de delay nos permite prender y apagar las led para formar la secuencia del semaforo
(Breve explicación de la función)

~~~ C (lenguaje en el que esta escrito)
void loop()
{
  Serial.println("Prende led verde");
  secuencia(ledGreen, 5000, 1000);
  Serial.println("Prende led amarillo");
  secuencia(ledYellow, 3000, 1000);
  Serial.println("Prende led rojo");
  secuencia(ledRed, 5000, 1000);
  Serial.println("Vuelve a empezar");
}
~~~

## :robot: Link al proyecto
- [proyecto Schiaffino] (https://www.tinkercad.com/things/10qGufkSAB1-brilliant-densor/editel?sharecode=oEnLGT-2U7SThnIi5KY-WkN-3ZVpxC7Ybp-m8PfOIUA)
- [proyecto Simone] (https://www.tinkercad.com/things/59JFMMUNXJy-smashing-hango-elzing/editel?sharecode=RyhmHt8iyIxD6rXJl_Qejh3F6JswjkwmnDtfDBG48AQ)
- [proyecto Villalba] (https://www.tinkercad.com/things/lNCvABa1HKT-copy-of-matias-villalba-ejercicio-2-4-div-d/editel sharecode=EJFfDO2ZyNUy4bPHWqmhLceneGhBtowOyD50hmNN1Sg)
- [proyecto Sassone] (https://www.tinkercad.com/things/5eB6TfLInHc-ingenious-kup-wolt/editel?sharecode=g73MXUOwZ1ez2ICqHsApRXK4MoKPoOfsh-24o9ul6yE)
- [proyecto Rossello] (https://www.tinkercad.com/things/apowO6ruCgk-ingenious-turing-bojo/editel?sharecode=BHMXS_B8_SMPxHeZN1rOwnd0Dvywdt7wrqlUDBAfrkk)







