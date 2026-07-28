# SyntaxWear

Landing page estática para um e-commerce de tênis e sneakers, com design inspirado em moda urbana e streetwear.

## Visão geral

Este projeto apresenta uma página única que reúne:
- Header fixo com navegação principal e atalhos (lojas, sobre, conta, ajuda, carrinho).
- Hero section com imagem de destaque, título principal e botões de ação.
- Seção de categorias com cards visuais para os segmentos Casual, Esporte, Moderno e Futurista.
- Grade de produtos em destaque com cards estilizados e foco no modelo "Krypton One".
- Footer com inscrição de newsletter, links sociais e navegação secundária.

## Tecnologias utilizadas

- HTML5
- CSS3
- Reset CSS personalizado
- Google Font (`Ubuntu Mono`)
- Imagens e ícones SVG

## Estrutura do projeto

```text
README.md
index.html
css/
├── base.css
├── footer.css
├── header.css
├── hero.css
├── product-category.css
├── product-grid.css
├── reset.css
└── variables.css
images/
├── banners/
├── icons/
└── products/
pages/
```

## Arquivos principais

- `index.html` — página principal.
- `css/reset.css` — estilo base para normalização de elementos.
- `css/variables.css` — variáveis CSS e import de fonte.
- `css/base.css` — tipografia básica, layout e botões.
- `css/header.css` — estilos do cabeçalho e menu responsivo.
- `css/hero.css` — estilo do banner principal.
- `css/product-category.css` — estilo dos cards de categoria.
- `css/product-grid.css` — estilo do grid de produtos.
- `css/footer.css` — estilo do rodapé.

## Como visualizar

1. Abra `index.html` em um navegador.
2. Ou use o Live Server no VS Code para desenvolvimento local.

## Observações importantes

- `index.html` referencia `css/layout.css` e `css/style.css`, mas esses arquivos não existem no projeto atual.
- O diretório `pages/` está presente, mas está vazio.
- Várias imagens usam nomes com extensão dupla como `.svg.svg` e `.jpg.jpg`; verifique se esses caminhos estão corretos.

## Recomendações

- Remova ou adicione `css/layout.css` e `css/style.css` conforme necessário.
- Corrija os arquivos de imagem com extensão duplicada se houver links quebrados.
- Atualize textos e imagens para refletir o branding final do site.

## Objetivo do projeto

Apresentar uma landing page visualmente atraente para uma loja de sneakers, com foco em experiência de navegação e estilo moderno.
