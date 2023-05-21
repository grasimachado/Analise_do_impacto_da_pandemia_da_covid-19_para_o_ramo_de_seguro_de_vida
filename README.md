# Analise_do_impacto_da_pandemia_da_covid-19_para_o_ramo_de_seguro_de_vida

Resumo. Segundo noticiado em diversas fontes de informação, a busca por seguro de vida acelerou na pandemia, pois as pessoas ficaram mais conscientes dos riscos e da vulnerabilidade diante da doença. E essa mudança de comportamento, trouxe um aumento na demanda por esse tipo de produto, e também em alguns casos uma maior dificuldade para as Seguradoras em relação ao pagamento das indenizações.
Diante desse cenário, minha curiosidade ficou aguçada e quis verificar através dos dados, como foi de fato esse impacto no ramo de seguro de vida.
Esse projeto visa através dos dados, verificar a evolução do prêmio direto e sinistros de seguros do ramo vida antes, durante e logo após o período da pandemia da covid-19.
Utilizando as técnicas e ferramentas de BI, os dados foram extraídos com a ferramenta PDI, e armazenados em um DW, que permitiu através da ferramenta Power BI elaborar relatórios com gráficos e alguns indicadores, tornando possível verificar como foi a evolução do prêmio e sinistro ao longo dos últimos seis anos.
 
1.	Introdução

O escopo desse projeto é o de verificar qual o impacto da pandemia do covid-19 para o ramo de seguro de vida no Brasil através de dados disponibilizados pela SUSEP (órgão fiscalizador e regulador do ramo de seguro), levando em consideração as dimensões de empresas, ramos, região geográfica do Brasil dos últimos seis anos.

Busca-se verificar a evolução do prêmio direto e sinistros de seguros, principalmente do segmento vida no período anterior, durante e logo após o período crítico da pandemia do covid-19, utilizando para isso ferramentas e as técnicas de BI.
2.	Modelagem

O processo de BI proposto para o projeto tem como fontes de dados os arquivos csv, que foram extraídos através da ferramenta Pentaho Data Integration (PDI) e após as devidas transformações (etapa ETL), foram posteriormente armazenados em um DW criado no SGBD Postgres, em um modelo estrela com dimensão tempo, empresa, ramos e região geográfica.

Os relatórios foram desenvolvidos através da ferramenta Microsoft Power BI, acessando os dados diretamente do DW.

3.	Resultados

Foram desenvolvidos dois dashboards: um apresentando um Panorama Geral com os principais indicadores do mercado de Seguros e um segundo com o foco mais específico no segmento Vida.

Foi possível verificar que realmente houve um crescimento bem expressivo nos prêmios diretos (46,31%) e nos sinistros ocorridos (44,68%) no período de 2017 a 2022, no segmento vida, e com a sinalização de tendência de crescimento no valor do prêmio direto e queda no valor de sinistro.

4.	Conclusão

Conforme visto nos relatórios gerados, realmente o impacto da pandemia da covid-19 para o ramo de seguro de vida foi significativo e como sinaliza uma tendência de crescimento mesmo após o término da pandemia, isso leva a crer que uma parte dos brasileiros passou a ter uma visão diferente sobre o seguro de vida no seu planejamento familiar. O que parece ser uma sinalização muito positiva para as Seguradoras que se adaptarem as novas exigências e demandas desse novo consumidor.
