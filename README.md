# Covid-19: Uma Análise Sobre os Impactos no SUS e no Trânsito

## Introdução

Conjunto de análises dos impactos da pandemia de Covid-19 nos indicadores do SUS e nos números do trânsito brasileiro (que, até 2019, era a [segunda maior causa de mortes no Brasil](https://tvbrasil.ebc.com.br/reporter-brasil/2019/09/acidentes-de-transito-sao-segunda-maior-causa-de-mortes-no-pais)). Para tal, dados de 2019 serão confrontados com os dados de 2020.

O foco da análise está em elucidar os seguintes pontos:

* Como a pandemia impactou o número de infrações de trânsito no Brasil?
* Qual o impacto no número de internações e óbitos relacionados a acidentes de trânsito?
* Há fundamento na máxima popular: "Existe a impressão de que só há mortes por covid [após o início da pandemia]"?
* Qual foi o impacto causado no número geral de internações e óbitos registrados no SUS?

### Dados Utilizados

As conclusões e análises foram baseadas única e exclusivamente em dados oficiais extraídos de portais do Governo Federal do Brasil. Por transparência, os dados em formato bruto estão armazenados neste respositório (com exceção dos dados de Covid-19, devido ao tamanho que excede o limite do GitHub), tal como os scripts que realizam a importação, limpeza, formatação e manipulação dos dados.

* Dados de Covid-19 foram extraídos do portal [Coronavírus Brasil](http://covid.saude.gov.br/) do Ministério da Saúde.
* Dados de infrações de trânsito foram extraídos do portal do [Ministério da Infraestrutura](https://www.gov.br/infraestrutura/pt-br/assuntos/transito/conteudo-denatran/estatisticas-quantidade-de-infracoes-denatran) no dia 25/03/2021 às 19:00.
* Dados epidemiológicos e de morbidade foram extraídos do sistema [TabNet](http://tabnet.datasus.gov.br/cgi/menu_tabnet_php.htm#), parte do DataSUS, no dia 25/03/2021 às 20:00. Os filtros usados foram especificados na pasta onde os dados estão armazenados.
