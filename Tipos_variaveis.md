## Variáveis e Tipos de Dados

## 📌 Variáveis em Python

```python
nome = "Maria"   # string
idade = 25       # inteiro (int)
altura = 1.70    # ponto flutuante (float)
ativo = True     # booleano (bool)
```

👉 O Python descobre o tipo sozinho de acordo com o valor atribuído.

## 📌 Principais Tipos de Dados em Python

### 🔤 String (str)

- Usada para textos.

```python
nome = "Maria"
mensagem = 'Olá, mundo!'
print(nome.upper()) # "MARIA"
print(len(nome)) # 5 (tamanho da string)
```

### 🔢 Números

- Inteiro (int) → números inteiros positivos ou negativos.

```python
x = 10
y = -5
```

- Ponto flutuante (float) → números decimais.

```python
pi = 3.1415
altura = 1.70
```

- Número complexo (complex) → usado em cálculos matemáticos avançados.

```python
z = 2 + 3j
```

### ✅ Booleano (bool)

- Valores lógicos: True ou False.

```python
ativo = True
print(10 > 5)   # True
print(10 == 5)  # False
```

### 📦 Coleções

- Lista (list) → mutável, pode alterar os elementos.

```python
frutas = ["maçã", "banana", "uva"]
frutas.append("laranja")
print(frutas)  # ['maçã', 'banana', 'uva', 'laranja']
```

- Tupla (tuple) → imutável, não pode alterar os elementos.

```python
cores = ("azul", "verde", "vermelho")
```

- Conjunto (set) → não aceita valores duplicados.

```python
numeros = {1, 2, 3, 3, 4}
print(numeros)  # {1, 2, 3, 4}
```

- Dicionário (dict) → pares chave/valor.

```python
pessoa = {"nome": "Ana", "idade": 30}
print(pessoa["nome"])  # Ana
```

## 📌 Verificando o tipo de uma variável

- Use a função type():

```python
x = 10
print(type(x))  # <class 'int'>
```

## 📌 Conversão de Tipos (Casting)

- Você pode converter variáveis de um tipo para outro:

```python
x = "10"
y = int(x)   # converte para inteiro
z = float(x) # converte para float
```

## 📍 Resumo rápido:

| Tipo      | Exemplo                                 | Descrição / Uso Principal                               |
| --------- | --------------------------------------- | ------------------------------------------------------- |
| `int`     | `idade = 25`                            | Números inteiros (positivos ou negativos).              |
| `float`   | `altura = 1.75`                         | Números decimais (ponto flutuante).                     |
| `complex` | `z = 2 + 3j`                            | Números complexos (mais usado em cálculos matemáticos). |
| `str`     | `nome = "Maria"`                        | Textos (strings). Pode usar `" "` ou `' '`.             |
| `bool`    | `ativo = True`                          | Valores lógicos: `True` ou `False`.                     |
| `list`    | `frutas = ["maçã", "banana"]`           | Lista **mutável** (aceita repetição e pode alterar).    |
| `tuple`   | `cores = ("azul", "verde")`             | Tupla **imutável** (não pode alterar valores).          |
| `set`     | `numeros = {1, 2, 3}`                   | Conjunto, **não aceita duplicados**.                    |
| `dict`    | `pessoa = {"nome": "Ana", "idade": 30}` | Estrutura de **chave → valor** (tipo JSON).             |

---
