# Platzom

Platzom es un idioma invetado para el [Curso de Funadmentos de JavaScripts](https://platzi.com/js) de [Platzi](https://platzi.com), el mejor lugar de educación online

## Descripción del idioma

- Si la palabra termina con "ar", se le quitan esas dos palabras
- Si la palabra inicia con z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partír en dos por la mitad y unir con guión medio
- Por ultimo, si la palabra orginal es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra intercalando letras mayúsculas y minusculas

## Instalación

```
npm install platzom
```

### Uso

```
import platzom from 'platzom'

platzom("Programar") // Program
platzom("Zorro") //Zorrope
platzom("abecedario") //abece-dario
platzom("sometemos") // SoMeTeMoS
```

## Creditos
-[Sacha Lifszyc](https://twitter.com/@slifszyc)

## Licencia

[MIT](https://opensource.org/licenses/MIT)
