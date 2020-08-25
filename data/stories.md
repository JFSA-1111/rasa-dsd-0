## path 1
* saludo
  - utter_saludo
  - utter_que_deseas

## path 1             
* saludo
  - utter_saludo
  - utter_que_deseas
* quiero_pelicula
  - utter_cuantos
* cantidad_asientos
  - utter_registrado
  - utter_ha_sido_de_ayuda
* afirmar
  - utter_registrado
  - utter_ha_sido_de_ayuda
  
## path 2             
* saludo
  - utter_saludo
  - utter_que_deseas
* quiero_pelicula
  - utter_cuantos
* cantidad_asientos
  - utter_registrado
  - utter_ha_sido_de_ayuda
* afirmar
  - utter_registrado
  - utter_ha_sido_de_ayuda
  
## decir adiós
* despedida
  - utter_despedida

## reto bot
* reto_bot
  - utter_soy_un_bot
  
## no entiendo
* reto_bot
  - utter_soy_un_bot
  - utter_que_deseas
* despedida
  - utter_despedida

## interactive_story_1
* saludo
    - utter_saludo

## interactive_story_1
* saludo
    - utter_saludo
    - utter_que_deseas
* quiero_pelicula{"pelicula": "funcion"}
    - utter_ha_sido_de_ayuda
* afirmar
    - utter_registrado
    - utter_despedida
