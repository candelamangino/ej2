<img alt="UCU" src="https://www.ucu.edu.uy/plantillas/images/logo_ucu.svg"
width="150"/>

# Universidad Católica del Uruguay

## Facultad de Ingeniería y Tecnologías

### Programación II

# Desafíos de programación orientada a objetos

## Consigna

Te han encargado crear un programa para la empresa “Smoothies R Us” que 
permita calcular el precio de los smoothies que venden a sus clientes.

Crea una clase `Ingridient` que representa los ingredientes del smoothie con 
las responsabilidades de:

* Conocer el nombre
* Conocer el costo; representa el costo de agregar el ingrediente a un smoothie

Crea una clase `Smoothie` con las responsabilidades de:

* Conocer el nombre
* Conocer el precio base; es independiente del costo de los ingredientes
* Conocer los ingredientes
* Agregar un ingrediente; un ingrediente no puede agregarse más de una vez
* Calcular el precio total; es la suma del costo de todos los ingredientes 
  de la lista más el precio base
* Devolver el nombre inicial del smoothie mostrando también todos los 
  ingredientes agregados. La firma de este método es `string GetFullName()`. 
  Por ejemplo, para un `Batido de frutilla` al cual se le agregan los 
  ingredientes   `Vainilla`, `Caramelo` y `Copo de chantilly`, se espera  
  `Batido de frutilla con vainilla, caramelo y copo de chantilly`.

Agrega en el programa en `Program.cs` un ejemplo donde creas instancias de 
estas clases y luego muestras en la consola el resultado del método 
`string GetFullName()`. 

Cuando tengas tu programa terminado, mira una posible solución [aquí](https://github.com/ucudal/PII_DesafioPOO_2_End).
Esa solución incluye comentarios sobre cómo resolver esta consigna en código. 

## Reflexiona

* ¿Pudiste completar el desafío? En caso de que no lo hayas terminado, ¿qué
  te lo impidió?
* ¿En qué se diferencia tu solución de la otra que te mostramos? ¿Son
  relevantes las diferencias?

> [!TIP]
> En caso de que tengas dudas al completar este desafío, consulta a tus
> profesores.

Referencia: https://edabit.com/challenge/rYKtzcuCQ9FQ9t9pH
