# Spring Boot e Observabilidade 

### Objetivo

Após participar do curso FullCycle da Code Education, resolvi criar esse projeto para pôr em prática os conhecimentos adquiridos durante o módulo de Observabilidade.

Esse módulo teve como objetivo, demonstrar como coletar métricas de uma aplicação cliente utilizando a biblioteca Prometheus e como exibir essas métricas utilizando o Grafana.

Além disso, foi demonstrado como integrar aplicações clientes com as ferramentas da Elastic Stack. 
A ideia consistiu em utilizar agentes que auxiliaram no processo de coleta de métricas dessa aplicação, por exemplo, uso de memória, uso de cpu, se a aplicação está ativa, etc.
Os agentes a serem utilizados são: Filebeat, HeartBeat e o APM Agent
Esses dados serão enviados ao Elasticsearch e poderemos utilizar o Kibana para acompanhar essas métricas através de painéis.


### Links das documentações oficiais

Elastic Stack: https://www.elastic.co/pt/what-is/elk-stack
<br>Familia de agente Beats: https://www.elastic.co/pt/beats/
<br>Elastic APM: https://www.elastic.co/pt/apm/
<br>Prometheus: https://prometheus.io/
<br>Grafana: https://grafana.com/