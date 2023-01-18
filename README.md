# Modern Data Stack

Repositório para armazenar os artefatos do Pipeline utilizando Modern Data Stack com AirByte + DBT + Airflow + SnowFlake + Metabase


## Infraestrutura:

- Setup do ambiente de desenvolvimento (Hardware, Software - Linux, Python, Docker, Curl, Pip, Git, Npm, etc...) - Construído com o Gitpod

- Setar as Permissoes do Gitpod ao Repositorio no Github - Ok

- Subir o Airbyte via docker 
    - Fork no projeto do Airbyte -- https://github.com/jorgebarrosmedeiros/airbyte.git
    - Clonar o repositório - git clone -b modern-data-stack https://github.com/jorgebarrosmedeiros/airbyte.git
    - cd airbyte
    - docker-compose-up

- Subir o Airflow via docker 

- Subir o Metabase via docker 

- Criar o script de execução 

- Testar a Execução 

- Snowflake Data Warehouse:
    
    - Criar a Conta no SnowFlake X
    - Verificar a existência das tabelas X
    - Obter os links de conexão e nome da conta X


## Extração:

- No Airbyte:

    - Conectar com as origens baseadas nos Csvs X
    - Criar as entidades no snowflake através do script base da documentação    X
    - Conectar o destino no snowflake X
    - Criar as conexões do airbyte associando as origens ao destino X
    - Testar as conexões X


## Preparação:

- No Airbyte (Destination Loading Method):

    - Local Staging (Ambiente de Desenvolvimento) X
    - Cloud Staging (Ambiente de Produção) X


## Transformação:

- No Dbt:

    - Criação da Conta  X
    - Conexão com o Github  X
    - Criação do Dbt Project  X
    - Criação do Profile de conexão com o snowflake X
    - Criação do Schema X
    - Criação dos Modelos Base X
    - Criação do Modelo Relacionado X
    - Visualização gráfica do modelo X 
    - Teste de execução X
    - Commits, Branches, Pull Requests, Merges no Github  X
    - Obtenção do link de conexão com o Airbyte  X


## Visualização:

- No Metabase:

    - Conectar Metabase com o Snowflake 
    - Criar uma Question  
    - Criar um Dashboard 
    - Adicionar uma Question 
    - Visualizar o Resultado  


## Orquestração:

- No Airflow:

    - Criar a dag  

    - Criar a Docker network

    - Incluir nos composes a network criada

    - Setup Up no serviço

    - Testar a conexao entre os containers do airflow e do airbyte

    - Criar as conexões com o Airbyte através do script  

    - Testar a execução do pipeline  


## Encerramento:

- Material de Apoio:

    - Links 

    - Códigos fonte

    - Apresentação