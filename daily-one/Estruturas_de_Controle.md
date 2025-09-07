## 🔀 **Estruturas de Controle em Python**

### ✅ **1. Estrutura Condicional** – `if`, `elif`, `else`

- Permite executar blocos de código dependendo de uma condição.

```python
idade = 18

if idade < 18:
    print("Menor de idade")
elif idade == 18:
    print("Tem exatamente 18 anos")
else:
    print("Maior de idade")
```

**👉 Importante: indentação (espaços) é obrigatória em Python (normalmente 4 espaços).**

---

### **🔁 2. Estrutura de Repetição** – `for`

- O for percorre elementos de uma sequência (lista, string, range, etc.).

```python
# Percorrendo uma lista
frutas = ["maçã", "banana", "uva"]
for fruta in frutas:
    print(fruta)

# Usando range()
for i in range(5):
    print(i)  # 0 até 4
```

---

### 🔁 **3. Estrutura de Repetição** – `while`

- Repete enquanto a condição for verdadeira.

```python
contador = 0

while contador < 5:
    print("Contador:", contador)
    contador += 1
```

#### **⚠️ Cuidado com loops infinitos:**

```python
while True:
    print("Isso nunca para! (CTRL + C para sair)")
```

---

### ⏭️ **4. Palavras-chave de Controle de Loop**

**- `break` → encerra o loop imediatamente.**

**- `continue` → pula para a próxima iteração do loop.**

**- `pass` → não faz nada (usado como "placeholder").**

```python
for i in range(10):
    if i == 5:
        break   # para o loop no 5
    if i % 2 == 0:
        continue  # pula os pares
    print(i)
```

---

## **🎯 5. Estruturas Aninhadas**

- Podemos colocar if dentro de if, ou loops dentro de loops.

```python
for x in range(3):
    for y in range(3):
        print(f"Posição: ({x}, {y})")

nota = 8
faltas = 2

if nota >= 7:
    if faltas <= 3:
        print("Aprovado!")
    else:
        print("Reprovado por faltas")
```

---

## **📝 Exemplo Prático**

```python
senha = "1234"
tentativas = 0

while tentativas < 3:
    entrada = input("Digite a senha: ")
    if entrada == senha:
        print("Acesso liberado!")
        break
    else:
        print("Senha incorreta.")
        tentativas += 1
```

---

## **📌 Resumo**

**`if` / `elif` / `else` → decisões.**

**`for` → repete em coleções ou intervalos.**

**`while` → repete enquanto a condição for verdadeira.**

**`break`, `continue`, `pass` → controlam os loops.**

---
