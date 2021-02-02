# Desafio técnico para a vaga de Time de Dados e Projetos  Bemol


:arrow_right: Código fonte no arquivo :arrow_right: **Desafio Bemol - Código Fonte.ipynb**

:arrow_right: Gráficos e tabelas de saída na pasta :arrow_right: **Saídas**

:arrow_right: Relatório com os resultados de saída no arquivo :arrow_right: **Relário_resultados.ipynb** :arrow_down:

#

### Dataset
* Dados Questão1

|num_compra|usuario|nome|Tipo de Mercadoria|Filial|data_compra|valor_compra|Imposto|CPF NA NOTA?|
|---|---|---|---|---|---|---|---|---|
|24937847|295|ANDERSON|SPLIT 8501 À 10000|Loja Autazes|06/04/2020 12:25:13|2582,4|116,208|Sim|
|23600787|331|RAIMUNDO|SPLIT INV 8501À10000|Loja Manicor é |06/04/2020 14:03:55|1919,28|86,3676|Sim|
|24298956|370|ROSILANE|SPLIT ACIMA DE 30000|Loja Manicor é |06/04/2020 14:35:14|10121,04|455,4468|Sim|


<br>

* Dados Questão2

|data_compra|inicio|termino|Loja|codloja|produto|EAN|Valor Unitário Sem Imposto|quantidade|valor_total|Impostos|Dinheiro de Volta (Aplicado direto no total)|
|--|--|--|--|--|--|--|--|--|--|--|--|
|430|05/07/2019 10:30:41|2019-07-05|2019-07-20|Unidade Manaus 1|49618556000135|Smart Pro|190199383180|3000|1|3.331,29|45|
|430|05/07/2019 11:58:18|2019-07-05|2019-07-20|Unidade Manaus 1|49618556000135|Smart Pro|190199383180|3000|1|3.331,29|45|
|430|05/07/2019 14:06:58|2019-07-05|2019-07-20|Unidade Manaus 1|49618556000135|Smart Pro|190199383180|3000|1|3.331,29|45|


#

#### Desario

Confecção de relatório com gráficos e tabelas

* Quem mais vendeu em tal unidade
* Porcentagem de CPF na nota
* Porcentagem de imposto
* Quanto o dinheiro de volta rendeu em desconto
* Venda por vendedor(nome)
* Produto mais vendido

#

OBS: Como não haviam informações sobre os campos do dataset, assumi que o dataset **Dados Questão1** são dados de venda e o **Dados Questão2** são dados de compra.

Tópicos do relatório:

* Visualiando os 3 vendedores que mais venderam em cada filial/loja (Dados Questão 1)
* Visualizando a porcentagem de pedidos de inclusão de CPF na nota em cada filial/loja (Dados Questão1)
* Visualizando a composição do valor do produto (% de imposto em cima do produto) (Dados Questão1)
* Vizualizando o total vendido (R$) em cada loja e o valor referente ao imposto
(Dados - Questão1)
* Quanto o dinheiro de volta rendeu em desconto
(Dados - Questão2)
* Desconto dos produtos em relação a quantidade comprada
(Dados - Questão2)
* Venda por Vendedor
(Dados - Questão1)
* Produto mais vendido
(Dados - Questão1)

#

### Visualiando os 3 vendedores que mais venderam em cada filial/loja <br>(Dados - Questão1)

<br>
<img src="https://github.com/Klemersoncastro/Desafio-t-cnico-Bemol/blob/main/Sa%C3%ADdas/Tabela%20em%20PNG-%20Top%203%20vendedores%20de%20cada%20loja.png?raw=true" align="center">

<br>
<img src="https://github.com/Klemersoncastro/Desafio-t-cnico-Bemol/blob/main/Sa%C3%ADdas/Gr%C3%A1fico%20-%20Top%203%20vendedores%20de%20cada%20loja.png?raw=true" align="center">

<br> 

### Visualizando a porcentagem de pedidos de inclusão de **CPF na nota** em cada filial/loja <br>(Dados - Questão1) 

<br>

<img src="https://github.com/Klemersoncastro/Desafio-t-cnico-Bemol/blob/main/Sa%C3%ADdas/Gr%C3%A1fico%20-%20Porcentagem%20de%20pedidos%20de%20CPF%20na%20nota%20de%20cada%20loja.png?raw=true" align="center">

<br>

### Visualizando a composição do valor do produto (% de imposto em cima do produto)<br> (Dados - Questão1)

<br>

<img src="https://github.com/Klemersoncastro/Desafio-t-cnico-Bemol/blob/main/Sa%C3%ADdas/Gr%C3%A1fico%20-%20Porcentagem%20de%20imposto.png?raw=true" align="center">

<br>

### Vizualizando o total vendido (R$) em cada loja e o valor referente ao imposto <br>(Dados - Questão1)

<br>

<img src="https://github.com/Klemersoncastro/Desafio-t-cnico-Bemol/blob/main/Sa%C3%ADdas/Gr%C3%A1fico%20-%20Total%20vendido%20em%20cada%20loja%20em%20reais.png?raw=true" align="center">

<br>

### Quanto o dinheiro de volta rendeu em desconto <br>(Dados - Questão2)

<h4>- Desconto total por produto e por filial/loja</h4>

<br>

<img src="https://github.com/Klemersoncastro/Desafio-t-cnico-Bemol/blob/main/Sa%C3%ADdas/Gr%C3%A1fico%20-%20Desconto%20total%20por%20produto%20e%20loja.png?raw=true" align="center">

<br>

### Desconto dos produtos em relação a quantidade comprada <br>(Dados - Questão2)

<br>

<img src="https://github.com/Klemersoncastro/Desafio-t-cnico-Bemol/blob/main/Sa%C3%ADdas/Tabela%20em%20PNG%20-%20desconto%20dos%20produtos%20em%20rela%C3%A7%C3%A3o%20a%20quantidade%20comprada.png?raw=true" align="center">

<br><br>
---
<img src="https://github.com/Klemersoncastro/Desafio-t-cnico-Bemol/blob/main/Sa%C3%ADdas/Gr%C3%A1fico%20-%20Desconto%20dos%20produtos%20em%20rela%C3%A7%C3%A3o%20a%20quantidade%20comprada.png?raw=true" align="center">
---
<br>

### Venda por Vendedor <br>(Dados - Questão1)

<h4>-  Concentração / Distribuição da quantidade de vendas dos vendedores de cada loja </h4>

<br>

<img src="https://github.com/Klemersoncastro/Desafio-t-cnico-Bemol/blob/main/Sa%C3%ADdas/Gr%C3%A1fico%20-%20concentra%C3%A7%C3%A3o_distribui%C3%A7%C3%A3o%20da%20quantidade%20de%20vendas%20dos%20vendedores%20de%20cada%20loja%20(1).png?raw=true" align="center">

<br>

### Produto mais vendido <br>(Dados - Questão1)

<h4>- Top 10 produtos mais vendidos por loja</h4>

<br>

<img src="https://github.com/Klemersoncastro/Desafio-t-cnico-Bemol/blob/main/Sa%C3%ADdas/Gr%C3%A1fico%20-%20Top%2010%20produtos%20mais%20vendidos%20por%20loja.png?raw=true" align="center">
