# Pizzaria Online

Bem-vindo ao sistema da **Pizzaria Online**! Este projeto foi desenvolvido para facilitar pedidos de pizzas e bebidas de forma online, com funcionalidades administrativas para gerenciar o cardápio e o sistema de pedidos.

## Funcionalidades

### Para os clientes:
- Visualizar o cardápio de pizzas e bebidas.
- Adicionar itens ao carrinho e realizar pedidos de forma rápida.
- Login e cadastro de usuários para acessar funcionalidades personalizadas.

### Para os administradores:
- Gerenciar o cardápio de pizzas e bebidas.
  - Adicionar, editar ou excluir pizzas e bebidas.
- Visualizar e gerenciar os pedidos realizados pelos clientes.

## Estrutura do Projeto

O sistema é dividido em diferentes páginas e funcionalidades:

- **index.html**: Página inicial que apresenta o cardápio e permite iniciar um pedido.
- **cardapio.html**: Página dedicada ao cardápio completo.
- **login.html**: Página de login e cadastro de novos usuários.
- **adm2.html** e **administrador.html**: Páginas para os administradores gerenciarem o sistema.

## Tecnologias Utilizadas

- **HTML5**: Estrutura principal do projeto.
- **CSS3**: Estilização das páginas.
  - Arquivos de estilo específicos para o header, rodapé e páginas individuais.
- **JavaScript**:
  - Funcionalidades dinâmicas para interação do usuário (e.g., adicionar ao carrinho, validações de formulários).
  - Arquivos dedicados para funcionalidades específicas (e.g., pedidos, administrador).
- **PHP**: Back-end para processamento de dados de login, cadastro e gerenciamento do cardápio (exemplo referenciado nos formulários).

## Estrutura de Diretórios

```
Pizzaria-Online/
├── index.html
├── login.html
├── cardapio.html
├── adm2.html
├── administrador.html
├── assets/
│   ├── css/
│   │   ├── index.css
│   │   ├── header.css
│   │   ├── rodape.css
│   │   ├── login.css
│   │   └── administrador.css
│   ├── img/
│   │   ├── logo.png
│   │   ├── carousel1.png
│   │   └── ...
│   ├── js/
│       ├── pedidos.js
│       ├── pagamento.js
│       └── administrador.js
└── LICENSE
```

## Como Executar

1. Faça o download ou clone este repositório.
2. Configure um servidor local (ex: XAMPP, WAMP ou outro servidor Apache com suporte a PHP).
3. Coloque os arquivos no diretório público do servidor (e.g., `htdocs` no XAMPP).
4. Acesse `http://localhost/index.html` no navegador para iniciar o sistema.

## Licença

Este projeto está licenciado sob a licença presente no arquivo [LICENSE](./LICENSE).

## Contato

Para dúvidas ou sugestões, entre em contato:
- **E-mail**: leticiaconforte@gmail.com


---

Aproveite a experiência com o sistema da Pizzaria Online!
