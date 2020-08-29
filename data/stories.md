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
* despedida
  - utter_despedida

## decir adiós
* despedida
  - utter_despedida

## reto bot
* reto_bot
  - utter_soy_un_bot
* despedida
  - utter_despedida

## no entiendo
* reto_bot
  - utter_soy_un_bot
  - utter_que_deseas
* despedida
  - utter_despedida

## interactive_story_1
* saludo
    - utter_saludo
* despedida
  - utter_despedida

## interactive_story_1
* saludo
    - utter_saludo
    - utter_que_deseas
* quiero_pelicula{"pelicula": "funcion"}
    - utter_ha_sido_de_ayuda
* afirmar
    - utter_registrado
    - utter_despedida
* despedida
  - utter_despedida

## interactive_story_1
* cantidad_asientos
    - utter_cuantos
* cantidad_asientos
    - utter_registrado
    - utter_ha_sido_de_ayuda

## interactive_story_1
* no entiendo{"alimento": "aguacates"}
    - action_revert_fallback_events
    - utter_default
    - action_restart

## interactive_story_1
* no entiendo

## interactive_story_1
* no entiendo

## interactive_story_1
* no entiendo
    - utter_despedida

## interactive_story_1
* quiero_pelicula{"pelicula": "funcion"}

## interactive_story_1
* quiero_pelicula{"pelicula": "presentacion"}
    - utter_cuantos
* cantidad_asientos
    - utter_registrado
    - utter_ha_sido_de_ayuda
* despedida
    - utter_despedida

## interactive_story_1
* cantidad_asientos{"pelicula": "presentacion"}
    - utter_cuantos
* cantidad_asientos
    - utter_registrado
    - utter_ha_sido_de_ayuda
* afirmar
    - utter_despedida

## interactive_story_1
* cantidad_asientos{"pelicula": "presentacion"}
    - utter_cuantos
* afirmar
    - utter_registrado
    - utter_ha_sido_de_ayuda
* despedida

## interactive_story_1
* saludo
    - utter_saludo
    - utter_que_deseas
* cantidad_asientos
    - utter_registrado

## interactive_story_1
* quiero_pelicula{"pelicula": "funcion"}
    - utter_cuantos
* despedida
    - utter_despedida

## interactive_story_1
* quiero_pelicula{"pelicula": "pelicula"}
    - utter_cuantos
* afirmar
    - utter_registrado
    - utter_ha_sido_de_ayuda
* afirmar

## interactive_story_1
* saludo
    - utter_saludo
    - utter_que_deseas
* quiero_pelicula{"pelicula": "pelicula"}
    - utter_cuantos
* afirmar

## interactive_story_1
* quiero_pelicula{"number": 2, "pelicula": "pelicula"}
    - utter_cuantos

## interactive_story_1
* saludo
    - utter_saludo
    - utter_que_deseas
* quiero_pelicula{"number": 2, "pelicula": "pelicula"}
    - utter_cuantos
* afirmar{"number": 3}
    - utter_registrado
    - utter_ha_sido_de_ayuda
* afirmar

## interactive_story_1
* quiero_pelicula{"number": 2, "pelicula": "funcion"}
    - utter_cuantos
* afirmar{"number": 6}
    - utter_registrado
    - utter_ha_sido_de_ayuda
* despedida

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas
* despedida
    - utter_despedida
* afirmar
* saludo
    - utter_saludo
* afirmar

## Story from conversation with 9e14b75e5e1a4f54b4f2a27715864364 on August 28th 2020

* saludo
    - utter_saludo
    - utter_que_deseas
* quiero_pelicula
    - utter_cuantos
* afirmar
    - utter_registrado
* despedida
    - utter_despedida

## Story from conversation with 57756360549840e083cee032a71ee1a6 on August 28th 2020

* despedida
    - utter_saludo
    - utter_que_deseas

## Story from conversation with b7f51160991145e3b8b8289855d23070 on August 28th 2020

* saludo
    - utter_saludo
    - utter_que_deseas
