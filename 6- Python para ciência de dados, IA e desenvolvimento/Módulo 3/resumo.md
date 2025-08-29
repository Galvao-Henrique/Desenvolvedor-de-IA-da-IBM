# Glossário de Fundamentos de Programação Python

| Termo | Definição | Exemplo |
|---|---|---|
| **Analogy** | Conceito ou comparação externa usada para explicar conceitos de forma mais compreensível. | Comparar variáveis com "caixas" que armazenam valores. |
| **Attributes** | Características ou propriedades de um objeto, acessadas com notação de ponto. | `texto.upper()`, `lista.append()` |
| **Branching** | Alterar fluxo do programa baseado em condições com `if`, `elif`, `else`. | `if idade >= 18:`<br>`    print("Maior")`<br>`else:`<br>`    print("Menor")` |
| **Comparison Operators** | Operadores para comparar valores e retornar resultados booleanos. | `==` (igual), `!=` (diferente), `<` (menor), `>` (maior), `<=` (menor ou igual), `>=` (maior ou igual) |
| **Conditions** | Usadas para tomar decisões no código baseado em expressões True/False. | `if x > 0:`, `while ativo:` |
| **Enumerate** | Função built-in que adiciona contador a iteráveis para loop com índices e elementos. | `for indice, valor in enumerate(lista):` |
| **Exception Handling** | Mecanismo para gerenciar erros e condições excepcionais durante execução. | `try:`<br>`    x = 1/0`<br>`except ZeroDivisionError:`<br>`    print("Erro: divisão por zero")` |
| **Explicitly** | Realizar ação ou especificar algo de forma clara e direta. | `int("10")` (conversão explícita) |
| **For Loops** | Usados para iterar sobre sequências (listas, tuplas, strings) ou objetos iteráveis. | `for item in lista:`<br>`    print(item)` |
| **Global Variable** | Variáveis definidas fora de funções, acessíveis e modificáveis de qualquer parte do código. | `x = 10` (global)<br>`def func():`<br>`    global x` |
| **Incremented** | Aumentar valor de variável por quantidade especificada. | `x += 1`, `contador = contador + 1` |
| **Indent** | Uso de whitespace no início da linha para significar estrutura e escopo de blocos. | `if condicao:`<br>`    print("Dentro do bloco")` (4 espaços) |
| **Indices** | Posição ou localização de elementos em sequência (string, lista, tupla), começando em 0. | `lista[0]` (primeiro elemento) |
| **Iterate** | Realizar operações repetidamente em cada item de coleção usando loops ou iteradores. | `for numero in [1,2,3]:`<br>`    print(numero)` |
| **Local Variables** | Variáveis definidas dentro de função ou bloco, acessíveis apenas dentro desse escopo. | `def func():`<br>`    x = 5` (local) |
| **Logic Operators** | Operadores para operações lógicas em valores booleanos. | `and` (E), `or` (OU), `not` (NÃO) |
| **Loops** | Construtores para repetir bloco de código múltiplas vezes. | `for`, `while` |
| **Parameters** | Placeholders em definições de função para aceitar valores quando chamada. | `def soma(a, b):` (a e b são parâmetros) |
| **Programming Fundamentals** | Fundamentos envolvem variáveis, estruturas de controle, funções, estruturas de dados, I/O e tratamento de erros. | Base de qualquer programa Python |
| **Range Function** | Gera sequência de números para iteração em loops. | `range(5)` → `0,1,2,3,4`<br>`range(1, 10, 2)` → `1,3,5,7,9` |
| **Scope of Function** | Região do código onde variável definida na função é acessível/visível. | Variáveis locais só existem dentro da função |
| **Sequences** | Coleções ordenadas de itens (strings, listas, tuplas) que permitem indexação e iteração. | `"hello"`, `[1,2,3]`, `(4,5,6)` |
| **Syntax** | Conjunto de regras para como código deve ser escrito e estruturado para interpretação correta. | `if condicao:` (dois pontos obrigatórios) |
| **While Loops** | Executam bloco de código repetidamente enquanto condição especificada for verdadeira. | `while contador < 5:`<br>`    print(contador)`<br>`    contador += 1` |