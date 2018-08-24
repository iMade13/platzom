# Platzom 
Platzom es un idioma inventado para el curso de Fundamentos de Javascript de Platzi

## Descripción del Idioma
- Si la palabra termina con 'ar' se le quitan dos letras.
- Si la palbra inciia con Z, se le añade 'pe' al final.
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión en el medio.
- Por último, si la palabra original en un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y minúsculas. 

## Instalación 
```
npm install platzom
```

## Uso
```
import platzom from 'platzom'

platzom('Programar') // Program
platzom('Zorro') // Zorrope
platzom('Zarpar') // Zarppe
platzom('abcedario') // abece-dario
platzom('sometemos') // SoMeTeMoS
```

## Créditos
- [Madeleine M](https://twitter.com/@made_marcano)

## Licencia
[MIT](https://opensource.org/licenses/MIT)