* cantidad_asientos
    - utter_cuantos
* afirmar
    - utter_registrado
    - utter_ha_sido_de_ayuda
* despedida
    - utter_despedida

## Story from conversation with ff7fe6bb495f4b3e82cec98c29e84cea on August 28th 2020

* afirmar
* saludo
    - utter_saludo
    - utter_que_deseas
* afirmar
    - utter_registrado
    - utter_ha_sido_de_ayuda
* afirmar
    - utter_despedida

## Story from conversation with 7df8e44beabc4b118c6a35b22d866a7b on August 28th 2020

* saludo
    - utter_saludo
    - utter_que_deseas
* despedida
    - utter_cuantos
* afirmar
    - utter_registrado
    - utter_ha_sido_de_ayuda
* despedida
    - utter_despedida

## Story from conversation with b7f51160991145e3b8b8289855d23070 on August 28th 2020

* quiero_pelicula{"pelicula":"pelicula"}
    - utter_cuantos
* afirmar
    - utter_registrado
    - utter_ha_sido_de_ayuda
* afirmar
    - utter_despedida

## Story from conversation with b7f51160991145e3b8b8289855d23070 on August 28th 2020

* saludo
    - utter_saludo
    - utter_que_deseas
* cantidad_asientos
    - utter_registrado
* despedida
    - utter_despedida

## Story from conversation with b7f51160991145e3b8b8289855d23070 on August 28th 2020

* saludo
    - utter_saludo
    - utter_que_deseas
* afirmar
    - utter_registrado
    - utter_ha_sido_de_ayuda
* afirmar
    - utter_despedida
* despedida
    - utter_despedida

## Story from conversation with b7f51160991145e3b8b8289855d23070 on August 28th 2020

* saludo
    - utter_saludo
    - utter_que_deseas
* afirmar
    - utter_registrado
    - utter_ha_sido_de_ayuda
* despedida
    - utter_despedida

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas
* afirmar
    - utter_registrado
    - utter_ha_sido_de_ayuda
* despedida
    - utter_despedida
* despedida

## Story from conversation with b7f51160991145e3b8b8289855d23070 on August 28th 2020

* saludo
    - utter_saludo
    - utter_que_deseas
* cantidad_asientos
    - utter_registrado
* despedida
    - utter_despedida

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas
* cantidad_asientos
    - utter_registrado
* despedida
    - utter_despedida

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas
* cantidad_asientos
    - utter_registrado
* afirmar
    - utter_despedida

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas
* quiero_pelicula
    - utter_cuantos
* afirmar
    - utter_registrado
* despedida
    - utter_despedida

## New Story

* quiero_pelicula
    - utter_cuantos
* cantidad_asientos
    - utter_registrado
    - utter_ha_sido_de_ayuda
* despedida
    - utter_despedida
* despedida
    - utter_despedida

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas
* afirmar
    - utter_registrado
    - utter_ha_sido_de_ayuda
* despedida
    - utter_despedida

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas
* quiero_pelicula{"pelicula":"presentacion"}
    - utter_cuantos
* afirmar
    - utter_registrado
    - utter_ha_sido_de_ayuda
* despedida
    - utter_despedida

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas
* quiero_pelicula
    - utter_cuantos

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas
* despedida
    - utter_cuantos

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas
* quiero_pelicula
    - utter_cuantos
* afirmar
    - utter_registrado
    - utter_ha_sido_de_ayuda

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas
* despedida
    - utter_cuantos

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas
* quiero_pelicula{"pelicula":"pelicula"}
    - utter_cuantos
* afirmar
    - utter_registrado
    - utter_ha_sido_de_ayuda
* despedida
    - utter_despedida

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas
* afirmar
    - utter_registrado
    - utter_ha_sido_de_ayuda
* despedida
    - utter_despedida
* despedida
    - utter_despedida

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas

## New Story

* saludo
    - utter_saludo
    - utter_que_deseas
* afirmar
    - utter_registrado
    - utter_ha_sido_de_ayuda
* afirmar
    - utter_despedida
