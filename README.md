<h1 align="center">☕️ Gerenciamento de Pedidos e Estoque</h1>

<div align="center">
  <img src="https://img.shields.io/badge/Java-17-007396?style=for-the-badge&logo=java" />
  <img src="https://img.shields.io/badge/Spring_Boot-2.7-brightgreen?style=for-the-badge&logo=springboot" />
  <img src="https://img.shields.io/badge/PostgreSQL-15-336791?style=for-the-badge&logo=postgresql" />
</div>

<hr style="border: 2px solid #2ecc40; margin: 24px 0;" />

<p><strong>Projeto voltado para o aprendizado prático de arquitetura de software,<br>
sem uso de código pronto ou IA, focando em boas práticas.</strong></p>

<hr style="border: 2px solid #2ecc40; margin: 24px 0;" />

<h2>🎯 Arquitetura</h2>
<pre style="background:#f5f5f5; padding:14px; border-radius:6px;">
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
</pre>

<hr style="border: 2px solid #2ecc40; margin: 24px 0;" />

<h2>🚀 Tecnologias</h2>
<ul>
  <li><strong>Java 17</strong> ☕️</li>
  <li><strong>Spring Boot, Spring Web, Spring Data JPA, Spring Security (JWT/Bcrypt)</strong> 🥗</li>
  <li><strong>Hibernate</strong> 🗄️</li>
  <li><strong>PostgreSQL</strong> <img src="https://img.shields.io/badge/PostgreSQL-15-336791?style=flat&logo=postgresql" height="16"/></li>
  <li><strong>Maven</strong> 🛠️</li>
  <li><strong>Docker (opcional)</strong> 🐳</li>
</ul>

<hr style="border: 2px solid #2ecc40; margin: 24px 0;" />

<h2>📝 Entidades Principais</h2>
<ul>
  <li><strong>Produto:</strong> item disponível para venda</li>
  <li><strong>Cliente:</strong> comprador</li>
  <li><strong>Pedido:</strong> registro da compra</li>
  <li><strong>ItemPedido:</strong> ligação entre Pedido e Produto (quantidade e valor)</li>
</ul>

<hr style="border: 2px solid #2ecc40; margin: 24px 0;" />

<h2>📋 Regras de Negócio</h2>
<ul>
  <li>Impede estoque negativo</li>
  <li>Reserva estoque ao criar pedido</li>
  <li>Devolve estoque ao cancelar pedido</li>
  <li>Só permite envio de pedidos pagos</li>
</ul>

<hr style="border: 2px solid #2ecc40; margin: 24px 0;" />

<h2>🔨 Passos para Implementação</h2>
<ol>
  <li>Configure projeto e banco</li>
  <li>Implemente Produto (CRUD)</li>
  <li>Use DTOs</li>
  <li>Implemente Cliente</li>
  <li>Implemente Pedido e ItemPedido</li>
  <li>Aplique regras de negócio no Service</li>
  <li>Adicione autenticação JWT apenas ao final</li>
</ol>

<hr style="border: 2px solid #2ecc40; margin: 24px 0;" />

<h2>🔒 Segurança</h2>
<p>Autenticação JWT e senhas com BCrypt <br>
(<em>Só após validação do sistema estar funcional</em>).</p>

<hr style="border: 2px solid #2ecc40; margin: 24px 0;" />
