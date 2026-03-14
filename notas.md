# List of some notes

## Reto de implementacion

- Va ser desafiante hacer la transicion entre la vista mobil y la vista desktop
  - hay un cambio de posicion (izq a der) de la imagen 
- Manejo de imagenes para cada resolucion de pantalla
  - tener q cambiar la imagen segun el window.widht del cliente

- JS: la transicion a la vista de success active/ error-state
- Elemento ul>li poner icon enves de punto por default

## Que aprendi

- La unidad relativa EM, calcula en base el margin en base su font-size o del padre.
Si tu html tiene font-size: 16px, estos serían los tamaños aproximados más comunes.
- font Size por default
| Elemento | font-size default               | Valor aprox (si root = 16px) |
| -------- | ------------------------------- | ---------------------------- |
| `h1`     | `2em`                           | 32px                         |
| `h2`     | `1.5em`                         | 24px                         |
| `h3`     | `1.17em`                        | ~18.7px                      |
| `h4`     | `1em`                           | 16px                         |
| `h5`     | `0.83em`                        | ~13.3px                      |
| `h6`     | `0.67em`                        | ~10.7px                      |
| `small`  | `smaller` (~0.8em)              | ~12–13px                     |
| `sub`    | `smaller`                       | ~12–13px                     |
| `sup`    | `smaller`                       | ~12–13px                     |
| `code`   | `1em` (pero con font monospace) | 16px                         |
| `kbd`    | `1em`                           | 16px                         |
| `samp`   | `1em`                           | 16px                         |
| `pre`    | `1em`                           | 16px                         |

- Elementos que no cambian el tamaño (heredan 16px)
- Muchos elementos solo heredan el font-size del padre: 
  - p, span, a, label, li, button, input, textarea

- Margenes por default
| Elemento | margin default |
| -------- | -------------- |
| `h1`     | `0.67em 0`     |
| `h2`     | `0.83em 0`     |
| `p`      | `1em 0`        |
| `ul`     | `1em 0`        |
| `body`   | `8px`          |
