# A Cláusula `SELECT`: Projeção, Aliases e Expressões Calculadas

## O que é a clásula `SELECT`?

O `DQL` (Data Query Language ou Linguagem de Consulta de Dados) é o subconjunto da linguagem `SQL` (Structured Query Language ou Linguagem de Consulta Estruturada) usado exclusivamente para consultar, buscar e recuperar dados armazenados em um banco de dados relacional.
O principal e único comando do `DQL` é o `SELECT`. Ele não **altera**, **apaga** ou **cria** dados na tabela; esse comando define quais colunas (ou cálculos) você deseja extrair da tabela (conceito de projeção na álgebra relacional).

> Para selecionar algo, eu preciso saber o local e como esse algo está armazenado ( onde estão os dados? como esses dados estão estruturados? )

## Elementos iniciais do `SELECT`: 
 - `SELECT *`: Elemento * (conringa) indica a necessidade de trazer todas as colunas da tabela (). Útil para testes, mas evitado em produção por desempenho.
 - Seleção de Colunas Específicas: Traz apenas o necessário (SELECT nome, email).
 - Aliases (`AS`): Renomeia visualmente os cabeçalhos das colunas no resultado para tornar o relatório legível.
 - Expressões e Colunas Calculadas: É possível realizar operações matemáticas e concatenações diretamente no `SELECT` sem alterar os dados salvos no banco.





