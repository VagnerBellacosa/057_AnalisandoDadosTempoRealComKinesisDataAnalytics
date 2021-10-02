# Amazon Kinesis Data Analytics

Obtenha insights práticos de streaming de dados com Apache Flink sem servidor

[Comece a usar o Amazon Kinesis Data Analytics](https://console.aws.amazon.com/kinesisanalytics/home?region=us-east-1#/gettingstarted)

O Amazon Kinesis Data Analytics é a maneira mais fácil de transformar e analisar dados de streaming em tempo real com o Apache Flink. O Apache Flink é uma estrutura e um mecanismo de código aberto para o processamento de streams de dados. O Amazon Kinesis Data Analytics reduz a complexidade de criar, gerenciar e integrar aplicações do Apache Flink com outros serviços da AWS.

O Amazon Kinesis Data Analytics se encarrega de tudo o que é necessário para executar continuamente as aplicações de streaming e dimensionar automaticamente para atender ao volume e à transferência de dados recebidos. Com o Amazon Kinesis Data Analytics, não há servidores a serem gerenciados, nenhuma taxa mínima ou custo de configuração, e você paga apenas pelos recursos que suas aplicações de streaming utilizam.

## Benefícios

### Processamento avançado em tempo real

O Amazon Kinesis Data Analytics oferece funções incorporadas para filtrar, agregar e transformar dados de streaming para análises avançadas. O serviço processa dados de streaming com latências de processamento de menos de 1 segundo, o que permite que você analise e responda a dados recebidos e eventos em tempo real.

### Não há servidores para gerenciar

O Amazon Kinesis Data Analytics tem uma arquitetura sem servidor, ou seja, não há servidores para serem gerenciados. O serviço executa aplicações de streaming sem necessidade de provisionamento ou gerenciamento de qualquer infraestrutura. O Amazon Kinesis Data Analytics aumenta e diminui automaticamente a escala vertical da infraestrutura necessária para processar dados de entrada.

### Pague somente pelo que usar

Com o Amazon Kinesis Data Analytics, você paga somente pelos recursos de processamento usados pela aplicação de streaming. Não há taxas mínimas nem compromissos antecipados.

## Fácil de usar

O Amazon Kinesis Data Analytics permite que você crie de forma rápida e fácil consultas e aplicações de streaming sofisticados em três etapas simples: configure as fontes de dados de streaming, crie as consultas ou aplicações de streaming e configure o destino para dados processados.

### Crie aplicações de streaming avançadas com Apache Flink

O Amazon Kinesis Data Analytics inclui bibliotecas de código aberto e tempos de execução baseados no [Apache Flink](https://flink.apache.org/) que possibilitam a criação de uma aplicação em horas, em vez de meses, usando seu IDE favorito. As bibliotecas extensíveis têm APIs especializadas para diferentes [casos de uso](https://flink.apache.org/usecases.html#eventDrivenApps), incluindo processamento de eventos com estado, transmissão de ETL e análises em tempo real. Você pode usar as bibliotecas para integração aos serviços da AWS como o [Amazon Managed Streaming for Apache Kafka](https://aws.amazon.com/pt/msk/) (Amazon MSK), Amazon Kinesis Data Streams, Amazon Kinesis Data Firehose, Amazon OpenSearch Service (sucessor do Amazon Elasticsearch Service), Amazon S3, Amazon DynamoDB e muito mais.

### Uso de sua linguagem favorita

O Amazon Kinesis Data Analytics oferece suporte a criação de aplicações em SQL, Java, Scala e Python. Você pode usar essas linguagens para criar facilmente aplicações que realizam junções, agregações em janelas de tempo, filtros e muito mais. Você pode estender as bibliotecas de código aberto e incluir bibliotecas personalizadas com a linguagem de sua preferência. Usando o Amazon Kinesis Data Analytics Studio, você pode criar aplicações interativamente em SQL, Scala e Python usando blocos de anotações do Apache Zeppelin. 

### Comece rapidamente a usar o Amazon Kinesis Data Analytics Studio

Com o Amazon Kinesis Data Analytics Studio, você pode consultar streams de dados interativamente e desenvolver aplicações de processamento de stream usando um ambiente de desenvolvimento interativo desenvolvido por blocos de anotações do [Apache Zeppelin](https://zeppelin.apache.org/). Com o Amazon Kinesis Data Analytics Studio, o processamento de dados de streaming é desenvolvido pelo Apache Flink. 

### Criação de aplicações de streaming com o Apache Beam

O Amazon Kinesis Data Analytics é compatível com a execução de aplicações de streaming criadas por meio do Java SDK do Apache Beam em um ambiente sem servidor do Apache Flink. O [Apache Beam](https://beam.apache.org/) é um modelo unificado de código aberto para definir aplicações de streaming e processamento de dados em lote que podem ser executadas em vários mecanismos de execução. Você pode criar facilmente aplicações de streaming do Apache Beam em Java e executá-las no Amazon Kinesis Data Analytics e outros mecanismos de execução.

## Como funciona

![Como funciona o Amazon Kinesis Data Analytics](https://d1.awsstatic.com/architecture-diagrams/Product-Page-Diagram_Kinesis-Data-Analytics-How-it-Works%402x-updated.7340988926f37d36097e2f9099483e7e67692deb.png)

## Casos de uso

### Streaming ETL

Você pode desenvolver aplicações de extração-transformação-carga (ETL) de transmissão com operadores integrados do Amazon Kinesis Data Analytics para transformar, agregar e filtrar dados em transmissão. É possível enviar seus dados de forma fácil, em segundos, para o Amazon Kinesis Data Streams, Amazon Managed Streaming for Apache Kafka (Amazon MSK), Amazon OpenSearch Service, Amazon S3, integrações personalizadas e muito mais usando conectores integrados.

Experimente o Streaming ETL com Apache Flink e o Amazon Kinesis Data Analytics usando o [código de exemplo no GitHub](https://github.com/aws-samples/amazon-kinesis-analytics-streaming-etl).

### Análises em tempo real

Você pode consultar e analisar interativamente os streams de dados em tempo real e produzir continuamente insights e resultados para casos de uso sensíveis ao tempo, como análises de streams de cliques. 

Verifique nossos resumos de solução de análise em tempo real sobre [monitoramento de log](https://aws.amazon.com/pt/solutions/implementations/real-time-insights-account-activity/) e [análise da Web](https://aws.amazon.com/pt/solutions/implementations/real-time-web-analytics-with-kinesis/).

### Processamento de evento com estado

Você pode desenvolver aplicações que processam eventos de um ou mais fluxos de dados e acionar processamento condicional e ações externas. É possível identificar padrões como detecção de anomalias em seus streams de dados usando bibliotecas do Apache Flink e SQL padrão para processamento de eventos complexos.

Verifique como [enriquecer seus stream de dados](https://aws.amazon.com/blogs/big-data/enrich-your-data-stream-asynchronously-using-amazon-kinesis-data-analytics-for-apache-flink/) usando o Amazon Kinesis Data Analytics.