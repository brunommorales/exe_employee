# Gerenciamento de Funcionários em Java

Este projeto é um programa simples de gerenciamento de funcionários em Java. Ele demonstra várias habilidades e conceitos fundamentais da programação em Java.

## Tecnologias e Conceitos Utilizados

- **Java**: Linguagem de programação principal.
- **Orientação a Objetos**: Modelagem da entidade "Employee" usando classes e objetos.
- **Collections**: Utilização da classe `ArrayList` para armazenar funcionários.
- **Entrada de Dados**: Captura de entrada do usuário com a classe `Scanner`.
- **Manipulação de Strings**: Operações de entrada e saída de texto.
- **Tratamento de Exceções**: Lidando com exceções, como IDs duplicados.
- **Stream e Lambdas**: Uso da Java Stream API para filtrar e localizar funcionários.
- **Encapsulamento**: Princípio de encapsulamento com atributos privados e métodos getters/setters.
- **Internacionalização**: Configuração da localização padrão com `Locale`.
- **Cálculos Matemáticos**: Aumento de salário com base em uma porcentagem.

## Como Usar

1. Clone este repositório: `git clone https://github.com/brunommorales/exe_employee.git`
2. Compile o código-fonte: `javac application/Main.java`
3. Execute o programa: `java application.Main`

Siga as instruções no console para registrar funcionários e realizar aumentos salariais.

## Exemplo de Uso

```shell
How many employees will be registered? 3

Employee #1:
Id: 1001
Name: John
Salary: 5000.00

Employee #2:
Id: 1002
Name: Jane
Salary: 4500.00

Employee #3:
Id: 1003
Name: Bob
Salary: 3000.00

Enter the employee id that will have salary increase: 1002
Enter the percentage: 10.0

List of employees:
Id: 1001, Name: John, Salary: 5000.00
Id: 1002, Name: Jane, Salary: 4950.00
Id: 1003, Name: Bob, Salary: 3000.00
