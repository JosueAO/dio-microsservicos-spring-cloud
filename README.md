## Projeto de arquitetura de software baseada em microsserviços
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" />  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" /> <img src="https://img.shields.io/badge/redis-%23DD0031.svg?&style=for-the-badge&logo=redis&logoColor=white" /> <img src="https://img.shields.io/badge/Elastic_Search-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" />

### Representação do modelo:

<p align="center"><img src="./img/Captura de tela de 2021-09-09 17-21-52.png" width="500"></p>

### Alguns passos básico sobre o comado ```http``` no terminal:

<p align="center"><img src="./img/passos1.png" width="400"></p>

### Esses passos são recomendados antes de testar o projeto:

```docker run -d --name elasticsearch -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" elasticsearch:6.6.2```

### Na pasta, ```Util``` existe um arquivo ```docker-compose.yml``` para também facilitar o ```Redis```: