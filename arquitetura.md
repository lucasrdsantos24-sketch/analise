Proposta de Arquitetura

Arquitetura sugerida

A arquitetura recomendada é baseada no padrão MVC.

- Model: responsável pelos dados e regras de negócio, como Produto, Pedido e Cliente.
- View: responsável pela interface do usuário.
- Controller: responsável por processar as ações do usuário e conectar Model e View.

Essa abordagem melhora a organização e facilita a manutenção.

Componentes principais

- Sistema de gerenciamento de produtos
- Sistema de pedidos
- Sistema de clientes
- Sistema de pagamento

Aplicação de padrões

O padrão Factory pode ser utilizado para criar objetos como Produto e Pedido.

O padrão Singleton pode ser aplicado na conexão com o banco de dados, garantindo uma única instância.
