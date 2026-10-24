# Rewiro

App web para dejar de fumar. Lleva la cuenta del tiempo sin fumar, los cigarros que no te fumaste y el dinero que te ahorras, y tiene un botón SOS para cuando llega el antojo.

Funciona en el navegador, sin instalar nada y sin cuenta. Los datos se guardan en `localStorage`, así que se quedan en el dispositivo.

## Qué hace

- **Hoy**: contador desde tu fecha de corte, cigarros evitados, dinero ahorrado y qué está pasando en tu cuerpo según el tiempo que llevas.
- **SOS**: eliges qué detonó el antojo y qué tan fuerte es, y te guía con 5 minutos de respiración y algunas ideas para aguantar.
- **Plan**: reglas tipo "si pasa esto, hago esto" para decidir antes de que llegue el antojo.
- **Premios**: pones cosas que quieres comprarte y se van pagando con lo que ahorras.
- **Patrones**: a qué hora y por qué te dan más antojos.

## Cómo correrlo

Abre `index.html` en el navegador. Si quieres servirlo local:

```
npx serve .
```

o

```
python -m http.server
```

## Estructura

```
index.html
css/styles.css
js/
  data.js     detonantes, hitos de salud y textos
  utils.js    helpers de formato y fechas
  store.js    guardado en localStorage
  views.js    pantallas
  sos.js      flujo del botón SOS
  main.js     eventos e inicio
```

Hecho con HTML, CSS y JavaScript sin frameworks.

## Nota

Esto no sustituye ayuda médica. En México la Línea de la Vida (800 911 2000) da orientación gratis.
