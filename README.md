# Previssao_tempo_Dataside
Objetivo
Avaliar conhecimentos nas linguagens Python e SQL e na engine de processamento Apache Spark.
Descrição
Neste desafio, você desenvolverá um notebook que será responsável por extrair dados de
previsão do tempo das cidades do Vale do Paraíba, região onde se localiza a Dataside. Para
consultar todas as cidades dessa região, utilizaremos a API do IBGE. No caso, basta realizar
uma requisição HTTP com o método GET, utilizando a URL abaixo:
https://servicodados.ibge.gov.br/api/v1/localidades/mesorregioes/3513/municipios
Com esses dados, gerar um data frame e a partir dele uma temp view. Ex: "cities"
Utilizando os nomes das cidades, deverão ser consultados os dados de previsão de tempo para
cada cidade. Para realizar essa consulta, poderá ser utilizada qualquer uma das APIs
informadas no link abaixo.
Public APIs - Wather
Obs.: Para algumas, pode ser necessário cadastrar-se para acessar sua API Key. Mas nenhuma
delas deve precisar cadastrar cartão de crédito ou adicionar qualquer valor monetário para
utilizar. Caso alguma solicite, basta optar por outra.
Com os dados consultados, gerar um data frame e partir dele outra temp view. Ex: "forecasts"
Com as temp views geradas, utilizar Spark SQL para criar queries e gerar data frames das
seguintes tabelas:
Tabela 1: dados de previsão do tempo para os próximos cinco dias, para cada data e
cidade consultadas. As colunas dessa tabela serão:
Cidade
CodigoDaCidade
Data
Regiao
Pais
Latitude
Desafio: Consumo de Dados para Previsão do Tempo das
Cidades do Vale do Paraíba.
