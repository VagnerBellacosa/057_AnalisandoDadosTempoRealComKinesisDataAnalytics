# Apache Flink

[PDF](https://docs.aws.amazon.com/pt_br/emr/latest/ReleaseGuide/emr-release.pdf#emr-flink)

[RSS](https://docs.aws.amazon.com/pt_br/emr/latest/ReleaseGuide/amazon-emr-release-notes.rss)



O [Apache Flink](https://flink.apache.org/) é um mecanismo de fluxo de dados de streaming que você pode usar para executar o processamento de streaming em tempo real em fontes de dados de alto throughput. O Flink é compatível com semântica do horário do evento para eventos fora de ordem, semântica exatamente uma vez, controle de pressão contrária e APIs otimizadas para criar aplicativos de streaming e de lote.

Além disso, o Flink tem conectores para fontes de dados de terceiros, como o seguinte:

- [Amazon Kinesis Data Streams](https://ci.apache.org/projects/flink/flink-docs-master/apis/streaming/connectors/kinesis.html)
- [Apache Kafka](https://ci.apache.org/projects/flink/flink-docs-master/apis/streaming/connectors/kafka.html)
- [Conector Flink](https://ci.apache.org/projects/flink/flink-docs-master/apis/streaming/connectors/elasticsearch2.html)
- [API de streaming do Twitter](https://ci.apache.org/projects/flink/flink-docs-release-1.2/dev/connectors/twitter.html)
- [Cassandra](https://ci.apache.org/projects/flink/flink-docs-master/apis/streaming/connectors/cassandra.html)

O Amazon EMR oferece suporte ao Flink como um aplicativo do YARN, para que você possa gerenciar recursos juntamente com outros aplicativos dentro de um cluster. O Flink no YARN permite que você envie trabalhos do Flink transitórios ou você pode criar um cluster de execução prolongada que aceite vários trabalhos e aloque recursos de acordo com a reserva geral do YARN.

O Flink é incluído no Amazon EMR versão 5.1.0 e versões posteriores.

**nota**

Support para o`FlinkKinesisConsumer`A classe do foi adicionada no Amazon EMR versão 5.2.1.

A tabela a seguir lista a versão do Flink incluída na versão mais recente do Amazon EMR série 6.x, além dos componentes que o Amazon EMR instala com o Flink.

Para obter a versão dos componentes instalados com o Flink nesta versão, consulte[Versões de componentes da versão 6.4.0](https://docs.aws.amazon.com/pt_br/emr/latest/ReleaseGuide/emr-640-release.html).

| Informações de versão do Flink para o emr-6.4.0 |                 |                                                              |
| :---------------------------------------------- | :-------------- | :----------------------------------------------------------- |
| Label de apresentação do Amazon EMR             | Versão do Flink | Componentes instalados com o Flink                           |
| emr-6.4.0                                       | Flink 1.13.1    | emrfs, hadoop-client, hadoop-mapred, hadoop-hdfs-datanode, hadoop-hdfs-library, hadoop-hdfs-namenode, hadoop-httpfs-server, hadoop-kms-server, hadoop-yarn-nodemanager, hadoop-yarn-resourcemanager, hadoop-yarn-timeline-server, flink-client, flink-jobmanager-config, hudi |

A tabela a seguir lista a versão do Flink incluída na versão mais recente do Amazon EMR série 5.x, além dos componentes que o Amazon EMR instala com o Flink.

Para obter a versão dos componentes instalados com o Flink nesta versão, consulte[Versões de componentes da versão 5.33.0](https://docs.aws.amazon.com/pt_br/emr/latest/ReleaseGuide/emr-5330-release.html).

| Informações de versão do Flink para o emr-5.33.0 |                 |                                                              |
| :----------------------------------------------- | :-------------- | :----------------------------------------------------------- |
| Label de apresentação do Amazon EMR              | Versão do Flink | Componentes instalados com o Flink                           |
| emr-5.33.0                                       | Flink 1.12.1    | emrfs, hadoop-client, hadoop-mapred, hadoop-hdfs-datanode, hadoop-hdfs-library, hadoop-hdfs-namenode, hadoop-httpfs-server, hadoop-kms-server, hadoop-yarn-nodemanager, hadoop-yarn-resourcemanager, hadoop-yarn-timeline-server, flink-client, flink-jobmanager-config |

**Tópicos**

- [Criação de um cluster com o Flink](https://docs.aws.amazon.com/pt_br/emr/latest/ReleaseGuide/flink-create-cluster.html)
- [Configuração do Flink](https://docs.aws.amazon.com/pt_br/emr/latest/ReleaseGuide/flink-configure.html)
- [Trabalhando com trabalhos do Flink no Amazon EMR](https://docs.aws.amazon.com/pt_br/emr/latest/ReleaseGuide/flink-jobs.html)
- [Uso do shell Scala](https://docs.aws.amazon.com/pt_br/emr/latest/ReleaseGuide/flink-scala.html)
- [Localização da interface da web do Flink](https://docs.aws.amazon.com/pt_br/emr/latest/ReleaseGuide/flink-web-interface.html)
- [Histórico de apresentação do Flink](https://docs.aws.amazon.com/pt_br/emr/latest/ReleaseGuide/Flink-release-history.html)



[Fornecer feedback](https://docs.aws.amazon.com/forms/aws-doc-feedback?hidden_service_name=EMR&topic_url=http://docs.aws.amazon.com/pt_br/emr/latest/ReleaseGuide/emr-flink.html)

**Tópico anterior:** [Criptografia no lado do cliente do Amazon S3](https://docs.aws.amazon.com/pt_br/emr/latest/ReleaseGuide/emr-emrfs-encryption-cse.html)

**Próximo tópico:** [Criação de um cluster com o Flink](https://docs.aws.amazon.com/pt_br/emr/latest/ReleaseGuide/flink-create-cluster.html)