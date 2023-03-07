# Chat-Serverless AWS Cloud
AWS: Amazon Web Services

Serverless:Serverless é um modelo de desenvolvimento nativo em nuvem para criação e execução de aplicações sem o gerenciamento de servidores.

Beneficions: 
- Agilidade
- Praticidade

Ambiente:
Node 17.7.1
_________________________________________________________
Principais Serviços de Computação da AWS:

EC2 - 'maquina virtual na nuvem'
EC2 Auto Scaling:  - 'escala o EC2'
Elastic Load Balance: 'balanceador de carga da AWS'
Elastic Container Service -  'subir os container na nuvem'
Elastic Kubernetes Services
AWS Lambda: 'só existe enquanto processa dados', sobe somente o código.


Principais Serviços de Storage:
Block Storage: como se fosse um HD na nuvem
S3: como se fosse um Drive
S3 Glacier: armazenamento a longo prazo


Database:
RDS: banco relacional (roda em maquina virtual)
DynamoDB: no-SQL
ElastiCache:  armazenamento e consultas rapidas, parecido com REDIS.


NetWork:

Amazon VPC: virtual prive cloud.
Security Groups: Fireal
Network Acess Control Lists (NACL): gerenciamento de redes e sub-redes
Amazon Route 53: configuração de rotas.


Segurança na AWS:
- existe muitos recursos.

No projeto sera usado o AWS IAM.
IAM: quem pode acessar determinada coisa.


IAM Users: representam uma pessoa ou serviço para interagir com recursos da AWS.
IAM Users Groups: reunem usuarios com permissões compartilhadas. Usuários podem pertencer a nenhum ou multiplos grupos.