# Burned Areas
Burned Areas - Data Science Project

Esse projeto está inserido no esforço de analisar, desenvolver e combinar técnicas de inteligência artificial com o conhecimento de sistemas ecológicos adquirido pelo INPE ao longo de anos de análise e monitoramento. Informações mais completas e confiávies auxiliam o tomador de decisão a traçar melhores estratégias e se tornam cada vez mais utilizáveis pelo INPE e úteis para a sociedade e a comunidade científica.  

Buscamos responder a pergunta: Como desenvolver uma abordagem de machine learning para classificar áreas queimadas? Apresentamos uma abordagem genérica, automática e ajustável para classificar áreas queimadas composta por estudos para melhorar a automação do processo de compreensão e classificação de áreas queimadas. 

Para isso, disponibilizamos algumas bases de dados de amostras, mostramos os atributos mais relevantes para enriquecer a base de conhecimento, o resultado da aplicação deles em uma comparação de modelos de classificação de machine learning. Validamos nossos estudos com dados de queimadas do Cerrado validados por especialistas. Analisamos modelos robustos o suficiente para manipular dados não classificados previamente e destacamos os melhores resultados obtidos e caminhos futuros de continuidade e melhoria do projeto com novos classificadores baseados em técnicas como deep learning. 

Todas as informações sobre o projeto podem ser encontradas em www.inpe.br/queimadas


************

1. Definição da área de estudo: 
  * Dados correspondentes às bandas 2,3,4,5,6 e 7, do satélite LandSat 8, já processados. 
  * Órbita-ponto: *223_067* 
  * Período: 2017
  Base de dados de áreas queimadas
  [Exemplo Base de Dados 223_067 2017](base_dados_223_067.csv)
  
2. Dados de entrada:
   [Notebook de explicação dos dados](Definicao_Dados_para_Classificacao.ipynb)
   
3. Criação de um modelo de árvore de decisão
   [Criação do modelo Arvore de Decisao](Passo_a_passo_arvores_de_decisao.ipynb)
   
3. Criação do Modelos de dados para áreas queimadas 
   [Criação do modelo Ensemble](Criacao_modelo_classificacao_223_067.ipynb)
 
4. Conjunto de Resultados de Classificação:
   [Resultados das classificações](resultados/)


