# 💊 Plataforma de Farmácia Virtual - AWS

Projeto de arquitetura de nuvem para uma farmácia online, focado em alta disponibilidade e segurança, desenvolvido para o desafio da DIO.

## 🛠️ Arquitetura e Tecnologias
A solução utiliza uma abordagem **Serverless** para otimização de custos:

* **Hospedagem:** Amazon S3 (Frontend) e CloudFront (Distribuição).
* **Autenticação:** Amazon Cognito (Login de clientes).
* **API:** Amazon API Gateway.
* **Processamento:** AWS Lambda (Backend em Node.js ou Python).
* **Banco de Dados:** Amazon DynamoDB (Catálogo de produtos e pedidos).
* **Notificações:** Amazon SNS (Avisos de entrega e promoções).

## 📐 Estrutura do Projeto
- `/docs`: Documentação da arquitetura.
- `/src`: (Opcional) Código fonte ou definições de infraestrutura.
