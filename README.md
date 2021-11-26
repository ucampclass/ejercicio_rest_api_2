# Ejercicio 2
- Crea un archivo index.html.
- Crea un archivo style.css. Debes importarlo a tus 
- Crea un archivo js que se llame clima.js. Debes importar este archivo a tu index.html
- En tu html, debes crear una sección la cual debe contener un input de tipo text y un boton que diga buscar.
- Desde tu javascript, cuando se de click en el boton buscar, deberas recuperar el valor del input. Valida que el valor del input no este vacio. Si contiene información debes consumir el siguiente servicio
**https://api.openweathermap.org/data/2.5/weather?q=${value}&appid=${apiKey}&units=metric**
- De la respuesta del objeto, busca la propiedad main. Dentro de la propiedad main esta otra propiedad con el nombre temp. Este valor lo deberas mostrar de forma dinamica usando javascrip.
