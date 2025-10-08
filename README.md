# tipos-de-dados-de-sql
Tipos de dados em sql
Numéricos:
Permitem armazenar números com precisão exata. Exemplos: 
INT: Números inteiros. 
DECIMAL/NUMERIC: Números decimais com precisão definida. 

Os tipos de dado numérico se dividem principalmente em inteiros (números sem parte fracionária) e ponto flutuante (números com parte fracionária). Além disso, existem categorias como os exatos (inteiros, decimais) e aproximados (ponto flutuante). Exemplos comuns incluem o tipo Integer (inteiro) e Double (ponto flutuante de precisão dupla). 
Tipos de dados numéricos
Dados Numéricos Exatos: 
São armazenados com 100% de precisão. 
Inteiros: Números inteiros positivos ou negativos, sem casa decimal. Exemplos: Integer (inteiro), Byte (números pequenos inteiros), Int64 (inteiros grandes). 
Decimal: Números com ponto fixo, também conhecidos como NUMERIC ou DECIMAL, que mantêm a precisão exata de um número com vírgula. 
Dados Numéricos Aproximados: 
Utilizam o formato de ponto flutuante para armazenar números com parte decimal. 
 
Strings: 
Em ciência da computação, um tipo de dados string representa uma sequência de caracteres, como letras, números, símbolos e espaços, usada para armazenar texto. As strings são definidas como um conjunto de caracteres delimitados por aspas, e são manipuladas por meio de funções específicas.

Qual é a funçaõ do string?
Retorna uma Variante (Cadeia) que contém uma cadeia de caracteres repetida com o comprimento especificado.

Uso da String:
Sequência de Caracteres: Uma string é uma coleção ordenada de caracteres. 
Delimitadores: Geralmente são envoltas por aspas,
Flexibilidade: Podem conter letras, números, símbolos, e espaços em branco. 
Armazenamento de Texto: Servem para guardar nomes de usuário, senhas, mensagens e dados de bancos de dados. 
Manipulação de Dados: São fundamentais para formatar e processar informações textuais em diversas aplicações. 
Índice: É possível acessar caracteres individuais de uma string por sua posição, chamada de índice, que começa em 0. 

Tipos de Data e hora:

•	DATE: 
Armazena apenas a data (dia, mês, ano), mas não a hora.
•	TIME: 
Armazena apenas a hora (HH:mm:ss), com precisão de até nanossegundos, mas sem a data.
•	DATETIME: 
Armazena tanto a data quanto a hora, com diferentes precisões e intervalos dependendo da implementação do sistema.
•	TIMESTAMP: 
Também armazena data e hora, muitas vezes com suporte a frações de segundo, como microssegundos (até 6 dígitos) em sistemas como o MySQL.

Exemplos de Uso :
Banco de Dados e Aplicações

Boleano:

o Booleano (às vezes abreviado para Bool ) é tipo de dado que tem um de dois valores possíveis (geralmente denotados como verdadeiro e falso ) que se destina a representar os dois valores de verdade da lógica e da álgebra boleana. 
Tipo de dado: Uma variável booleana armazena apenas um valor: verdadeiro ou falso. 
Tomada de decisão: Em programação, valores booleanos são usados em condicionais (como comandos if e else) para determinar quais blocos de código serão executados ou ignorados. 
Exemplo: Se uma condição if (idade > 18) for verdadeira, um código será executado; se for falsa, outro código (em um else) poderá ser acionado. 


| Tipo de dados  | Formatar                                  | Intervalo                                                          | Precisão          | Tamanho de armazenamento (bytes) | Precisão de segundo fracionário definida pelo usuário | Deslocamento de fuso horário |
|----------------|-------------------------------------------|--------------------------------------------------------------------|-------------------|----------------------------------|-------------------------------------------------------|------------------------------|
| time           | HH: mm: ss [.nnnnnnnn]                    | 00:00:00.0000000 a 23:59:59.9999999                                | 100 nanossegundos | 3 a 5                            | Sim                                                   | Não                          |
| date           | yyyy-MM-dd                                | 0001-01-01 a 9999-12-31                                            | 1 dia             | 3                                | Não                                                   | Não                          |
| smalldatetime  | aaaa-MM-dd HH:mm:ss                       | 01.01.00 a 06.06.79                                                | 1 minuto          | 4                                | Não                                                   | Não                          |
| datetime       | aaaa-MM-dd HH:mm:ss[.nnn]                 | 1753-01-01 a 9999-12-31                                            | 0,00333 segundo   | 8                                | Não                                                   | Não                          |
| datetime2      | aaaa-MM-dd HH:mm:ss[.nnnnnnn]             | 0001-01-01 00:00:00.0000000 a 9999-12-31 23:59:59.9999999          | 100 nanossegundos | 6 a 8                            | Sim                                                   | Não                          |
| datetimeoffset | aaaa-MM-dd HH:mm:ss[.nnnnnnn] [+\|-]HH:mm | 0001-01-01 00:00:00.0000000 a 9999-12-31 23:59:59.9999999 (em UTC) | 100 nanossegundos | 8 a 10                           | Sim                                                   | Sim                      
