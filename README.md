<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=80&color=77080E&text=ようこそ&fontSize=18&fontAlign=83&fontColor=E1FDFE&animation=scaleIn"/>

<div>
    <img src="icons8-python.gif" alt="Outra imagem" height="90" width="90">
</div>

# Python

## Repository intended to hold exercises to consolidate the Python language.

## Conceitos básicos da sintaxe em Python:

- ### Identação:

No Python, a indentação (espaços ou tabulações no início de uma linha) é utilizada para delimitar blocos de código. Diferente de outras linguagens que utilizam chaves ou palavras-chave, o Python utiliza a indentação para determinar o escopo das declarações. Por exemplo: 

if condition:

    # Bloco de código se a condição for verdadeira

    instrucao1
    instrucao2

else:

    # Bloco de código se a condição for falsa

    instrucao3
    instrucao4

- ### Comentários:

Os comentários são linhas de texto no código que são ignoradas pelo interpretador do Python. Eles são utilizados para explicar ou documentar o código. No Python, os comentários de uma única linha começam com o símbolo #, enquanto os comentários de várias linhas são delimitados por três aspas """ . Por exemplo:

### Este é um comentário de uma única linha:

    """
    Este é um comentário
    de várias linhas
    """

### Ponto e vírgula:

Diferente de outras linguagens, o Python não requer o uso de ponto e vírgula (;) ao final de cada instrução. No entanto, se você desejar escrever várias instruções em uma única linha, pode separá-las com um ponto e vírgula. Por exemplo:

    instrucao1; instrucao2; instrucao3

- ### Uso de parênteses:

Os parênteses são utilizados para agrupar expressões, definir funções e realizar chamadas a funções. Por exemplo:

    resultado = (a + b) * c

## Tipos de dados básicos:

Em Python, os tipos de dados básicos são as categorias nas quais podemos classificar os valores que utilizamos em nossos programas. Compreender os diferentes tipos de dados é fundamental para trabalhar com variáveis e realizar operações em Python. Os tipos de dados básicos incluem:

- ### Inteiros (int):

Os números inteiros são aqueles que não têm parte decimal. Em Python, são representados simplesmente escrevendo o número sem aspas nem pontos decimais. Por exemplo:

    idade = 25
    quantidade = 100

- ### Flutuantes (float):

Os números flutuantes, também conhecidos como números de ponto flutuante, são aqueles que têm uma parte decimal. Em Python, são representados utilizando um ponto para separar a parte inteira da parte decimal. Por exemplo:

    preço = 9.99
    altura = 1.75

- ### Cadeias de texto (strings):

As cadeias de texto, ou simplesmente cadeias, são sequências de caracteres encerradas entre aspas simples ('...') ou duplas ("..."). São utilizadas para representar texto em Python. Por exemplo:

    nome = "Juan"
    mensagem = '¡Hola, mundo!'

