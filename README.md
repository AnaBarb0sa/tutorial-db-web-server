# tutorial-db-web-server
Atividade: Elaboração de aplicação web integrada a um banco de dados

## Objetivo
O projeto tem como objetivo a criação de um web server utilizando EC2 (Elastic Compute Cloud) e RDS (Relational Database Service) da AWS.

**EC2:**
Responsável por hospedar o servidor web. 
- Amazon Linux;
- Os grupos de segurança estão configurados para permitir o tráfego HTTP/HTTPS e a comunicação entre o EC2 e o RDS.
  
**RDS:**
Está armazenando os dados da aplicação web.
- PostgreSQL.

Esse repositório contém:
- pasta 'dba': contém o código de configuração do banco de dados (RDS) para conexão com a EC2;
- pasta 'page': contém o código html/php criado, bem como a conexão entre o frontend e backend;
- pasta 'video': contém o vídeo mostrando as instâncias e o código funcionando.
