# internet-speedtest-docker

**Alunos:** Augusto Tumelero Mesquita e Michel Borille <br/>
**Professor:** Fernando Posser <br/>
**Disciplina:** Sistemas Operacionais

__**Speedtest**__

O Speedtest é uma aplicação para monitorar em tempo real a velocidade de download, upload e ping da conexão de internet. A aplicação por meio do Docker Compose executa três containers principais:
<ul>
  <li>InfluxDB: Um banco de dados utilizado para dados coletados em espaços de tempo</li>
  <li>Grafana: Ferramenta para criar gráficos e dashboards</li>
  <li>SpeedTest: Uma ferramenta desenvolvida em Python que testa a internet e armazena os resultados no InfluxDB</li>
</ul>

## Executando o container
O único requerimento é ter o Docker Compose instalado e rodas os seguintes comandos:

```console
$ git clone https://github.com/Augusto55/internet-speedtest-docker.git
$ cd internet-speedtest-docker

$ docker-compose up -d 
```




Repositórios utilizados
---------------------------------

* [influxdb](https://hub.docker.com/_/influxdb/) 
* [Grafana](https://hub.docker.com/r/grafana/grafana/)
* [SpeedTest](https://github.com/sivel/speedtest-cli/)
* [SpeedTest Docker Compose (Repositório original)](https://github.com/pedrocesar-ti/internet-speedtest-docker)

Autor do repositório original: [pedrocesar-ti](https://github.com/pedrocesar-ti)



