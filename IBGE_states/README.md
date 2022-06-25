# Projeto IBGE Estados
<br>

Esse projeto teve como objetivo analisar as variáveis que possuem maior correlação com o IDH de cada estado do Brasil. Para isso foi utilizado a biblioteca de webscraping BeautifulSoup para realizar a aquisição de dados do site do IBGE e Regex para a limpeza do conjunto de dados.
A correlação foi analisada para as seguintes variáveis:
* Matrículas em escolas primárias;
* População;
* Número total de veículos;
* Renda per capita.

A variável que obteve melhor correlação foi a de renda per capita o que já era esperada pois a mesma faz parte da fórmula para o cálculo do IDH. O mesmo era esperado para a variável de matrículas em escolas primárias, porém nela foi observado o menor valor de correlação dentre as variáveis.
Outro fator analisado no projeto foi a distribuição do IDH nas regiões brasileiras. Para isso foi utilizado a biblioteca Geopandas e feita a plotagem do mapa dos estados com seus respectivos valores de IDH. Com isso, percebeu-se que no Brasil estados localizados na região Sul, Sudeste e Centro-Oeste tendem apresentar IDH maiores que nas demais regiões brasileiras.  
