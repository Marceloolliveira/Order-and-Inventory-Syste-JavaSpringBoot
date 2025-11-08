// Sistema desenvolvido em Java 17 + Spring Boot
<p align="center"> <img src="https://img.shields.io/badge/Java-17-007396?style=for-the-badge&logo=java" /> <img src="https://img.shields.io/badge/Spring_Boot-2.7-brightgreen?style=for-the-badge&logo=springboot" /> <img src="https://img.shields.io/badge/PostgreSQL-15-336791?style=for-the-badge&logo=postgresql" /> </p>

src/main/java/com.seuprojeto
    ├── config
    ├── controller
    ├── service
    ├── repository
    ├── domain (ou model)
    ├── dto
    └── exception
src/main/resources
    └── application.yml

🚀 Tecnologias
☕ Java 17

🥗 Spring Boot, Spring Web, Spring Data JPA, Spring Security (JWT/Bcrypt)

🗄️ Hibernate, PostgreSQL

🛠️ Maven

🐳 Docker (opcional)

📝 Entidades Principais
Produto: item à venda

Cliente: comprador

Pedido: registro da compra

ItemPedido: ligação entre Pedido e Produto (quantidade e valor)

📋 Regras de Negócio
Impede estoque negativo

Reserva estoque ao criar pedido

Devolve estoque ao cancelar pedido

Só permite envio de pedidos pagos

🔨 Passos para Implementação
Configure projeto e banco

Implemente Produto (CRUD)

Use DTOs

Implemente Cliente

Implemente Pedido e ItemPedido

Aplique regras de negócio no Service

Adicione autenticação JWT apenas ao final

🔒 Segurança
Autenticação JWT e senhas com BCrypt (após validação do sistema).
