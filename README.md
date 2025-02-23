## Descrição do Projeto
Este projeto consiste em um modelo conceitual de um sistema de e-commerce que gerencia informações de clientes, pagamentos e entregas. O foco do modelo é permitir que o sistema seja capaz de lidar com diferentes tipos de clientes (Pessoa Jurídica - PJ e Pessoa Física - PF), múltiplas formas de pagamento e rastreamento de entregas.

## Objetivos do Projeto
O sistema foi projetado para acomodar as seguintes funcionalidades e exigências:

Cliente PJ e PF: Cada cliente pode ser uma Pessoa Jurídica (PJ) ou Pessoa Física (PF), mas não pode ter ambas as informações. Ou seja, uma conta pode ser associada exclusivamente a um tipo de cliente.

Pagamento: O sistema permite que um cliente registre mais de uma forma de pagamento, como cartão de crédito, boleto, transferência bancária, entre outros.

Entrega: O modelo de entrega agora inclui um status da entrega (como "Em Processamento", "Enviado", "Entregue") e um código de rastreio para permitir que o cliente acompanhe o progresso da entrega.

## Estrutura do Modelo
Clientes: A tabela de clientes pode incluir informações como nome, CPF/CNPJ, tipo de cliente (PJ ou PF), e um campo de múltiplas formas de pagamento.

Pagamentos: A tabela de pagamentos será associada a cada cliente, permitindo que múltiplos métodos de pagamento sejam registrados, com campos como tipo de pagamento, valor, status e data de pagamento.

Entregas: A tabela de entregas conterá informações relacionadas ao status da entrega e o código de rastreio, possibilitando ao cliente acompanhar o processo de envio.
