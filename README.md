# EcoTrend — Checkpoint IV (Front-End)

Loja virtual de moda sustentável. O projeto é um site estático, responsivo,
construído com HTML, CSS e Bootstrap a partir do design no Figma.

- **Site (GitHub Pages):** https://savac-challenge-fiap.github.io/cp4-frontend/
- **Design (Figma):** https://www.figma.com/design/3yJ1nLbHljozr8qqfrQ6yX/JOVI-Challenge---FIAP-2026?node-id=876-2

## Páginas

| Página | Arquivo | Descrição |
| --- | --- | --- |
| Home | `index.html` | Hero, coleções em destaque e vitrine de produtos |
| Categorias | `pages/categorias.html` | Listagem/catálogo de produtos |
| Produto (PDP) | `pages/pdp.html` | Detalhe do produto: fotos, cores, tamanhos e compra |
| Contato | `pages/contato.html` | Formulário para falar com a loja |

Todas as páginas compartilham o mesmo **header** e **footer** (traduzidos para
pt-BR, com navegação entre as páginas do projeto).

## Tecnologias

- HTML5 semântico
- CSS3 (variáveis/design tokens em `css/style.css`)
- [Bootstrap 5.3](https://getbootstrap.com/) (grid e componentes, via CDN)
- Google Fonts — Nunito
- Font Awesome (ícones)

## Estrutura

```
.
├── index.html            # Home
├── pages/
│   ├── categorias.html
│   ├── pdp.html
│   └── contato.html
├── css/
│   ├── style.css         # estilos globais + design system (header, footer, home)
│   ├── pdp.css           # estilos da página de produto
│   └── contato.css       # estilos da página de contato
└── img/                  # imagens, ícones e favicon
```

## Integrantes

| Nome | RM |
| --- | --- |
| Ana Beatriz Da Cruz Silva | 572278 |
| Arthur Carvalho Gomes Da Costa | 570387 |
| Carolina Kiyomi Hada | 571664 |
| Sávio Pessôa Afonso | 570789 |
| Victor Paes Pontes | 572781 |
