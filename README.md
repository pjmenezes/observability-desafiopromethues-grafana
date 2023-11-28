# Desafio Observabilidade

Criando um ambiente de observabilidade usando Prometheus e Grafana para monitorar uma aplicação de exemplo.

## Technologies Utilizaddas:

* Linux 
* Python Application
* Prometheus
* Grafana
* Slack API - Incoming Webhooks


## 

- No caminho ``/python/app.py`` rodei o comando: ``python3 app.py`` 

![Alt text](/observability-lab/img/01.png?raw=true)

- Em outra janela no termianl ``docker compose up -d``

![Alt text](/observability-lab/img/02.png?raw=true)

- Conferir se os container foram criados ``docker container ls``  ou  ``docker ps``

![Alt text](/observability-lab/img/03.png?raw=true)

- Acessando o Promethues e verificando as métricas da aplicação
![Alt text](/observability-lab/img/0000.png?raw=true)

- Acessando o Garana 

![Alt text](/observability-lab/img/04.png?raw=true)

Adicionnei um ``DATA SOURCE`` tipo ``PROMETHEUS``

![Alt text](/observability-lab/img/05.png?raw=true)

Atribuir um nome, adicionei conexão com URL do promethues

![Alt text](/observability-lab/img/06.png?raw=true)

por fim...cliquei em ``Salvar e testar``

![Alt text](/observability-lab/img/07.png?raw=true)

- Criei um Painel no Grafana para monitoria minha aplicação python

![Alt text](/observability-lab/img/08.png?raw=true)

- Enviando notificação no canl Slack
![Alt text](/observability-lab/img/alerta.png?raw=true)





