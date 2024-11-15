# Resolução Atividade de implementação de testes Unitários com JUnit

### Aluno:
Kayk Dario Correia de Araujo - 01612869

## Perguntas:

### Por que é importante escrever testes unitários para cada método?

Os testes servem como uma forma de documentação do comportamento esperado do código. Eles mostram como os métodos devem ser usados e quais resultados são esperados.  Ajudam a identificar bugs e falhas no código logo no início do desenvolvimento, antes que o software seja integrado ou liberado. Isso reduz o custo e o tempo de correção de erros

### O que significa um teste ser "unitário" e como isso difere de outros tipos de testes?

Um teste unitário é um teste que verifica o comportamento de uma única unidade de código, geralmente uma função ou método. O objetivo é garantir que essa unidade funcione corretamente de forma isolada, sem depender de outras partes do sistema.


### Que tipo de exceções vocês observaram ao tentar dividir por zero e como o teste ajudou a identificar problemas?

 Ao tentar dividir um número por zero, a exceção que geralmente é lançada é ArithmeticException em Java, com uma mensagem que pode ser "Divisão por zero não é permitida." Essa exceção é uma forma de o Java sinalizar que a operação não é válida. Sem esse teste, o código poderia falhar em produção, resultando em comportamentos inesperados ou falhas no sistema. O teste ajuda a garantir que o código seja robusto e trate adequadamente casos de erro.