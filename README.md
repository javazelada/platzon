# Platzon

platzon es un idioma inventado para el [curso de fundamentos de javascript](https://platzi.com/js) de platzi

## Descripcion del idioma
- Si la palabra termina en "ar", se le quitan esos dos caracteres
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partir a la mitad y unir con un guión del medio
- Por último, si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y minúsculas

## Instalacion

```
npm install Platzom
```

## uso

```
import platzom from 'platzom'

console.log(platzom("Programar")) // Program
console.log(platzom("Zorro")) // Zorrope
console.log(platzom("Zarpar")) // Zarppe
console.log(platzom("abecedario")) // abece-dario
console.log(platzom("sometemos")) // SoMeTeMoS
```

## Creditos
- [Javier Zelada](https://twitter.com/javazelada1)

## Licencia
- [MIT](https://opensource.org/licenses/MIT)
