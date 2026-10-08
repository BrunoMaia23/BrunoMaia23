# Bruno Maia

Engenheiro de dados. Trabalho com dados de direitos autorais de música: arquivos que chegam de
parceiros em layouts antigos, cadastro de obras e fonogramas, replicação entre bancos e os relatórios
que saem disso. No dia a dia uso Python e SQL (Oracle e PostgreSQL) com Airflow e, conforme o projeto,
Spark, Kafka com Debezium, AWS e Power BI.

Os repositórios abaixo são versões, escritas do zero e com dados inventados, de problemas que resolvi
ou ajudei a resolver no trabalho. Nenhum tem código ou dado da empresa, e o README de cada um conta de
onde o problema veio.

*Data engineer. The repositories below are from-scratch versions of problems from my job, built with
made-up data. The READMEs are in Portuguese.*

- [ddex-medallion-pipeline](https://github.com/BrunoMaia23/ddex-medallion-pipeline): XML DDEX em
  camadas com Spark e Iceberg, conferido célula a célula contra o sistema antigo
- [cdc-kafka-postgres](https://github.com/BrunoMaia23/cdc-kafka-postgres): replicação contínua com
  Debezium e Kafka; o consumidor grava o offset no banco de destino, na mesma transação dos dados
- [powerbi-pdf-completo](https://github.com/BrunoMaia23/powerbi-pdf-completo): o PDF completo de um
  relatório do Power BI, por um relatório paginado aberto por URL
- [matching-de-obras](https://github.com/BrunoMaia23/matching-de-obras): casamento das obras enviadas
  por um parceiro com o catálogo, com nota explicável e revisão dos casos duvidosos
- [importador-ficha-tecnica](https://github.com/BrunoMaia23/importador-ficha-tecnica): ficha técnica
  em Excel para o banco, com contrato JSON e uma transação por ficha
- [arquivo-posicional](https://github.com/BrunoMaia23/arquivo-posicional): arquivo de largura fixa
  para o banco, com layout declarativo e aplicação por diferença
- [fila-para-api](https://github.com/BrunoMaia23/fila-para-api): repasse de uma fila do banco para uma
  API, sem reenvio e com retomada por etapa
- [recalculo-com-replica](https://github.com/BrunoMaia23/recalculo-com-replica): recálculo que espera
  a réplica bater de verdade antes de somar
- [sync-pastas-s3](https://github.com/BrunoMaia23/sync-pastas-s3): sincronização de pastas com o S3,
  guiada por um YAML por tipo de documento
- [monitor-urls-quebradas](https://github.com/BrunoMaia23/monitor-urls-quebradas): URLs que quebraram
  na migração de um site, ordenadas por tráfego, com sugestão de redirect

De estudo: [vendas-supermercado-databricks](https://github.com/BrunoMaia23/vendas-supermercado-databricks),
um MVP de engenharia de dados da pós-graduação, e
[carga-solr-airflow](https://github.com/BrunoMaia23/carga-solr-airflow), um desafio técnico com
Airflow, Solr e Docker.
