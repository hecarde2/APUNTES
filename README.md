# APUNTES
"""
Aquí tienes una explicación más detallada de cada tema en Python, con ejemplos claros que puedes copiar y usar:

## 1. Variables y Tipos de Datos

### Declaración y Uso de Variables
Las variables son contenedores para almacenar datos. En Python, no necesitas declarar el tipo de variable; se determina automáticamente.

```python
# Declaración de variables
edad = 25          # Entero
altura = 1.75     # Flotante
nombre = "Juan"    # Cadena
es_estudiante = True  # Booleano
```

### Tipos de Datos
- **Enteros (`int`)**: Números sin decimales. Ejemplo: `5`, `-3`.
- **Flotantes (`float`)**: Números con decimales. Ejemplo: `3.14`, `-0.001`.
- **Cadenas (`str`)**: Texto encerrado entre comillas. Ejemplo: `"Hola, mundo!"`.
- **Booleanos (`bool`)**: Verdadero o falso. Ejemplo: `True`, `False`.

## 2. Operadores Aritméticos y Lógicos

### Operadores Aritméticos
Estos operadores se utilizan para realizar cálculos matemáticos.

```python
a = 10
b = 5
suma = a + b         # Suma
resta = a - b        # Resta
multiplicacion = a * b  # Multiplicación
division = a / b     # División
modulo = a % b       # Módulo (resto de la división)
```

### Operadores Lógicos
Estos operadores se utilizan para combinar condiciones booleanas.

```python
x = True
y = False
resultado_and = x and y  # AND: True si ambos son True
resultado_or = x or y    # OR: True si al menos uno es True
resultado_not = not x     # NOT: Inverso del valor
```

## 3. Estructuras de Control

### Condicionales
Las estructuras condicionales permiten ejecutar diferentes bloques de código según ciertas condiciones.

```python
if edad >= 18:
    print("Eres mayor de edad")
elif edad >= 13:
    print("Eres un adolescente")
else:
    print("Eres un niño")
```

### Bucles
Los bucles permiten repetir un bloque de código varias veces.

#### Bucle For
Utilizado para iterar sobre una secuencia (lista, tupla, cadena).

```python
for i in range(5):  # Itera sobre los números del 0 al 4
    print(i)  # Imprime cada número
```

#### Bucle While
Ejecuta un bloque de código mientras una condición sea verdadera.

```python
contador = 0
while contador < 5:
    print(contador)  # Imprime el contador
    contador += 1    # Incrementa el contador
```

### Break y Continue
- **break**: Termina el bucle.
- **continue**: Salta a la siguiente iteración del bucle.

```python
for i in range(5):
    if i == 3:
        break  # Sale del bucle cuando i es 3
    print(i)

for i in range(5):
    if i == 2:
        continue  # Salta la iteración cuando i es 2
    print(i)
```

## 4. Funciones

### Definición de Funciones
Las funciones permiten encapsular código que se puede reutilizar.

```python
def saludar(nombre):
    return f"Hola, {nombre}"

print(saludar("Juan"))  # Llama a la función y imprime "Hola, Juan"
```

### Funciones Lambda
Funciones anónimas que se pueden definir en una sola línea.

```python
suma = lambda x, y: x + y
print(suma(5, 3))  # Imprime 8
```

## 5. Estructuras de Datos

### Listas
Colecciones ordenadas y mutables de elementos.

```python
frutas = ["manzana", "naranja", "plátano"]
frutas.append("kiwi")  # Agrega un elemento al final de la lista
print(frutas)  # Imprime ['manzana', 'naranja', 'plátano', 'kiwi']
```

### Tuplas
Colecciones ordenadas e inmutables.

```python
coordenadas = (10.0, 20.0)
print(coordenadas)  # Imprime (10.0, 20.0)
```

### Diccionarios
Colecciones de pares clave-valor.

```python
persona = {"nombre": "Juan", "edad": 30}
print(persona["nombre"])  # Accede al valor por la clave, imprime "Juan"
```

## 6. Manejo de Errores

### Validación de Entradas
Usa `try` y `except` para manejar errores y evitar que el programa se detenga.

```python
try:
    numero = int(input("Introduce un número: "))
except ValueError:
    print("No es un número válido")
```

## 7. Buenas Prácticas de Programación

- **Modularización**: Divide el código en funciones y módulos para mejorar la legibilidad y reutilización.
- **Comentarios**: Usa comentarios para explicar el código y hacerlo más comprensible.

```python
# Esta función suma dos números
def sumar(a, b):
    return a + b
```

Estos son los conceptos fundamentales de Python explicados de manera más detallada. Puedes copiar y pegar los ejemplos en tu entorno de programación para probarlos. Si tienes más preguntas o necesitas más ejemplos, ¡hazmelo saber!
