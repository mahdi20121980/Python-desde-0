![Imagen de portada](images/Python_desde_cero.png)

## Tipos de Datos y Variables en Python

En Python, como en cualquier lenguaje de programación, necesitamos almacenar información y trabajar con ella.
Los tipos de datos definen la clase de información que podemos guardar (números, texto, etc.), mientras que las variables son como contenedores que guardan estos valores.

---

### 1. Tipos de Datos Primitivos

Python tiene varios tipos de datos básicos o primitivos que son fundamentales:

- Enteros (int): Representan números enteros, ya sean positivos, negativos o cero.

      Ejemplos: 10, -5, 0, 123456.
  
- Flotantes (float): Representan números con decimales.

        Ejemplos: 3.14, -2.5, 0.0, 1.0e6 (notación científica).

- Cadenas (str): Representan texto, que se encierra entre comillas simples (') o dobles ("). Las comillas triples (''' o """) se usan para cadenas multilínea.

        Ejemplos: 'Hola Mundo', "Python es genial", '123'.

- Booleanos (bool): Representan valores de verdad, que pueden ser True (verdadero) o False (falso). Son esenciales para la lógica y las decisiones en el código.

---

### 2. Declaración de Variables

En Python, no necesitas declarar explícitamente el tipo de una variable. Simplemente le asignas un valor y Python infiere el tipo:

    # Asignación de variables
    edad = 30            # int
    altura = 1.75        # float
    nombre = "Ana"       # str
    es_estudiante = True  # bool
    
    print(edad)
    print(altura)
    print(nombre)
    print(es_estudiante)

---

### 3. Convenciones de Nombres para Variables

Elegir buenos nombres para las variables es crucial para que el código sea legible. Aquí tienes algunas convenciones comunes (aunque Python es bastante flexible):

- **Nombres descriptivos**: Usa nombres que indiquen claramente el propósito de la variable. Por ejemplo, cantidad_de_productos es mejor que x.

- **Minúsculas con guiones bajos (snake_case)**: Es la convención más común en Python para variables y funciones. Por ejemplo, nombre_completo, precio_unitario.

- **Evita nombres reservados**: No uses palabras clave de Python como if, else, for, while, etc.

- **Empieza con una letra o guion bajo**: No uses números al inicio de una variable (ej: 1variable es incorrecto)

- **No uses espacios**: En lugar de espacios usa _, ej mi_variable

- **Se conciso**: Intenta no crear nombres de variables demasiado largos

---

### 4. Ejercicios Prácticos

Para consolidar tus conocimientos, aquí tienes algunos ejercicios prácticos:

- Ejercicio 1: Calculadora básica:
  Declara dos variables de tipo int (por ejemplo, num1 y num2).
  Realiza las operaciones de suma, resta, multiplicación y división.
  Imprime los resultados.

- Ejercicio 2: Datos de usuario:
  Declara variables para almacenar el nombre (tipo str), la edad (tipo int) y si tiene licencia (tipo bool).
  Asigna valores a estas variables.
  Imprime un mensaje usando estas variables (p. ej., "Hola, [nombre]. Tienes [edad] años y [tienes o no tienes] licencia").

- Ejercicio 3: Conversión de tipos:
  Declara una variable de tipo str que contenga un número (p. ej., numero_str = "123").
  Convierte esta variable a tipo int y a tipo float.
  Imprime los resultados.
  Tip: Puedes convertir tipos usando int(), float(), y str().

--- 

### 5. Ejemplo de Conversión de Tipos
    numero_str = "123"
    numero_int = int(numero_str)
    numero_float = float(numero_str)

    print(type(numero_str))  # Imprime: <class 'str'>
    print(type(numero_int))  # Imprime: <class 'int'>
    print(type(numero_float)) # Imprime: <class 'float'>

    print(numero_int)
    print(numero_float)

---

### 6. Notas Adicionales

- Python es un lenguaje de tipado dinámico, lo que significa que el tipo de una variable puede cambiar durante la ejecución del programa (aunque en general se recomienda no hacerlo).
- La función type() te ayuda a conocer el tipo de dato de una variable.
- Los operadores básicos como +, -, *, /, y ** (potencia) funcionan con números.
