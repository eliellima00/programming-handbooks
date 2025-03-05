# Handbook: Tipos Primitivos em Python e Principais Funções de Manipulação

## 1. Tipos Primitivos

Em Python, os tipos primitivos são as unidades básicas de dados que compõem todas as estruturas mais complexas. Eles incluem:

### 1.1 Inteiros (`int`)

Representam números inteiros, positivos ou negativos.

**Exemplo:**

```python
x = 10
y = -5
```

**Principais funções:**

- `abs(x)`: Retorna o valor absoluto.
- `bin(x)`: Converte para binário.
- `hex(x)`: Converte para hexadecimal.
- `oct(x)`: Converte para octal.

### 1.2 Ponto Flutuante (`float`)

Representam números com casas decimais.

**Exemplo:**

```python
pi = 3.14159
temperature = -10.5
```

**Principais funções:**

- `round(x, n)`: Arredonda para `n` casas decimais.
- `float(x)`: Converte um valor para `float`.

### 1.3 Booleano (`bool`)

Possui dois valores: `True` e `False`.

**Exemplo:**

```python
is_active = True
is_admin = False
```

**Principais funções:**

- `bool(x)`: Converte um valor para booleano.
- `not x`: Inverte o valor booleano.

### 1.4 String (`str`)

Sequência de caracteres.

**Exemplo:**

```python
name = "Python"
greeting = 'Hello, World!'
```

**Principais funções:**

- `len(s)`: Retorna o tamanho da string.
- `s.upper()`: Converte para maiúsculas.
- `s.lower()`: Converte para minúsculas.
- `s.strip()`: Remove espaços extras.
- `s.replace(old, new)`: Substitui partes da string.
- `s.split(sep)`: Divide uma string em uma lista.
- `s.count(value)`: Conta quantas vezes o valor aparece na string.

### 1.5 Bytes (`bytes`)

Representam uma sequência de bytes imutável.

**Exemplo:**

```python
b = b"Hello"
```

**Principais funções:**

- `len(b)`: Retorna o tamanho da sequência.
- `b.decode()`: Converte para string.

## 2. Conversão Entre Tipos

Python permite conversão entre os tipos primitivos.

**Exemplos:**

```python
x = int("10")      # Converte string para inteiro
f = float("3.14")  # Converte string para float
s = str(100)       # Converte inteiro para string
b = bool(1)        # Converte inteiro para booleano
```

## 3. Operadores Comuns

### 3.1 Operadores Aritméticos

```python
x + y  # Soma
x - y  # Subtração
x * y  # Multiplicação
x / y  # Divisão (float)
x // y # Divisão inteira
x ** y # Potenciação
x % y  # Módulo
```

### 3.2 Operadores de Comparação

```python
x == y  # Igual a
x != y  # Diferente de
x > y   # Maior que
x < y   # Menor que
x >= y  # Maior ou igual a
x <= y  # Menor ou igual a
```

### 3.3 Operadores Lógicos

```python
x and y  # E lógico
x or y   # Ou lógico
not x    # Não lógico
```

Esse handbook cobre os tipos primitivos mais importantes e as principais funções para manipulá-los no Python. É essencial compreender esses conceitos para desenvolver aplicações eficientes!

