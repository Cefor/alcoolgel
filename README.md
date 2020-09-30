# Variações de preço e de quantidade nas compras públicas de álcool em gel durante a COVID-19

### Autores: Gustavo Fernando Fröhlich, Kilma Mônica Donato de Araújo, Fabiano Peruzzo Schwartz

A presente pesquisa se dedica a responder a seguinte pergunta: o preço médio e a quantidade média de itens das compras do álcool em gel sofreram alteração significativa ante o cenário de pandemia da COVID-19? Assumiu-se por hipótese que as condições de oferta e demanda decorrentes do cenário emergencial poderiam resultar em aumento dos preços e das quantidades adquiridas. Foram utilizados dados do [Painel de Preços do Ministério da Economia] (https://paineldeprecos.planejamento.gov.br/) e o teste não paramétrico de Mann-Whitney-Wilcoxon para a comparação dos contextos antes e durante a pandemia. Os resultados sugerem que nos três primeiros meses da crise os preços do álcool em gel dobraram e foram comprados mais frascos do produto do que nos últimos dois anos.  

## Lista de variáveis

| **Variável** | **Descrição** |
| --- | --- |
| Data da Compra | Variável quantitativa, expressa a data da compra. **Exemplo** : 22 Out 2019 |
| Descrição do Objeto | Variável qualitativa, nominal, descreve o bem ou serviço comprado. **Exemplo** : Álcool etílico |
| Unidade | Variável qualitativa, categórica, expressa a unidade de fornecimento do item comprado. **Exemplo** : Frasco 500 ml |
| Valor Unitário | Variável quantitativa, expressa o valor em reais (R$) da unidade de fornecimento comprada. **Exemplo** : R$ 4,52 |
| Quantidade | Variável quantitativa, expressa a quantidade de unidades de fornecimento compradas. **Exemplo** : 250 unidades |
| Período da Pandemia | Variável qualitativa, categórica, com duas categorias: 0 – período anterior à pandemia; 1- período da pandemia. |

## Lista de arquivos

| **Arquivo** | **Descrição** |
| --- | --- |
| df_consultanpan.csv | Compras de álcool em gel, no Distrito Federal, realizadas **antes** da pandemia |
| df_consultapan.csv | Compras de álcool em gel, no Distrito Federal, realizadas **durante** a pandemia |
| df_compras.csv | Consolidação dos dois arquivos anteriores |
| ValorAlcoolGel.Rmd | Código R para a geração dos resultados obtidos |
| ValorAlcoolGel.html | Resultado da execução do arquivos ValorAlcoolGel.Rmd |


## Publicação 

Este estudo foi aceito para publicação na Revista Comunicação em Ciências da Saúde.

