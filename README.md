# PowerBI_desafio4
Dashboard criado a partir do conjunto de dados "seguro_saude.csv" de acordo com os requisitos estipulados no arquivo "Desafio-Requisitos V2.pdf".

## <b>Passo a passo para resolução do problema:</b>

<i>--> Carregamento dos dados .csv

--> Transformação dos dados:

- Utilizar primeira linha como cabeçalho;
- Remoção da primeira linha que estava duplicada (2 cabeçalhos);
- Limpeza de registros com valores nulos e/ou inconsistentes com a filtragem.

_________

## <b>Cumprimento dos requisitos do pdf:</b>


-  <b>Requisito número 1:</b>

Foi utilizado um cartão com a soma total da coluna "valor_seguro_saude".
Resposta: R$ 17.68 Mi

-  <b>Requisito número 2:</b>

Foi utilizado um cartão com a média da coluna "idade".
Resposta: 39

-  <b>Requisito número 3:</b>

Foi utilizado um cartão com a média da coluna "valor_seguro_saude".
Resposta: R$ 13.27 Mil

-  <b>Requisito número 4:</b>

Criação de uma nova coluna para faixa etária dividindo a coluna "idade" em grupos com a ferramenta "grupos de dados": 18 a 29, 30 a 39, 40 a 49, 50 a 59 e 60 a 69.

-  <b>Requisito número 5:</b>

Os valores da coluna vão de 0 a 5, portanto não é possível saber se os dados referem-se ao número de filhos, ou se indicam se é criança ou não. No entanto o valor mínimo na coluna "idade" é 18, o que leva ao descarte dessa última possibilidade.  Dessa forma a coluna de dados "crianca" não condiz com a coluna "idade" e não é coerente com o que é pedido, logo tomou-se a decisão de desconsiderá-la.

-  <b>Requisito número 6:</b>

Foi descartado pelo mesmo motivo do requisito de número 5.

-  <b>Requisito número 7:</b>

Foi utilizado um gráfico de dispersão que calcula a relação da idade com o IMC, além disso uma linha de tendência foi adicionada para melhor visualização.
Resposta: a tendência é positiva. Quanto maior a idade, maior o IMC.

-  <b>Requisito número 8:</b>

Foi utilizado um gráfico de rosca para comparação entre os dois gêneros.
Resposta: homens.

-  <b>Requisito número 9:</b>

Foi utilizado um cartão com a média geral do IMC. Quando selecionado o gênero "mulher" no gráfico de rosca é possível analisar qual a média para esse grupo em específico e comparar com a média geral.

-  <b>Requisito número 10:</b>

Foram utilizadas duas visualizações de filtro: regiões e idade. Seleciona-se portanto a região sudeste, a idade de 50 a 64, o gênero "homens" no gráfico de rosca, verifica-se a média de gastos no cartão adicionado "Média de Gastos" e compara-se com a média geral da região.



