# Projeto de Análise e Engenharia de Dados na EstrelaBet
Este repositório apresenta uma coleção de projetos que demontram meu envolvimento e contribuições como Analista de Dados e Engenheiro de Dados na EstrelaBet. Durante meu tempo na empresa, estive envolvido em várias análises e visualizações de dados que forneceram insights valiosos para diferentes áreas do negócio. Aqui estão alguns dos projetos destacados:
## Administração
- Visualizações e insights utilizando Metabase, incluindo análise de:
  - Quantidade de clientes distintos de cassino por mês
  - Top 10 de jogos de cassino mais jogados por mês
  - Top 10 jogos de cassino com maior porcentagem de GGR sobre o GGR total
  - Alertas para monitorar perdas de dados nas tabelas do banco de dados
  - NGR (Net Gaming Revenue) das apostas esportivas em relação às outras apostas
  - Comparativos de registros e depósitos em diferentes intervalos de tempo
## CI (Customer Intelligence)
- Análises envolvendo:
  - Montante de bônus usado por mês
  - Lista de clientes que jogaram um jogo específico
  - Recorrência de entrada de clientes na plataforma (lifetime)
  - Revenue Share por mês para cada afiliado
  - Tendências de comissões, Net & PL, registros, visitas e revenue share
## Comercial de Expansão
- Projeções e análises de dados para:
  - Turnover de afiliados
  - Afiliados que atingiram metas estipuladas
  - Métricas de depósito e utilização de valor depositado
## Segurança de Dados
- Monitoramento de integridade dos dados em todas as tabelas do banco de dados
## E-Sports
- Análises envolvendo:
  - Perfil dos apostadores de e-sports por diferentes variáveis demográficas
  - Lista de usuários que apostaram em e-sports
  - Total e volume das apostas em e-sports por competição e por jogo
## Esporte & Risco
- Controle e análise de:
  - Bônus fornecidos e utilizados
  - Apostas em aberto por fornecedor
  - Rollover diário
  - Uso de bônus por usuários
## CEO
- Criação de dashboard para acompanhar as metas internas da empresa
## Ciência de Dados
- Métricas detalhadas para cada jogo específico, incluindo usuários distintos, montante apostado e quantidade de apostas

# Engenharia de Dados
Durante meu período na EstrelaBet, desempenhei um papel fundamental na implementação de soluções de engenharia de dados. Algumas das contribuições significativas incluem:

- Desenvolvimento de scripts em Python para realizar as seguintes tarefas:

  - Extração de dados, seja do banco de dados interno ou de arquivos CSV
  - Transformação de dados de acordo com os requisitos de negócios
  - Upload dos dados processados para a camada landing designada pela empresa

- Implementação de pipelines de transformação de dados utilizando Python e a biblioteca Pandas, realizando operações avançadas, como:

  - Conversão de arquivos CSV para o formato Parquet
  - Upload dos arquivos Parquet para um bucket S3 para posterior processamento por meio do DBT
  - Realização de transformações e comparações complexas entre dataframes

- Criação de códigos Python para facilitar a migração de dados entre bancos de dados distintos, garantindo a integridade e consistência dos dados durante todo o processo de transferência.

- Participação ativa em uma significativa migração de dados entre a EstrelaBet e uma empresa parceira, assegurando a transferência segura e precisa dos dados entre as duas organizações.

- Implementação de pipelines de processamento de dados na infraestrutura de nuvem da AWS, utilizando serviços como AWS Glue, Athena e S3 para executar transformações e limpezas de dados em larga escala, garantindo a eficiência e confiabilidade do sistema.

Meu trabalho em engenharia de dados na EstrelaBet demonstra minha capacidade de projetar e implementar soluções robustas que garantem a qualidade e integridade dos dados, facilitando análises precisas e decisões estratégicas fundamentadas.

# Migração
Decidi criar um tópico específico para minha experiência na migração de banco de dados na EstrelaBet

Durante minha atuação na EstrelaBet, liderei o desenvolvimento e implementação de uma pipeline de extração e tratamento de dados altamente eficiente, que desempenhou um papel crucial na integridade e qualidade dos dados utilizados para análises e tomadas de decisão estratégicas. Essa pipeline foi construída utilizando uma combinação de tecnologias e serviços de nuvem, incluindo AWS S3, AWS Glue, Athena e DBT.

O processo teve início com a extração de dados do banco de dados Athena, onde os dados brutos foram obtidos e armazenados em um bucket S3 dedicado, garantindo um armazenamento seguro e escalável. Em seguida, utilizei os recursos poderosos do AWS Glue para realizar transformações complexas nos dados, garantindo a conformidade com os requisitos específicos do negócio e a limpeza de quaisquer inconsistências ou anomalias nos dados brutos.

Uma vez que os dados foram adequadamente tratados e transformados, utilizei o DBT (Data Build Tool) para criar e gerenciar uma tabela bem estruturada, proporcionando uma base sólida para análises avançadas e geração de relatórios precisos. A implementação cuidadosa dessa pipeline resultou em uma melhoria significativa na eficiência operacional, reduzindo o tempo de processamento e garantindo a integridade dos dados ao longo de todo o ciclo de vida.

Além disso, a configuração cuidadosa da pipeline permitiu a fácil integração com sistemas de análise de dados avançados, fornecendo insights valiosos para as equipes de análise e tomada de decisão da empresa. Esse trabalho demonstrou minha habilidade em projetar e implementar soluções de engenharia de dados robustas e eficazes, que impulsionaram diretamente a capacidade da empresa de utilizar dados como um ativo estratégico para impulsionar o crescimento e o sucesso do negócio.
