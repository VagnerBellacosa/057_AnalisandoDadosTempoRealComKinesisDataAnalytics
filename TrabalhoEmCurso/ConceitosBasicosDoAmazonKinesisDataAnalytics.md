# Conceitos básicos do Amazon Kinesis Data Analytics

A melhor maneira de começar a usar o Amazon Kinesis Data Analytics é obter experiência prática criando uma aplicação de exemplo. Basta acessar o [console do Amazon Kinesis Data Analytics](https://console.aws.amazon.com/kinesisanalytics/home) e criar uma nova aplicação do Amazon Kinesis Data Analytics. Use as etapas a seguir, dependendo se você escolher (i) uma aplicação do Apache Flink usando um IDE (Java, Scala ou Python) ou uma aplicação do Apache Beam (Java), (ii) aplicação de bloco de anotações do Studio (Apache Flink SQL, Python ou Scala por meio de uma experiência de desenvolvimento interativa), ou (iii) uma aplicação baseada em SQL do Kinesis Data Analytics por meio de um editor de console:

## Você pode criar aplicações de streaming com o Apache Flink e o Apache Beam

Para começar, crie uma aplicação do Kinesis Data Analytics que leia e processe dados de streaming de forma contínua. Baixe as bibliotecas de Apache Flink de código aberto usando sua IDE favorita, escreva seu código da aplicação e teste-o com dados de streaming ao vivo. Você pode configurar os destinos para onde o Kinesis Data Analytics deverá enviar os resultados.

Você pode obter instruções sobre como fazer download das bibliotecas e criar sua primeira aplicação no [Guia do desenvolvedor do Amazon Kinesis Data Analytics para Apache Flink](https://docs.aws.amazon.com/kinesisanalytics/latest/java/what-is.html). Aqui você também encontrará os componentes necessários para executar aplicações que usam o Apache Beam. Você pode encontrar um código equivalente em outras linguagens compatíveis com o Apache Flink na documentação oficial do Apache Flink, para a versão do Apache Flink que você está usando no Amazon Kinesis Data Analytics.

### Etapa 1: Baixe as bibliotecas de código aberto para a sua IDE favorita

![Criar aplicativo Java](https://d1.awsstatic.com/products/kinesis/Analytics/kda-java-create.31e16e59b9261cfbdcacff366beb376c6d9078b7.png)

Você pode começar baixando as bibliotecas de código aberto que incluem o SDK da AWS, o Apache Flink e os conectores dos serviços da AWS. 

### Etapa 2: Crie uma aplicação de teste no Apache Flink ou no Apache Beam

![Amostra de c&oacute;digo Java](https://d1.awsstatic.com/products/kinesis/Analytics/kda-java-code2.dea93d33188def10d5021c43d35d4b268fa1b321.PNG)

Você escreve o código da aplicação Apache Flink usando fluxos de dados e operadores de fluxo. Os fluxos de dados da aplicação são a estrutura de dados que são executadas durante o processamento usando o código da aplicação. Os dados fluem continuamente das fontes para os fluxos de dados da aplicação. Um ou mais operadores de fluxo são usados para definir seu processamento nos fluxos de dados do aplicativo.

### Etapa 3: faça o upload do seu código para o Kinesis Data Analytics

![Configurar aplicativo Java](https://d1.awsstatic.com/products/kinesis/Analytics/kda-java-configure2.9bd765b846cb93fb98deaffe57c6c6d355ff9174.png)

Uma vez definido, faça o upload do seu código para o Amazon Kinesis Data Analytics e o serviço administrará tudo o que é necessário para executar continuamente as aplicações em tempo real, incluindo o dimensionamento automático para corresponder ao volume e à taxa de transferência dos dados recebidos.

### Conceitos básicos do guia do desenvolvedor de Apache Flink

A seção [Getting Started with Amazon Kinesis Data Analytics for Apache Flink Applications](https://docs.aws.amazon.com/kinesisanalytics/latest/java/getting-started.html) do guia do desenvolvedor oferece uma demonstração simples sobre como criar sua primeira aplicação.

### Comece a usar rapidamente com uma solução predefinida

Use a [Solução de dados em streaming da AWS para Amazon Kinesis](https://aws.amazon.com/pt/solutions/implementations/aws-streaming-data-solution-for-amazon-kinesis/) para ajudar a resolver casos de uso de streaming em tempo real, como captura de logs de aplicações de alto volume, análise de dados de sequência de cliques, entrega contínua para um data lake e muito mais.

### Introdução ao Amazon Kinesis Data Analytics usando o Apache Flink

O [vídeo de treinamento de 15 minutos](https://www.aws.training/learningobject/video?id=27167) explica como usar aplicações do Apache Flink no Amazon Kinesis Data Analytics para obter insights oportunos sobre seus dados.

## É fácil começar a usar o Amazon Kinesis Data Analytics Studio.

Para começar, crie uma nova aplicação no Kinesis Data Analytics Studio. Inicie a aplicação e abra o bloco de anotações do Apache Zeppelin e grave o código da aplicação em SQL, Python e Scala, com um mecanismo de processamento de stream desenvolvido pelo Apache Flink. Teste sua aplicação com dados de streaming ao vivo e explore a aparência de seus dados de streaming com consultas SQL e visualização integrada. Você pode configurar os destinos para onde o Kinesis Data Analytics deverá enviar os resultados. Opcionalmente, você pode promover seu código na nota para uma aplicação de streaming do Apache Flink de longa duração com estado durável e autoescalabilidade.

Você pode obter instruções sobre como começar no Guia do desenvolvedor do Amazon Kinesis Data Analytics Studio. Você também encontrará exemplos para experimentar várias consultas SQL e amostras de programas Python e Scala em seus dados de streaming.

### Etapa 1: Criar uma aplicação do Amazon Kinesis Data Analytics

![Criar uma aplica&ccedil;&atilde;o Java](https://d1.awsstatic.com/products/kinesis/Analytics/kinesis-data-analytics-studio-app-step-1.a6d61608f5b15cba722e7fea5f98151affd2169a.png)

Você pode começar no console do Amazon Kinesis Data Analytics, Amazon MSK ou Amazon Kinesis Data Streams. Você também pode usar conectores personalizados para se conectar a qualquer outra fonte de dados.

### Etapa 2: Gravar código no bloco de anotações sem servidor em SQL, Python e Scala e desenvolver aplicações do Apache Flink rapidamente

![C&oacute;digo de exemplo Java](https://d1.awsstatic.com/products/kinesis/Analytics/kinesis-data-analytics-studio-app-step-2.8c9347080600a1315cd6bda7f9960e456e2fb378.png)

Você pode executar parágrafos individuais na anotação, ver os resultados em contexto e usar a visualização integrada do Apache Zeppelin para acelerar o desenvolvimento. Você também pode usar funções definidas pelo usuário em seu código.

### Etapa 3: Criar e implantar como uma aplicação de streaming do Kinesis Data Analytics

![Configurar uma aplica&ccedil;&atilde;o Java](https://d1.awsstatic.com/products/kinesis/Analytics/kinesis-data-analytics-studio-app-step-3.445c88fa937e44ae94d547ae87339a90d5049174.png)

Você pode implantar seu código como uma aplicação de processamento de stream em execução contínua com apenas alguns cliques. Sua aplicação implantada será uma aplicação do Kinesis Data Analytics para Apache Flink com estado durável e autoescalabilidade. Você também terá a oportunidade de alterar fontes, destinos, registros e níveis de monitoramento antes de produzir seu código.

## Comece a usar o Amazon Kinesis Data Analytics SQL

Para começar, crie uma nova aplicação no Amazon Kinesis Data Analytics. Selecione o stream de demonstração que disponibilizamos como entrada, escolha um modelo e edite a consulta SQL. Você poderá ver os resultados no console ou carregá-los no Amazon Elasticsearch Service, como também visualizá-los usando o Kibana. Em alguns minutos, você poderá implantar um aplicativo de dados de streaming completo.

### Etapa 1: configure o stream de entrada

![Configurar o stream de entrada](https://d1.awsstatic.com/products/kinesis/Analytics/thumbnail-kinesis-analytics-source.702600de1796d8a7adea498a94c4031259eb5fe1.png)

Primeiro, acesse o [console do Amazon Kinesis Data Analytics](https://console.aws.amazon.com/kinesisanalytics/home) e selecione um stream de dados do Kinesis ou um stream de entrega do Kinesis Data Firehose como entrada. O Amazon Kinesis Data Analytics consome os dados, reconhece automaticamente formatos de dados padrão e sugere um esquema. Você pode refinar esse esquema ou, se seus dados de entrada não forem estruturados, definir um novo usando nosso editor de esquema intuitivo.

[Ler a documentação ](https://docs.aws.amazon.com/kinesisanalytics/latest/dev/how-it-works.html)

### Etapa 2: escreva suas consultas SQL

![Escrever suas consultas SQL](https://d1.awsstatic.com/products/kinesis/Analytics/thumbnail-kinesis-analytics-editor.0a4f4e56d908357d6cce390b85128fc21a532e04.png)

Em seguida, escreva suas consultas SQL para processar dados usando o editor SQL do Amazon Kinesis Data Analytics e modelos incorporados, e teste-os com dados de streaming em tempo real.

[Ler a documentação ](https://docs.aws.amazon.com/kinesisanalytics/latest/dev/getting-started.html)

### Etapa 3: configure o stream de saída

![Configurar o stream de sa&iacute;da](https://d1.awsstatic.com/products/kinesis/Analytics/thumbnail-kinesis-analytics-destination.6c3a3155577e98b862bf5f368d7418786a15e526.png)

Finalmente, indique os destinos em que você deseja que os resultados sejam carregados. O Amazon Kinesis Data Analytics já vem integrado ao Amazon Kinesis Data Streams e ao Amazon Kinesis Data Firehose. Portanto, é fácil enviar resultados processados para o Amazon S3, o Amazon Redshift, o Amazon Elasticsearch Service ou o seu próprio destino personalizado.

[Ler a documentação ](https://docs.aws.amazon.com/kinesisanalytics/latest/dev/examples.html)

## Exemplos de conceitos básicos

Esses recursos oferecem exemplos de aplicativos de dados de streaming e instruções detalhadas para que você possa experimentar e adquirir experiência prática.

### Como funciona

Este [Guia do desenvolvedor de SQL](https://docs.aws.amazon.com/kinesisanalytics/latest/dev/how-it-works.html) oferece uma visão geral da arquitetura, da criação de aplicações e da configuração de entradas e saídas do Amazon Kinesis Data Analytics.

### Conceitos básicos

No [guia de conceitos básicos](https://docs.aws.amazon.com/kinesisanalytics/latest/dev/getting-started.html), mostramos em detalhes como configurar uma conta da AWS, a Interface da Linha de Comando (ILC da AWS) e a criação do seu primeiro aplicativo do Amazon Kinesis Data Analytics.

### Aplicativos de exemplo

Este [guia de aplicativos de exemplo](https://docs.aws.amazon.com/kinesisanalytics/latest/dev/examples.html) oferece exemplos de código e instruções detalhadas para ajudar a criar aplicativos do Amazon Kinesis Data Analytics e testar resultados.

## Vídeos de instruções

É fácil começar a usar o Kinesis Data Analytics. Os vídeos de instruções facilitam ainda mais o seu trabalho ao disponibilizar análises aprofundadas sobre casos de uso comuns e fluxos de trabalho de processamento de stream. Eles também oferecem uma visão geral detalhada sobre os recursos fundamentais para que você possa fazer o seu trabalho. Siga os links abaixo para assistir às gravações:

<iframe id="lb-video-0_Youtube_api" class="vjs-tech" sandbox="allow-scripts allow-same-origin allow-presentation allow-popups" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" frameborder="0" allowfullscreen="1" title="YouTube video player" width="640" height="360" src="https://www.youtube-nocookie.com/embed/2dNixWqL6dY?controls=0&amp;modestbranding=1&amp;rel=0&amp;showinfo=0&amp;loop=0&amp;fs=0&amp;hl=pt&amp;enablejsapi=1&amp;origin=https%3A%2F%2Faws.amazon.com&amp;widgetid=1" style="box-sizing: inherit; width: 197.5px; height: 111.094px; position: absolute; top: 0px; left: 0px; opacity: 1; transition: all 0.2s ease-in-out 0s;"></iframe>



Introduction to Amazon Kinesis Data Analytics (2:21)

<iframe id="lb-video-1_Youtube_api" class="vjs-tech" sandbox="allow-scripts allow-same-origin allow-presentation allow-popups" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" frameborder="0" allowfullscreen="1" title="YouTube video player" width="640" height="360" src="https://www.youtube-nocookie.com/embed/0Z5VnCWiBCA?controls=0&amp;modestbranding=1&amp;rel=0&amp;showinfo=0&amp;loop=0&amp;fs=0&amp;hl=pt&amp;enablejsapi=1&amp;origin=https%3A%2F%2Faws.amazon.com&amp;widgetid=2" style="box-sizing: inherit; width: 197.5px; height: 111.094px; position: absolute; top: 0px; left: 0px; opacity: 1; transition: all 0.2s ease-in-out 0s;"></iframe>



Feed real-time dashboards (3:14)

<iframe id="lb-video-2_Youtube_api" class="vjs-tech" sandbox="allow-scripts allow-same-origin allow-presentation allow-popups" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" frameborder="0" allowfullscreen="1" title="YouTube video player" width="640" height="360" src="https://www.youtube-nocookie.com/embed/C-Em7ZM2X9k?controls=0&amp;modestbranding=1&amp;rel=0&amp;showinfo=0&amp;loop=0&amp;fs=0&amp;hl=pt&amp;enablejsapi=1&amp;origin=https%3A%2F%2Faws.amazon.com&amp;widgetid=3" style="box-sizing: inherit; width: 197.5px; height: 111.094px; position: absolute; top: 0px; left: 0px; opacity: 1; transition: all 0.2s ease-in-out 0s;"></iframe>



Create real-time alarms (2:59)

<iframe id="lb-video-3_Youtube_api" class="vjs-tech" sandbox="allow-scripts allow-same-origin allow-presentation allow-popups" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" frameborder="0" allowfullscreen="1" title="YouTube video player" width="640" height="360" src="https://www.youtube-nocookie.com/embed/fhebe7AflTI?controls=0&amp;modestbranding=1&amp;rel=0&amp;showinfo=0&amp;loop=0&amp;fs=0&amp;hl=pt&amp;enablejsapi=1&amp;origin=https%3A%2F%2Faws.amazon.com&amp;widgetid=4" style="box-sizing: inherit; width: 197.5px; height: 111.094px; position: absolute; top: 0px; left: 0px; opacity: 1; transition: all 0.2s ease-in-out 0s;"></iframe>



Generating time series analytics (2:32)

## Comece a usar o Amazon Kinesis Data Analytics

![Cadastre-se para obter uma conta da AWS](https://d1.awsstatic.com/webteam/product-pages/Product-Page_Standard-Icons_02_Sign-Up_SqInk.f43d5ddc9c43883eec6187f34c68155402b13312.png)

Cadastre-se para obter uma conta da AWS

Obtenha acesso instantâneo ao [nível gratuito da AWS](https://aws.amazon.com/free).

![Consulte o guia de conceitos b&aacute;sicos](https://d1.awsstatic.com/webteam/product-pages/Next-Steps-Icon_User-guide.24c016304c2e2b01024d8f0a103ba4f61c1e6fc9.png)

Consulte o guia de conceitos básicos

Saiba como usar o Amazon Kinesis Data Analytics no guia passo a passo para [SQL](https://docs.aws.amazon.com/kinesisanalytics/latest/dev/getting-started.html) ou [Apache Flink](https://docs.aws.amazon.com/kinesisanalytics/latest/java/getting-started.html).

![Comece a criar no console](https://d1.awsstatic.com/webteam/product-pages/Product-Page_Standard-Icons_03_Start-Building_SqInk.6a1ef4429a6604cda9b0857084aa13e2ee4eebca.png)

Comece a criar aplicativos de streaming

Crie sua primeira aplicação de streaming no [console](https://console.aws.amazon.com/kinesisanalytics/home) do Amazon Kinesis Data Analytics.