# Projeto Extensao Observatorio Climatico Local

# Sobre o projeto

O Observatório Climático Local é um projeto extensionista voltado à coleta, organização e análise de dados meteorológicos históricos de uma localidade.

A iniciativa busca transformar informações meteorológicas em indicadores acessíveis, contribuindo para a compreensão das condições climáticas locais e oferecendo subsídios informativos ao público beneficiário.

O desenvolvimento utiliza ferramentas de análise e engenharia de dados, integrando coleta por API, tratamento com Python, armazenamento em DuckDB e consultas SQL.

# Objetivos

  * Coletar dados meteorológicos históricos por meio de uma API pública.
  * Organizar e padronizar as informações obtidas.
  * Verificar a qualidade e a consistência dos registros.
  * Armazenar os dados em um banco DuckDB.
  * Desenvolver consultas SQL para calcular indicadores meteorológicos.
  * Produzir informações que possam contribuir para as necessidades da comunidade beneficiária.

# Fonte de dados

  * Open-Meteo — Historical Weather A: https://open-meteo.com/en/docs/historical-weather-api
      A API será utilizada para obter informações meteorológicas históricas a partir das coordenadas geográficas e do período selecionado.

# Perguntas analíticas

1. Como se comportaram as temperaturas mínimas e máximas durante o período analisado?
2. Qual foi o volume de precipitação e como ele se distribuiu ao longo do período?
3. Quais padrões podem ser observados entre temperatura e precipitação?

# Indicadores
* Temperatura máxima média.
* Temperatura mínima média.
* Precipitação acumulada.
* Quantidade de dias com precipitação igual ou superior a 1 mm.
* Amplitude térmica média.

# Tecnologias
* Python: Desenvolvimento do processo
* Requests: Comunicação com a API
* pandas: Tratamento e validação dos dados
* DuckDB: Armazenamento analítico
* SQL: Consultas e cálculo dos indicadores

# Arquitetura
O processo será organizado em etapas:
* Coleta: obtenção dos dados meteorológicos por meio da API Open-Meteo.
* Preservação: armazenamento da resposta original em formato JSON.
* Tratamento: organização, padronização e validação dos registros com pandas.
* Armazenamento: carga dos dados tratados em uma tabela DuckDB.
* Análise: desenvolvimento de consultas SQL e cálculo dos indicadores.
* Interpretação: análise dos resultados considerando as necessidades do público beneficiário.

# Finalidade extensionista

O projeto busca disponibilizar informações meteorológicas organizadas e compreensíveis, contribuindo para a disseminação do conhecimento sobre as condições climáticas locais e atendendo às necessidades do público beneficiário.

# Status do desenvolvimento
As etapas de implementação, coleta, tratamento, armazenamento e análise serão documentadas progressivamente conforme o desenvolvimento do projeto.
