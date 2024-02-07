# Tipos de datos primitivos, operadores básicos, variables y expresiones 📚

### Tipos de datos primitivos

En términos simples los tipos de datos son categorías que le dicen al programa qué tipo de valor se está manejando, como números, texto o verdadero/falso. Estos tipos determinan qué operaciones se pueden realizar con esos datos en un programa.

1. **Enteros (`int`):** 
   - Son números sin parte decimal.
   - Ejemplo: `5`, `-3`, `42`.

2. **Números de Punto Flotante (`float`):**
   - Representan números reales y pueden tener una parte decimal.
   - Ejemplo: `3.14`, `-0.001`, `2.0`.

3. **Cadenas de Caracteres (`str`):**
   - Representan texto.
   - Se escriben entre comillas simples `'...'` o dobles `"..."`.
   - Ejemplo: `'Hola'`, `"Python"`.

4. **Booleanos (`bool`):**
   - Representan verdadero o falso.
   - Solo tienen dos valores: `True` o `False`.

### Operadores Básicos

Los operadores básicos en Python se dividen en varias categorías, cada una diseñada para realizar diferentes tipos de operaciones: aritméticas, asignación, comparación, lógicas, y más. A continuación, se detalla cada tipo:

#### Operadores Aritméticos
Estos operadores se utilizan para realizar operaciones matemáticas básicas:

- **Suma (`+`):** Suma dos operandos. Ejemplo: `5 + 3` resulta en `8`.
- **Resta (`-`):** Resta el operando derecho del izquierdo. Ejemplo: `5 - 3` resulta en `2`.
- **Multiplicación (`*`):** Multiplica dos operandos. Ejemplo: `5 * 3` resulta en `15`.
- **División (`/`):** Divide el operando izquierdo por el derecho. Ejemplo: `5 / 2` resulta en `2.5`.
- **División Entera (`//`):** Divide el operando izquierdo por el derecho y redondea hacia abajo para obtener un entero. Ejemplo: `5 // 2` resulta en `2`.
- **Módulo (`%`):** Devuelve el resto de la división entre el operando izquierdo y el derecho. Ejemplo: `5 % 2` resulta en `1`.
- **Exponenciación (`**`):** Eleva el operando izquierdo a la potencia del derecho. Ejemplo: `2 ** 3` resulta en `8`.

#### Operadores de Asignación
Estos operadores se utilizan para asignar valores a variables:

- **Asignación (`=`):** Asigna el valor del lado derecho al operando de la izquierda. Ejemplo: `x = 5`.
- **Asignaciones compuestas (`+=`, `-=`, `*=`, `/=`, etc.):** Realizan una operación entre dos operandos y asignan el resultado al operando izquierdo. Ejemplo: `x += 3` es equivalente a `x = x + 3`.

#### Operadores de Comparación
Permiten comparar dos valores:

- **Igual (`==`):** Verifica si dos valores son iguales.
- **No igual (`!=`):** Verifica si dos valores no son iguales.
- **Mayor que (`>`), Menor que (`<`), Mayor o igual que (`>=`), Menor o igual que (`<=`):** Comparan dos valores en términos de magnitud.

#### Operadores Lógicos
Se utilizan para combinar declaraciones condicionales:

- **AND (`and`):** Devuelve `True` si ambos operandos son verdaderos.
- **OR (`or`):** Devuelve `True` si al menos uno de los operandos es verdadero.
- **NOT (`not`):** Invierte el estado lógico del operando. Si es `True`, devuelve `False` y viceversa.

#### Ejemplos de Uso
```python
# Aritméticos
resultado = 10 + 5  # Suma: 15

# Asignación
x = 10
x += 5  # x ahora es 15

# Comparación
es_igual = (10 == 5)  # False

# Lógicos
resultado_logico = (10 > 5) and (10 < 20)  # True
```

### Variables en Python

Las variables son nombres (identificadores) que se refieren a valores almacenados en la memoria de la computadora. En Python, las variables son dinámicas, lo que significa que automáticamente pueden cambiar de tipo basado en el valor que se le asignes. Algunos puntos clave son:

- **Declaración y Asignación:** No se necesita declarar una variable antes de asignarle un valor. La creación de la variable ocurre automáticamente en el momento de la asignación. Por ejemplo: `x = 5` asigna el valor `5` a la variable `x`.
- **Tipado Dinámico:** Python permite que reasignes variables a valores de diferentes tipos. Esto significa que si `x = 5` (un entero), puedes luego asignar `x = "Hola"` (una cadena de caracteres) sin error.
- **Nombres de Variables:** Los nombres de las variables en Python pueden incluir letras, números y guiones bajos, pero no pueden comenzar con un número. Deben ser descriptivos para hacer el código más legible, por ejemplo: `contador`, `nombre_usuario`, `total`. Python utiliza el naming convention snake_case lo que significa que todas las variables que unan mas de una palabra deberá tener un `_`. Ejemplo: `nombre_completo`, `direccion_fiscal`.
- **Sensibilidad al Caso:** Las variables en Python son sensibles al caso, lo que significa que `variable`, `Variable` y `VARIABLE` serían tres variables distintas.

### Expresiones en Python

Una expresión en Python es una combinación de valores, variables, operadores y llamadas a funciones que se evalúan a un único valor. Las expresiones son el "cómo" de Python para hacer cálculos o evaluar condiciones. Algunos detalles sobre las expresiones son:

- **Operadores y Valores:** Las expresiones utilizan operadores para realizar cálculos o comparaciones entre valores o variables. Por ejemplo, la expresión `2 + 3` utiliza el operador de suma `+` para sumar los valores `2` y `3`.
- **Tipos de Expresiones:** Hay varios tipos de expresiones en Python, incluidas las aritméticas, lógicas, de comparación y de asignación. Por ejemplo, `x > y` es una expresión de comparación que evalúa si `x` es mayor que `y`.
- **Prioridad de Operadores:** Python sigue reglas de prioridad para determinar el orden en que se evalúan las operaciones dentro de una expresión. Por ejemplo, en la expresión `3 + 4 * 5`, la multiplicación se realiza primero.
- **Evaluación de Expresiones:** Cuando Python evalúa una expresión, el resultado es un valor que puede ser asignado a una variable, impreso, o utilizado de alguna otra manera. Por ejemplo, si `x = 7` y `y = 3`, entonces la expresión `x - y` se evalúa a `4`.

---

## Referencias 🌐

- [Tipos de Datos Primitivos en Python](https://docs.python.org/3/library/stdtypes.html)
- [Operadores Básicos en Python](https://docs.python.org/3/library/stdtypes.html#numeric-types-int-float-complex)

---

### [Ir al cuestionario 📝](../../cuestionario/01-fundamentos/tipos-de-datos-y-operaciones.md)

### [Ir al temario 🔍](../../readme.md)