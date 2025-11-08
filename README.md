Gerenciamento de Pedidos e Estoque
Este repositório implementa um sistema completo para controle de pedidos e estoque, projetado para promover autonomia e entendimento de arquitetura sem dependência de automação ou IA.

Arquitetura
O projeto segue separação de responsabilidades, garantindo escalabilidade e facilidade de manutenção:

config

controller

service

repository

domain/model

dto

exception

Tecnologias
Java 17

Spring Boot

Spring Web

Spring Data JPA

Spring Security (JWT/bCrypt)

Hibernate

PostgreSQL

Maven

Docker (opcional)

Entidades Principais
Produto: item disponível para venda

Cliente: comprador

Pedido: registro da transação

ItemPedido: relaciona Pedido e Produto, registrando quantidade e valor

Regras de Negócio
Estoque não pode ser negativo

Reserva de estoque ao criar pedido

Reposição de estoque ao cancelar pedido

Somente pedidos pagos podem ser enviados

Passos de Implementação
Configure projeto e banco

Implemente Produto e seu CRUD

Use DTOs para ocultar modelo

Implemente Cliente

Implemente Pedido e ItemPedido com relacionamentos

Adicione regras na camada de serviço

Implemente autenticação JWT após o sistema estar funcional

Segurança
Autenticação JWT e senhas seguras (BCrypt) são aplicadas após validação funcional do sistema.
