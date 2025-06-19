# 💻 Desafio: Sistema Bancário com Python

Este projeto consiste na criação de um **sistema bancário simples em Python** pelo **Bootcamp Santander + DIO Backend com python**, operado via terminal, que permite ao usuário realizar depósitos, saques, visualizar o extrato e sair da aplicação. O desafio visa aplicar conceitos básicos de lógica de programação, estruturas de decisão e laços de repetição. 

---

## 🧾 Menu Principal

``` bash
====== Menu ======
    [1] Depositar
    [2] Sacar
    [3] Extrato
    [4] Sair
==================
```

---
## ⚙️ Funcionalidades

### 🟢 1. Depositar
- O usuário informa um valor positivo.
- Se válido, o valor é adicionado ao saldo e registrado no extrato.
- Caso contrário, uma mensagem de erro é exibida.

### 🔴 2. Sacar
- O usuário informa o valor que deseja sacar.
- Regras aplicadas:
  - Valor não pode ultrapassar o saldo disponível.
  - Valor máximo por saque: **R$500**.
  - Limite de **3 saques diários**.
  - Valor deve ser positivo.
- Se todos os critérios forem atendidos, o saque é efetuado e registrado no extrato.

### 📋 3. Extrato
- Exibe todas as movimentações feitas (depósitos e saques).
- Mostra o saldo atual.
- Caso nenhuma movimentação tenha sido realizada, exibe uma mensagem padrão.

### ❌ 4. Sair
- Encerra o programa.

---

## 💡 Regras do Sistema

| Regra                     | Valor                   |
|--------------------------|--------------------------|
| Limite de saque por vez  | R$500                    |
| Limite diário de saques  | 3 saques                 |
| Valor de depósito mínimo | Maior que zero           |
| Valor de saque mínimo    | Maior que zero           |

---

## 🧠 Conceitos Aplicados

- Laço de repetição com `while True`
- Estrutura condicional (`if/elif/else`)
- Manipulação de strings
- Controle de fluxo com `break`
- Operações aritméticas e lógicas

---

## 📁 Estrutura do Projeto

Este projeto é um único script `.py` que pode ser executado diretamente no terminal com Python 3:

```bash
python main.py
