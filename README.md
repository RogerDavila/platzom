# Platzom

Platzom es un idioma inventado para el [Curso de Fundamentos de JavaScript](https://platzi.com/js) de [Platzi](https://platzi.com), el mejor lugar de educación online

## Descripción del idioma
- Si la palabra termina con "ar", se le quitan esas dos letras
- Si la palabra inicia co Z, se le añade "pe" al final.
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio
- Por últmo, si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero   intercalando letras mayúsculas y minúsculas.

## Instalación
```
npm install platzomR
```

## Uso
```
import platzom from 'platzom'

platzom("Programar") //Program
platzom("Zorro") //Zorrope
platzom("Zarpar") //Zarppe
platzom("abecedario") //abece-dario
platzom("sometemos") //SoMeTeMoS
```

##Créditos
- [Roger Dávila](https://www.facebook.com/Rogery.Davila)

##Licencia
[MIT](https://opensource.org/licenses/MIT)
