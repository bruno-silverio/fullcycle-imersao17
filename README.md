# Imersão Full Cycle - Ecommerce

### Projeto: Sistema de Ecommerce baseado em Microsserviços
  - Catálogo de produtos
  - Cart
  - Checkout
  - Pagamento
    
<div align="center">
  
  ## Casos de usos, arquitetura e wireframes
  
  <img src="https://github.com/bruno-silverio/fullcycle-imersao17/assets/27282770/e1650d00-1199-473a-869b-aaf1f2c51487" width="480" height="300">
  
  ### Arquitetura geral do sistema
  
  <img src="https://github.com/bruno-silverio/fullcycle-imersao17/assets/27282770/2094dae8-e972-4173-bda4-9c3e75d967f3">

  ### Criar contexto local de produtos
  
  A aplicação Nest.js terá sua própria tabela de produtos para satisfazer as necessidades locais das ordens de pedido
  
  ### Criar nova ordem de pedido
  
  <img src="https://github.com/bruno-silverio/fullcycle-imersao17/assets/27282770/13cd2b10-389d-4306-8d7b-e88fd969c9d6">

  ### Publicar evento de nova ordem criada
  
  <img src="https://github.com/bruno-silverio/fullcycle-imersao17/assets/27282770/954255e8-af18-4bf8-bd79-f2bc6c09b47d">

  ### Autenticação
  
  <img src="https://github.com/bruno-silverio/fullcycle-imersao17/assets/27282770/050ffe25-0b36-433d-b952-f1cfa5dc2b1f">

</div>




## Ordem do desenvolvimento
- [x] Microsserviço API de produtos - Go
- [ ] API das ordens de compra - Nest.js
  - [ ] Criar o projeto Nest.js
  - [ ] Criar o banco de dados MySQL e integrar com TypeORM
  - [ ] Criar fixture para carregar produtos localmente
  - [ ] Criar rotas REST:
    - [ ] Get /orders - Listar ordens de pedido de um cliente
    - [ ] GET /orders/:ID - Mostrar uma ordem de pedido de um cliente
    - [ ] POST /orders - Criar nova ordem de pedido
    - [ ] POST /auth/login - Gerar token JWT
  - [ ] Criar publicação de evento de criação de uma ordem de pedido no RabbitMQ
- [ ] Frontend da loja - Next.js
- [ ] Integração do Frontend com Backend
- [ ] Processamento de pagamento - Go

## Autores

- [@argentinaluiz](https://github.com/argentinaluiz)
- [@wesleywillians](https://github.com/argentinaluiz)

##
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nextjs" />
    <img src="https://skillicons.dev/icons?i=nestjs" />
    <img src="https://skillicons.dev/icons?i=go" />
    <img src="https://skillicons.dev/icons?i=docker" />
    <img src="https://skillicons.dev/icons?i=rabbitmq" />
  </a>
</p>
