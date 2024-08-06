# Desafio Google Analytics (Empresa fictícia Cyclistic - Programa de Marketing)
## Pergunta de negócio: Como os membros anuais e casuais usam as bicicletas de maneiras diferentes?

## Ferramentas e Bibliotecas Utilizadas

Este projeto foi desenvolvido utilizando as seguintes ferramentas e bibliotecas:

- **Google Colab**: Ambiente de desenvolvimento em nuvem que permite executar Python diretamente no navegador, sem necessidade de configuração adicional.
- **pandas**: Biblioteca essencial para manipulação e análise de dados.
- **NumPy**: Biblioteca fundamental para computação científica em Python.
- **gc**: Biblioteca de coleta de lixo, usada para otimizar a memória durante a manipulação de grandes conjuntos de dados.
- **os**: Biblioteca que fornece uma forma portátil de usar funcionalidades dependentes do sistema operacional.
- **Matplotlib**: Biblioteca utilizada para criação de visualizações e gráficos.

## Etapas do Projeto

1. Coleta dos dados no site informado pela empresa: arquivos CSV;
2. Exploração e Análise Inicial dos Dados: identifiquei possíveis problemas;
3. Limpeza de Dados: Removi duplicatas, linhas com valores nulos e ajustei as colunas de data/hora para datetime;
4. Preparação dos Dados: realizei a concatenação das 12 planilhas em um único Dataframe.
5. Análise Exploratória de Dados (EDA): explorei os dados;
6. Relatório e Comunicação: comuniquei os resultados.


## Conclusões

- **Duração Média das Viagens:**
  - A duração média das viagens é maior entre os usuários casuais. Isso pode ser interpretado como um padrão de uso para atividades recreativas, como passeios em parques. Em contraste, os membros tendem a realizar viagens mais curtas, possivelmente relacionadas a compromissos diários como trabalho ou escola.

- **Quantidade de Viagens:**
  - Um membro faz aproximadamente 29% mais viagens do que um usuário casual, embora as viagens dos membros sejam geralmente mais curtas.

- **Horário de Uso:**
  - O horário de uso reforça a finalidade das viagens dos membros. Observou-se que eles utilizam o serviço com maior frequência no início da manhã e no final da tarde. Em contraste, os usuários casuais tendem a usar o serviço durante a madrugada e no meio da tarde, períodos em que o transporte público pode ser menos frequente.

- **Locais Populares:**
  - Os locais mais populares para os membros e usuários casuais reforçam as conclusões sobre os padrões de uso:
  
  **Top 5 Locais para Membros:**
  1. Clinton St & Washington Blvd  
  2. Kingsbury St & Kinzie St        
  3. Clark St & Elm St             
  4. Wells St & Concord Ln          
  5. Clinton St & Madison St   

  **Top 5 Locais para Usuários Casuais:**
  1. Streeter Dr & Grand Ave             
  2. DuSable Lake Shore Dr & Monroe St     
  3. Michigan Ave & Oak St                 
  4. Millennium Park                       
  5. DuSable Lake Shore Dr & North Blvd  