Você pode incluir caracteres especiais nas cadeias utilizando o caractere de escape \. Por exemplo, para incluir aspas dentro de uma cadeia, você pode usar \' ou \". Também pode utilizar a notação de tripla aspa ('''...''' ou """...""") para criar cadeias de várias linhas.

- ### Booleanos:

Os valores booleanos representam os valores de verdade: True (verdadeiro) e False (falso). São comumente utilizados em expressões condicionais e operações lógicas. Por exemplo:

    é_maior_de_idade = True
    tem_desconto = False

## Variáveis:

As variáveis são contêineres que nos permitem armazenar e manipular dados em nossos programas. Você pode pensar em uma variável como uma etiqueta à qual você atribui um valor específico. Em Python, não é necessário declarar o tipo de dados de uma variável com antecedência, pois o Python infere o tipo de dados automaticamente com base no valor atribuído.

- ### Declaração e atribuição de variáveis:

As variáveis são contêineres que nos permitem armazenar e manipular dados em nossos programas. Para declarar e atribuir um valor a uma variável em Python, utilizamos o operador de atribuição =. O nome da variável vai à esquerda do operador, e o valor que você deseja atribuir vai à direita. Por exemplo:

    nome = "Juan"
    idade = 25
    altura = 1.75
    é estudante = True

No exemplo, declaramos e atribuímos valores às variáveis nome, idade, altura e é_estudante. O Python infere automaticamente o tipo de dados de cada variável com base no valor atribuído.

Você também pode atribuir o mesmo valor a várias variáveis em uma única linha usando o operador de atribuição múltipla:

    a = b = c = 10

Neste caso, as variáveis a, b e c terão o valor 10.

- ### Regras para nomear variáveis:

- Os nomes das variáveis só podem conter letras (a-z, A-Z), números (0-9) e sublinhados (_). Não podem começar com um número.
- O Python diferencia maiúsculas de minúsculas, então nome e Nome são variáveis diferentes.
- Não se pode usar palavras-chave reservadas do Python como nomes de variáveis (por exemplo, if, else, for, while, etc.).
- Recomenda-se usar nomes descritivos para as variáveis, que indiquem claramente seu propósito: nome, idade, total_vendas, etc.

Seguindo essas regras, alguns exemplos de nomes de variáveis válidos são:

    idade
    nome_completo
    total_vendas
    _contador

E alguns exemplos de nomes de variáveis inválidos são:

    1idade   # Começa com um número
    nome-completo   # Usa um hífen em vez de um sublinhado
    
    if # Palavra-chave reservada do Python

## Operadores:

Os operadores são símbolos especiais que nos permitem realizar operações em variáveis e valores. Python fornece diferentes tipos de operadores para realizar operações aritméticas, comparações e operações lógicas.

- ### Aritiméticos:

Os operadores aritméticos são utilizados para realizar operações matemáticas básicas. Os principais operadores aritméticos em Python são:

- Soma (+): soma dois valores.
- Subtração (-): subtrai o segundo valor do primeiro.
- Multiplicação (*): multiplica dois valores.
- Divisão (/): divide o primeiro valor pelo segundo e devolve um resultado de tipo flutuante.
- Divisão inteira (//): divide o primeiro valor pelo segundo e devolve um resultado de tipo inteiro (a parte decimal é descartada).
- Módulo (%): devolve o resto da divisão entre o primeiro valor e o segundo.
- Exponenciação (**): eleva o primeiro valor à potência do segundo.

Exemplos:
    
    a = 10
    b = 3

    soma = a + b   # 13
    subtracao = a - b    # 7
    multiplicacao = a * b    # 30
    divisao = a / b   # 3.333333333
    divisao_inteira = a // b   # 3
    modulo = a % b   # 1
    exponenciacao = a ** b   # 1000

- ### De comparação:

Os operadores de comparação são utilizados para comparar dois valores e devolvem um valor booleano (True ou False) segundo o resultado da comparação. Os operadores de comparação em Python são:

- Igual a (==): devolve True se ambos os valores são iguais.
- Diferente de (!=): devolve True se os valores são diferentes.
- Maior que (>): devolve True se o primeiro valor é maior que o segundo.
- Menor que (<): devolve True se o primeiro valor é menor que o segundo.
- Maior ou igual que (>=): devolve True se o primeiro valor é maior ou igual que o segundo.
- Menor ou igual que (<=): devolve True se o primeiro valor é menor ou igual que o segundo.

Exemplos:

    a = 10
    b = 3

    igual = a == b   # False
    diferente = a != b   # True
    maior que = a > b   # True
    menor que = a < b   # False
    maior ou igual = a >= b   # True
    menor ou igual = a <= b   # False

- ### Lógicos:

Os operadores lógicos são utilizados para combinar expressões condicionais e avaliar múltiplas condições. Os operadores lógicos em Python são:

- AND (and): devolve True se ambas as condições são verdadeiras.
- OR (or): devolve True se ao menos uma das condições é verdadeira.
- NOT (not): inverte o valor de uma condição, devolve True se a condição é falsa e False se a condição é verdadeira.

Exemplo:

    a = 10
    b = 3

    resultado_and = (a > 5) and (b < 5)   # True
    resultado_or = (a > 15) or (b < 5)   # True
    resultado_not = not (a > 5)   # False
    Você pode utilizar esses operadores para realizar cálculos, tomar decisões baseadas em comparações e combinar condições lógicas em seus programas.

## Estruturas Condicionais:

As estruturas condicionais nos permitem executar diferentes blocos de código segundo se cumpra ou não uma determinada condição. Em Python, as estruturas condicionais mais utilizadas são if, if-else e if-elif-else.

- IF - A estrutura if é utilizada para executar um bloco de código se uma condição for verdadeira. 
- IF-ELSE - A estrutura if-else nos permite especificar um bloco de código alternativo que será executado se a condição do if for falsa.
- IF-ELIF-ELSE - A estrutura if-elif-else nos permite especificar múltiplas condições e blocos de código alternativos. 

- ### Loops:

Os loops nos permitem repetir um bloco de código várias vezes. Em Python, os loops mais comuns são for e while.

- For - O loop for é utilizado para iterar sobre uma sequência (como uma lista, uma tupla ou uma string) ou qualquer objeto iterável. 
- While - O loop while é utilizado para repetir um bloco de código enquanto uma condição for verdadeira. 

- ### Controle de Loops:

- Break - A instrução break é utilizada para sair prematuramente de um loop, independentemente da condição. Quando um break é encontrado, o loop é interrompido e o fluxo de execução continua com a próxima instrução fora do loop.
- Continue - A instrução continue é utilizada para pular o restante do bloco de código dentro de um loop e passar para a próxima iteração.
- Pass - A instrução pass é uma operação nula que não faz nada. É utilizada como um marcador de posição quando uma instrução é sintaticamente necessária, mas nenhuma ação é desejada.

## Conclusão:
As estruturas de controle são ferramentas poderosas que nos permitem controlar o fluxo de execução de nossos programas. Com as estruturas condicionais (if, if-else, if-elif-else) podemos tomar decisões baseadas em condições, enquanto que com os loops (for, while) podemos repetir blocos de código várias vezes. Além disso, as instruções break, continue e pass nos fornecem um controle adicional sobre o comportamento dos loops.

<hr>

<div align="center">
    <img width="200" src="a-logo-design-in-an-oriental-style-featu_i-4pO2wTT92w3TENQ8Gg6A_naugfvo1SRq3Q7v-Y8cNlA.png"/>
</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=80&color=77080E&fontSize=14&fontAlign=83&fontColor=E1FDFE&animation=scaleIn&section=footer"/>


