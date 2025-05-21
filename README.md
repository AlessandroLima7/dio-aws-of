# dio-aws-of
Projeto feito para atender atividade da plataforma DIO onde o objetivo é trazer soluções Cloud para uma indrutria farmacêutica onde não nenhum tipo de recurso em nuvem ainda.

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 21/05/2025
Empresa: Abstergo Industries
Responsável: Alessandro dos Santos Lima  

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Indutrie, realizado por Alessandro dos Santos Lima. O objetivo do projeto foi *elencar 3 serviços AWS, com a finalidade de *realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto: 

Etapa 1: 
- Lambda
- O objetivo dessa ferramenta é trazer custo somente para quando o código é executado
- Nesse caso usaremos o serviços AWS Lambda para colocar todo o código que faz o CRUD do estoque da empresa, sendo assim pago somente por quando é executada uma operação de alteração de estoque.

Etapa 2: 
- DynamoDB
- Esse bando de dados NoSQL permite eficiência e escalabilidade permitindo armazenas as quantidades de diferentes itens do estoque sem manter um custo fixo, mas somente por requisição.
- A ideia é que o serviços citado na etapa 1 (AWS Lambda) acessa o DynamoDB e realize o CRUD nele trazendo custo somente quando houver uma alteração no estoque.

Etapa 3:

- API Gateway HTTP
- Este serviço permite a comunicaçãop segura e de forma eficiente usando o protocolo HTTP (outros também) ao serviço da etapa 1 (AWS Lambda) de forma simples e prática.
- Será utilizado para disponibilizar os endpoints para a parte de front-end conseguir comunicar com o código back-end no serviço Lambda. 

## Conclusão
A implementação de ferramentas na empresa *Abstergo Industrie tem como esperado a diminuição na utilização de uma infraestrutura física para a gestão de seu estoque, e isso não só gera economia, como gera também segurança para os dados já que estão sobre proteção da Amazon Web Service. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologia que possam melhorar ainda mais os processos da empresa. 

Assinatura do Responsável pelo Projeto:

Alessandro dos Santos Lima

