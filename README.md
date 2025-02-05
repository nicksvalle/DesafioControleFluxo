# Desafio Controle de Fluxo

Este projeto é um exercício de controle de fluxo em Java, que recebe dois números inteiros como entrada e imprime uma sequência de números com base na diferença entre eles. Caso o primeiro número seja maior que o segundo, uma exceção personalizada (
`ParametrosInvalidosException`) é lançada.

## 🚀 Tecnologias utilizadas
- Java 17+
- Scanner (para entrada de dados)
- Tratamento de exceções

## 📌 Como funciona
1. O usuário insere dois números inteiros.
2. Se o primeiro número for **menor** que o segundo:
   - O programa calcula a diferença entre os dois números.
   - Imprime no console uma contagem de `1` até essa diferença.
3. Se o primeiro número for **maior** que o segundo:
   - O programa lança uma exceção `ParametrosInvalidosException` com a mensagem: **"O segundo parâmetro deve ser maior que o primeiro"**.

## 📥 Entrada de dados
O programa solicita os seguintes dados no terminal:
```
Digite o primeiro parâmetro:
12
Digite o segundo parâmetro:
30
```

## 📤 Saída esperada
```
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
...
Imprimindo o número 18
```

Se o primeiro número for maior que o segundo:
```
O segundo parâmetro deve ser maior que o primeiro
```

## 🛠 Como executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/desafio-controle-fluxo.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd desafio-controle-fluxo
   ```
3. Compile o código:
   ```bash
   javac -d bin src/*.java
   ```
4. Execute o programa:
   ```bash
   java -cp bin Contador
   ```

---

# Flow Control Challenge

This project is a Java exercise on flow control. It receives two integer inputs and prints a sequence of numbers based on the difference between them. If the first number is greater than the second, a custom exception (`ParametrosInvalidosException`) is thrown.

## 🚀 Technologies used
- Java 17+
- Scanner (for user input)
- Exception handling

## 📌 How it works
1. The user enters two integers.
2. If the first number is **less than** the second:
   - The program calculates the difference between them.
   - Prints a count from `1` up to this difference.
3. If the first number is **greater than** the second:
   - The program throws a `ParametrosInvalidosException` with the message: **"O segundo parâmetro deve ser maior que o primeiro"**.

## 📥 Input example
```
Digite o primeiro parâmetro:
12
Digite o segundo parâmetro:
30
```

## 📤 Expected output
```
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
...
Imprimindo o número 18
```

If the first number is greater than the second:
```
O segundo parâmetro deve ser maior que o primeiro
```

## 🛠 How to run
1. Clone this repository:
   ```bash
   git clone https://github.com/seu-usuario/desafio-controle-fluxo.git
   ```
2. Navigate to the project folder:
   ```bash
   cd desafio-controle-fluxo
   ```
3. Compile the code:
   ```bash
   javac -d bin src/*.java
   ```
4. Run the program:
   ```bash
   java -cp bin Contador
   ```

