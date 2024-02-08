# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 07/02/2024
Empresa: Abstergo Industries 
Responsável: Rogério Marcondes

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo, realizado por Rogério Marcondes. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- DynamoDB Accelerator (DAX)
- Banco de Dados não relacional
- Registro das compras e estoque
Ferramenta escolhida para criar um banco de dados para registro dos medicamentos, tendo como atributos número de identificação do medicamento, nome, descrição, lote, validade e quantidade disponivel, e também a criação de um banco de dados para registro das compras, assim melhorando a administração do estoque e ter acesso fácil ao registro de compras, sendo o acesso á estes bancos extremamente veloz, por possuir um cache para requisições frequentes.

Etapa 2: 
- Amazon Lambda
- Programação em nuvem
- Criação de código para acesso, alteração e deleção para o banco de dados

Etapa 3: 
- Amazon Virtual Private Cloud
- Criação de rede em nuvem
- Rede privada para proteção de dados



## Conclusão
A implementação de ferramentas na empresa Abstergo tem como esperado, melhorar a administração do estoque e registro de compras, criando um banco de dados para registro dos medicamentos, tendo como atributos número de identificação do medicamento, nome, descrição, lote, validade e quantidade disponivel, e também a criação de um banco de dados para registro das compras, assim melhorando a administração do estoque e ter acesso fácil ao registro de compras, sendo o acesso á estes bancos extremamente veloz, por possuir um cache para requisições frequente. Criar também, códigos de requisição que acessaram estes bancos de dados, que serão implementados em um software para ter uma administração mais intuitiva, além de também criar uma rede privada para proteger estes bancos de dados. Todas estas implementações irão aumentar a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- Documentação Amazom DynamoDB
https://docs.aws.amazon.com/dynamodb/
- Documentação Amazon Lambda
https://docs.aws.amazon.com/pt_br/lambda/
- Documentação Amazon Virtual Private Cloud
https://docs.aws.amazon.com/pt_br/vpc/

Assinatura do Responsável pelo Projeto:

Rogério Gomes Marcondes