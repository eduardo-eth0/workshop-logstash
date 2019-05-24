# Workshop Logstash
![](./images/logstash_logo.png)

## Introdução

O ***Logstash*** é uma ferramenta de coleta e tratamendo de dados, com recursos em tempo real funcionando como um pipline.

A principal função do ***Logstash*** é unificar dados de diferentes fontes dinamicamente, normalizar eles em um ou vários destinos da sua escolha.

Com o ***Logstash*** você vai conseguir integrar seus dados de forma que eles fiquem visiveis por toda organização, sendo desde de dados de analise de negócio até uma analise mais aprofundada dos seus sistemas por exemplo. 

Muita das pessoas conheceram o ***Logstash*** como um grande coletor de logs, mas seus recursos vão muito além disso, qualquer tipo de evento pode ser enriquecido e transformado, graças a sua grande variedade de plugins de ***Input***, ***Filter*** e ***Output***.

Hoje o ***Logstash*** conta com vários codecs nativos que também facilitam muito a ingestão e o processo de tratamento dos dados.

## Com grandes poderes vem grandes responsabildiades

Você precisa processar muitos dados? Seus ***Logtash*** não ta dando mais conta? Basta adicionar mais nós horizontalmente e você já terá toda a sua capacidade de processamento melhorada, e um outro ponto extremamente importante que se faz necessário lembrar e que ele tem uma forte integração com ***Elasticsearch*** e ***Kibana***.

![](./images/logstash_overview.png)

Além de tudo isso tem uma arquitetura completamente conectável! Com ***Logstash*** você será capaz de inserir dados de ***qualquer*** fonte, digerir eles e salvar também em qualquer fonte.

Isso se torna ainda mais poderoso devido ao seu grande ecossistema de plugins e ainda a capacidade de você conseguir desenvolver o seu proprio plugin!

Hoje existem mais de 200 plugins disponiveis.

## Algumas aplicações

### Logs e métricas

Capturando logs, você tera a possibilidade de capturar logs como:


- Web
- Logs de aplicação
- log4j 
- syslog
- rede
- firewall


e ainda existe a possibildiade de você fazer um socket tcp ou udp para receber e enviar dados para possiveis pontos não cobertos por plugin! 

### Web

Outro ponto possível também com o ***Logstash*** é transformar suas requisições HTTP em eventos, com isso podemos consumir serviços como:

- Twitter 
- Webhooks (github, JIRA)
- Consultar endpoints especificos

Consumindo endpoints http, podemos ainda mais crescer nossa capacidade de coletar eventos de diversas partes do nosso ecossistema.

## Datastore e streams

Essa é uma outra maneira de você conseguir dar muito mais valor aos seus dados que você tem guardado ou que são enviados via stream, exemplos:

- Coletar dados de uma base de dados relacional
- Kafka
- RabbitMQ
- SQS

### Sensores de IoT

Use o ***Logstash*** para centralizar informações de vários sensores IoT, capture dados de sensores e enriqueça esses dados para posterior analise.

Ter um grande backbone de ingestão de dados para redes de IoT é uma otima abordagem e o ***Logstash*** vai ajudar muito nisso, podendo ser o grande centralizador dessas comunicações.

## Aproveite para enriquecer tudo

Quando melhor for seus dados melhor vai ser o seu conhecimento sobre seu negócio e não importa que tipo de dado ou negócio seja.

Fazer o trabalho de limpar e transformar sua informação durante o processo de ingestão vai te trazer um ganho imediado de possiveis insights durante o processo de filtro ou até mesmo o processo de output.

O ***Logstash*** já vem com várias possibilidades já prontas, desde agregadores, modificadores, marcadores geograficos e muitos outras possibildiades já disponivies para que você use assim que acabe a instalacão.

Existem filtros como o **Grok** que vai te possibiltar encontrar padrões de uma forma mais simplificada que o uso de expressões regulares puras, outro ponto que pode te ajudar a ter uma visão melhor são as coordenads geograficas, que podem te ajudar a ter uma ideia espacial da sua informação.

Existem também filtros já prontos para arquivos do tipo CSV, facilitando a leitura desse tipo de arquivo, outro ponto importante também é a capacidade de anonimizar dados sensiveis.

Outro ponto bem importante são os codecs que nos ajudam a processar saidas do tipo JSON ou até mesmo multiline.

## Alguns exemplos do que temos dentro do Logstash

### Analise
- 	Elasticsearch
- 	MongoDB

### Arquivamento
- S3
- HDFS

### Monitoramento
- Nagios
- Ganglia
- Zabbix
- Graphite
- Datadog
- Cloudwatch

### Alerta
- Email
- IRC
- SNS
- Pagerduty

## Bora começar isso?

### Instalando o Logstash
`O Logstash necessita do Java 8 ou 11 para funcionar podendo ser tanto a versão da oracle quando OpenJDK`

Para verificar a sua versão do java use o comando:

```
java -version
```

Você deve obter uma saida parecida com essa:

```
openjdk version "11.0.3" 2019-04-16
OpenJDK Runtime Environment (build 11.0.3+7-Ubuntu-1ubuntu219.04.1) 
OpenJDK 64-Bit Server VM (build 11.0.3+7-Ubuntu-1ubuntu219.04.1, mixed mode, sharing)
```

