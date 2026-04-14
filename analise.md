Análise do Sistema Real

Parte 1 – Análise do Sistema

1. Objetivo do sistema
O sistema tem como objetivo permitir que clientes realizem pedidos online de pizzas, lanches e bebidas de forma prática, facilitando o processo de compra e comunicação com o estabelecimento.

2. Funcionalidades
O sistema oferece visualização de produtos organizados por categorias, adição de itens ao carrinho, seleção de produtos, finalização de pedidos e redirecionamento para contato via WhatsApp. Também permite visualizar promoções disponíveis.

3. Interação do usuário
O usuário acessa o site, navega pelas categorias, escolhe produtos, adiciona ao carrinho e finaliza o pedido. Após isso, o sistema direciona o usuário para o WhatsApp para confirmação.

4. Organização dos produtos
Os produtos estão organizados em categorias como pizzas, lanches, bebidas e promoções. Cada categoria agrupa vários produtos, formando uma estrutura hierárquica simples.

---

Parte 2 – Análise de Arquitetura

O sistema apresenta uma arquitetura do tipo cliente-servidor, comum em aplicações web.

Pode-se inferir a existência de três camadas:
- Camada de apresentação (interface do usuário)
- Camada de aplicação (lógica de pedidos)
- Camada de dados (armazenamento de informações)

Existe uma separação básica de responsabilidades, onde a interface lida com o usuário e o backend com as regras de negócio.

Parte 3 – Análise de Design

A coesão do sistema é média, pois cada funcionalidade possui um propósito específico.

O acoplamento é moderado, devido à dependência de serviços externos como o WhatsApp.

A separação de responsabilidades existe de forma básica, mas não segue claramente padrões estruturados.
