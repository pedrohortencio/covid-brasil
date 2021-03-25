# Informações Sobre os Dados

Como consta na README.md principal, os dados foram baixados de canais oficiais do governo.

## Denatran
Os dados do Denatran, relativos à **quantidade de infrações** cometidas mensalmente nas Unidades da Federação do Brasil, foram extraídos do site do Ministério da Infraestrutura,
dentro da categoria do Denatran. Podem ser encontrados, ao menos durante a confecção desta nota, neste site do [Governo do Brasil](https://www.gov.br/infraestrutura/pt-br/assuntos/transito/conteudo-denatran/estatisticas-quantidade-de-infracoes-denatran).

Foram baixados os dados de 2019 e de 2020. Os dados são mensais, compondo um total de 24 CSVs.

## SUS
Os dados do SUS, relativos aos indicadores de internações, óbitos, dias de internação, etc, por CID, foram obtidos através do [TabNet-DataSUS](http://tabnet.datasus.gov.br/cgi/menu_tabnet_php.htm#).
Esse sistema exige que seja feito um filtro para que os dados requisitados sejam exibidos, de modo que se faz necessário especificar os filtros usados para gerar os dados desta pasta
(usados na análise). As opções usadas para gerar os arquivos CSV foram:
1. Em "Informações em Saúde (TABNET)"
2. Em "Epidemiológicas e Morbidade"
3. Em "Morbidade Hospitalar do SUS (SIH/SUS)"
4. Selecionado "Geral, por local de internação - a partir de 2008"
5. Selecionado "Abrangência geográfica: Brasil por Regionais/Estados"
6. Os campos foram preenchidos da seguinte forma:
    - Linha: "Lista Morb CID-10";
	 - Coluna: "Não ativa";
	 - Conteúdo: todos selecionados;
	 - Período: mês a mês, individualmente, para os anos de 2019 e 2020;
	 - Caráter de Atendimento: "Urgência";
	 - Demais mantidos no padrão;


OS dados colhidos no dia 25/03/2021 entre 19:00 e 20:00.
