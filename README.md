# aws-vpc-ec2-webserver
# Projeto AWS – VPC e Servidor Web

Criação de uma infraestrutura completa na AWS utilizando VPC, sub-redes públicas e privadas, tabelas de rotas e Internet Gateway.

## Etapas realizadas

* Criação de VPC personalizada
* Configuração de sub-redes públicas e privadas
* Associação de tabelas de rotas
* Criação de Security Group com liberação de HTTP
* Provisionamento de instância EC2
* Configuração de servidor web (Apache)

## Tecnologias utilizadas

* AWS VPC
* AWS EC2
* Amazon Linux 2023
* Apache

## Objetivo

Simular um ambiente de infraestrutura em nuvem com acesso público a uma aplicação web.

## Observação

Projeto desenvolvido em ambiente de laboratório com evidências registradas por capturas de tela.

## Evidências

### VPC criada
![VPC](./vpc-overview.png)

### Subnets públicas
![Public Subnet 1](./public-subnet-1.png.png)
![Public Subnet 2](./public-subnet-2.png.png)

### Subnets privadas
![Private Subnet 1](./private-subnet-1.png.png)
![Private Subnet 2](./private-subnet-2.png.png)

### Tabelas de rotas
![Public Route Table](./public-route-table.png.png)
![Private Route Table](./private-route-table.png.png)

### Security Group (HTTP liberado)
![Security Group](./security-group-http.png.png)

### Instância EC2 rodando
![EC2](./ec2-instance-running.png.png)

### Servidor web funcionando
![Web Server](./web-server-running.png.png)
