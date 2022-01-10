Es fácil ver que en `Pepita.volar_hacia! Barreal` el objeto receptor es `Pepita`, el mensaje `volar_hacia!` y el argumento [`Barreal`](https://es.wikipedia.org/wiki/Barreal); pero ¿dónde queda eso de objeto y mensaje cuando hacemos, por ejemplo, `2 + 3`?

Como ya dijimos, todas nuestras interacciones en un ambiente de objetos ocurren enviando mensajes y las operaciones aritméticas **no son la excepción** a esta regla.

En el caso de `2 + 3` podemos hacer el mismo análisis:

* el objeto receptor es `2`;
* el mensaje es `+`;
* el argumento es `3`.

Y de hecho, ¡también podemos escribirlo como un envío de mensajes convencional!

> Probá en la consola los siguientes envíos de mensajes:
>
```ruby
ム 5.+ 6
ム 3.< 27
ム Pepita.== Norita
```