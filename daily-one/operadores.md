## ⚡ **Operadores em Python**

- Operadores são símbolos usados para realizar operações em variáveis e valores.
  Exemplo básico:

```python
a = 10
b = 3
print(a + b)  # 13
```

---

### 🔢 1. Operadores Aritméticos

- Usados para cálculos matemáticos.

| Operador               | Exemplo  | Resultado |
| ---------------------- | -------- | --------- |
| `+` (soma)             | `5 + 2`  | `7`       |
| `-` (subtração)        | `5 - 2`  | `3`       |
| `*` (multiplicação)    | `5 * 2`  | `10`      |
| `/` (divisão)          | `5 / 2`  | `2.5`     |
| `//` (divisão inteira) | `5 // 2` | `2`       |
| `%` (módulo/resto)     | `5 % 2`  | `1`       |
| `**` (exponenciação)   | `5 ** 2` | `25`      |

---

### 🔍 2. Operadores de Comparação

- Usados para comparar valores. Sempre retornam True ou False.

| Operador              | Exemplo  | Resultado |
| --------------------- | -------- | --------- |
| `==` (igual)          | `5 == 5` | `True`    |
| `!=` (diferente)      | `5 != 3` | `True`    |
| `>` (maior que)       | `5 > 3`  | `True`    |
| `<` (menor que)       | `5 < 3`  | `False`   |
| `>=` (maior ou igual) | `5 >= 5` | `True`    |
| `<=` (menor ou igual) | `3 <= 5` | `True`    |

---

### ✅ 3. Operadores Lógicos

- Usados em expressões condicionais.

  | Operador        | Exemplo             | Resultado |
  | --------------- | ------------------- | --------- |
  | `and` (e)       | `(5 > 2 and 3 < 4)` | `True`    |
  | `or` (ou)       | `(5 > 10 or 3 < 4)` | `True`    |
  | `not` (negação) | `not(5 > 2)`        | `False`   |

---

### 📦 4. Operadores de Atribuição

- Usados para armazenar valores em variáveis (muitas vezes combinados com aritméticos).

| Operador | Exemplo   | Equivalente   |
| -------- | --------- | ------------- |
| `=`      | `x = 5`   | atribui 5 a x |
| `+=`     | `x += 3`  | `x = x + 3`   |
| `-=`     | `x -= 3`  | `x = x - 3`   |
| `*=`     | `x *= 3`  | `x = x * 3`   |
| `/=`     | `x /= 3`  | `x = x / 3`   |
| `//=`    | `x //= 3` | `x = x // 3`  |
| `%=`     | `x %= 3`  | `x = x % 3`   |
| `**=`    | `x **= 3` | `x = x ** 3`  |

---

### 🔗 5. Operadores de Identidade

- Comparam se duas variáveis são o mesmo objeto na memória.

```python
x = [1, 2, 3]
y = x
z = [1, 2, 3]

print(x is y)   # True  (apontam para o mesmo objeto)
print(x is z)   # False (mesmo valor, mas objetos diferentes)
print(x is not z) # True
```

---

### 📂 6. Operadores de Associação

- Verificam se um valor está dentro de uma sequência (listas, strings, etc).

```python
frutas = ["maçã", "banana", "uva"]

print("maçã" in frutas)      # True
print("laranja" not in frutas) # True
```

---

### 🎯 Exemplo prático combinando operadores:

```python
idade = 20
tem_carteira = True

if idade >= 18 and tem_carteira:
    print("Pode dirigir!")
else:
    print("Não pode dirigir.")
```

---
