# Tipos de datos primitivos (numéricos, cadenas, booleanos) y sus operaciones. 📚

En términos simples los tipos de datos son categorías que le dicen al programa qué tipo de valor se está manejando, como números, texto o verdadero/falso. Estos tipos determinan qué operaciones se pueden realizar con esos datos en un programa.

Python tiene varios tipos de datos primitivos que son los bloques básicos de construcción de datos en el lenguaje. Los más comunes son:

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

### Operaciones con Tipos de Datos Primitivos

Cada tipo de dato tiene operaciones específicas que se pueden realizar con ellos. Algunas de las más comunes son:

- **Operaciones con Enteros y Flotantes:**
  - Suma: `+`
  - Resta: `-`
  - Multiplicación: `*`
  - División: `/`
  - División entera: `//`
  - Residuo o módulo: `%`
  - Potencia: `**`

- **Operaciones con Cadenas:**
  - Concatenación: `+`
  - Repetición: `*`
  - Acceso a caracteres individuales mediante índices.

- **Operaciones con Booleanos:**
  - Operadores lógicos: `and`, `or`, `not`

### Ejemplos en Python

```python
# Enteros y Flotantes
a = 10
b = 3.5
print(a + b)  # Suma: 13.5

# Cadenas
saludo = "Hola"
nombre = "Mundo"
print(saludo + " " + nombre)  # Concatenación: Hola Mundo

# Booleanos
verdadero = True
falso = False
print(verdadero and falso)  # Operación lógica: False
```

---

## Referencias 🌐

- [Documentación Oficial de Python - Tipos de Datos](https://docs.python.org/3/library/datatypes.html)
- [Documentación Oficial de Python - Tipos Incorporados](https://docs.python.org/3/library/stdtypes.html)
- [Documentación Oficial de Python - Modelo de Datos](https://docs.python.org/3/reference/datamodel.html)

---

### [Ir al cuestionario 📝](../../cuestionario/01-fundamentos/tipos-de-datos-y-operaciones.md)

### [Ir al temario 🔍](../../readme.md)