# Errores frecuentes - Objetivo 4

- Hablar de "herramientas de test" sin especificar qué es lo que hacen esas
  herramientas de test. No existen las herramientas de test, existen
  herramientas que llevan a cabo diferentes funcionalidades relacionadas con los
  tests. El tipo de esas herramientas, para las funcionalidades que se requieren
  en el objetivo, es lo que hay que hay que reflejar aquí.

- TDD no sólo es una metodología para escribir tests, es una para modularizar el
  código de forma que sea fácil de testear y para que sea más fácil de entender,
  refactorizar y evolucionar. Para hacer esto lo más importante, entre los
  principios SOLID, es la S de *Separation of concerns*: se trata de que cada
  función haga una cosa y solo una. Eso hace más fácil testear esa única cosa.
  - Si te preguntas si una función hace una sola cosa y solo una, en el momento
    que tengas más de un bucle o más de un `if` y sobre todo `if`s anidados, ya
    estás haciendo más de una cosa.
