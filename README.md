# SyntaxWear

SyntaxWear é um projeto de landing page para uma loja online de tênis e sneakers, com foco em um visual moderno, elegante e voltado para o público urbano. O site foi desenvolvido em HTML e CSS, com estrutura organizada em arquivos separados para facilitar manutenção e evolução.

## Sobre o projeto

Este projeto tem como objetivo apresentar a marca SyntaxWear, destacar modelos de calçados, exibir categorias principais e oferecer uma experiência visual atrativa para o usuário. A interface inclui:

- header com logo, navegação e menu mobile
- seção hero com destaque principal e chamadas para ação
- cards de categorias como Casual, Esportivo, Moderno e Futurista
- grid de produtos em destaque
- footer com newsletter, redes sociais e links de navegação

## Tecnologias utilizadas

- HTML5 para estrutura da página
- CSS3 para estilização e layout
- Arquivos CSS organizados por responsabilidade:
  - reset.css
  - variables.css
  - base.css
  - layout.css
  - components/ para blocos reutilizáveis como header, hero, categorias e produtos

## Estrutura do projeto

```text
ecommerce-sytaxwear/
├── index.html
├── css/
│   ├── base.css
│   ├── layout.css
│   ├── reset.css
│   ├── variables.css
│   └── components/
│       ├── footer.css
│       ├── header.css
│       ├── hero.css
│       ├── product-category.css
│       └── product-grid.css
├── images/
│   ├── banners/
│   ├── favicons/
│   ├── icons/
│   ├── logo/
│   └── products/
└── README.md
```

## Como visualizar o projeto

Não há dependências externas nem build necessário. Você pode abrir o arquivo index.html diretamente no navegador ou usar uma extensão como Live Server no VS Code para visualizar a página em um servidor local.

### Opção 1: abrir diretamente

1. Abra a pasta do projeto no VS Code
2. Clique em index.html
3. Selecione a opção "Open with Live Server" ou abra o arquivo no navegador

### Opção 2: usar Live Server

1. Instale a extensão Live Server no VS Code
2. Clique com o botão direito em index.html
3. Selecione "Open with Live Server"

## Como personalizar

- Edite o conteúdo principal em index.html
- Ajuste cores, tipografia e espaçamentos em css/variables.css e css/base.css
- Modifique seções visuais específicas nos arquivos dentro de css/components/
- Troque imagens e ícones nas pastas de images/

## Melhorias futuras

- Adicionar páginas internas de categoria e produto
- Implementar interação com carrinho e menu
- Criar versão responsiva mais refinada para dispositivos móveis
- Integrar com um backend ou e-commerce funcional

## Autor

Projeto desenvolvido como exemplo de site institucional/landing page para e-commerce com HTML e CSS.

