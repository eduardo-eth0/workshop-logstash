# Workshop Logstash


## Introdução

O ***Logstash*** é uma ferramenta de coleta e tratamendo de dados, com recursos em tempo real funcionando como um pipline.

A principal função do ***Logstash*** é unificar dados de diferentes fontes dinamicamente, normalizar eles em um ou vários destinos da sua escolha.

Com o ***Logstash*** você vai conseguir integrar seus dados de forma que eles fiquem visiveis por toda organização, sendo desde de dados de analise de negócio até uma analise mais aprofundada dos seus sistemas por exemplo. 

Muita das pessoas conheceram o ***Logstash*** como um grande coletor de logs, mas seus recursos vão muito além disso, qualquer tipo de evento pode ser enriquecido e transformado, graças a sua grande variedade de plugins de ***Input***, ***Filter*** e ***Output***.

Hoje o ***Logstash*** conta com vários codecs nativos que também facilitam muito a ingestão e o processo de tratamento dos dados.

## Com grandes poderes vem grandes responsabildiades

Você precisa processar muitos dados? Seus ***Logtash*** não ta dando mais conta? Basta adicionar mais nós horizontalmente e você já terá toda a sua capacidade de processamento melhorada, e um outro ponto extremamente importante que se faz necessário lembrar e que ele tem uma forte integração com ***Elasticsearch*** e ***Kibana***.

![](https://www.elastic.co/guide/en/logstash/current/static/images/logstash.png)

Além de tudo isso tem uma arquitetura completamente conectável! Com ***Logstash*** você será capaz de inserir dados de ***qualquer*** fonte, digerir eles e salvar também em qualquer fonte.

Isso se torna ainda mais poderoso devido ao seu grande ecossistema de plugins e ainda a capacidade de você conseguir desenvolver o seu proprio plugin!

Hoje existem mais de 200 plugins disponiveis.

##Algumas aplicações

###Logs e métricas

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



