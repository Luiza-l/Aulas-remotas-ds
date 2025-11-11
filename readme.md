# Atividade Remota de Desenvolvimento de Sistemas 

## Sobre o Repositório
Este repositório contém quatro atividades práticas desenvolvidas em **Python**, com o objetivo de exercitar os conceitos básicos da linguagem, como entrada de dados, conversão de tipos, condicionais e loops.

As atividades fazem parte da disciplina **Desenvolvimento de Sistemas**, foram realizadas em aulas remotas e têm como foco o aprendizado dos principais conceitos de **Python**, incluindo **entrada e saída de dados**, **estruturas condicionais**, **laços de repetição** e **programação orientada a objetos (POO)** com **classes e herança**. 

---

## Atividades

### **Atividade 1 — Verificador de Maioridade (`atividade1.py`)**

#### Objetivo
Praticar o uso das funções **`input()`** (para receber dados do usuário), **`int()`** (para converter texto em número) e a estrutura condicional **`if/else`** (para tomar decisões com base na idade informada).

#### Desafio
O programa deve:
1. Perguntar o **nome** do usuário.  
2. Perguntar a **idade** do usuário.  
3. Verificar se a idade é **maior ou igual a 18**.  
4. Exibir a mensagem:
   - “Olá, [nome], você é **maior de idade**.” se idade ≥ 18  
   - “Olá, [nome], você é **menor de idade**.” se idade < 18  

#### Conceitos aplicados
- Entrada e saída de dados (`input()` / `print()`)
- Conversão de tipos (`int()`)
- Estruturas condicionais (`if`, `else`)

---

### **Atividade 2 — Tabuada (`atividade2.py`)**

#### Objetivo
Praticar o uso de **loops `for`** com a função **`range()`** e reforçar o uso de **entrada e conversão de dados**.

#### Desafio
O programa deve:
1. Solicitar um **número inteiro** ao usuário.  
2. Utilizar um **loop `for`** para exibir a **tabuada desse número**, de 1 até 10.  


#### Conceitos aplicados
- Laço de repetição (`for`)
- Função `range()`
- Conversão de tipos (`int()`)

---

### **Atividade 3 — Função Calculadora (`funcao_calculadora.py`)**

#### Objetivo  
Criar um arquivo chamado **`funcao_calculadora.py`**.  
Dentro dele, definir uma função Python que receba **três parâmetros** (por exemplo: `numero1`, `numero2` e `operacao`) e **retorne o resultado de uma operação matemática básica**.  

#### Desafio  
O programa deve:  
1. Definir uma função chamada **`calculadora()`** que receba os três parâmetros.  
2. Verificar qual operação foi informada e realizar o cálculo correspondente.  
3. Exibir o resultado da operação para o usuário.  

#### Operações aceitas  
- `soma` → realiza a adição  
- `subtracao` → realiza a subtração  
- `multiplicacao` → realiza a multiplicação  
- `divisao` → realiza a divisão (com verificação de divisão por zero)  

#### Conceitos aplicados  
- Definição e chamada de **funções**  
- Uso de **parâmetros** e **retorno de valores**  
- **Estruturas condicionais** (`if`, `elif`, `else`)    

---

### **Atividade 4 — Orientação a Objetos com Herança (`heranca_veiculos.py`)**

#### Objetivo
Criar um programa em **Python** que utilize **herança entre classes**, definindo uma classe base (pai) e uma classe derivada (filha).

#### Desafio
O programa deve:
1. Criar uma **classe base** chamada `Veiculo`, com os atributos:
   - `marca`
   - `modelo`
2. Criar uma **classe filha** chamada `Carro`, que **herde** de `Veiculo` e adicione um novo atributo:
   - `portas`
3. Criar **objetos** para ambas as classes e exibir seus atributos no terminal.

#### Conceitos aplicados
- Programação Orientada a Objetos (POO)
- Criação de classes e objetos
- Herança (`class Carro(Veiculo)`)
- Uso da função **`super()`** para reutilizar o construtor da classe pai

---

## ⚙️ Tecnologias Utilizadas
- Linguagem: **Python 3.14.0**
- Editor: **Visual Studio Code**

---

## Autor
**Maria Luiza Nunes dos Santos Silva**  
Disciplina: *Desenvolvimento de Sistemas*  
Escola: *Etec Parque da Juventude*  
Ano: *2025*

