# Açaí da Bibi — Landing Page

Landing page para uma açaiteria fictícia chamada **Açaí da Bibi**, desenvolvida
como projeto da disciplina de Desenvolvimento Web.

## Aluno
Eric G. Andrade

## Sobre o projeto
O site apresenta o cardápio, a história da açaiteria e informações de contato,
com identidade visual (cores e logo) baseada na marca "Açaí da Bibi". A
navegação principal acontece em uma única página (`index.html`), com páginas
complementares para o cardápio completo e o formulário de contato.

## Estrutura do site

- **`index.html`** — página principal (one-page), contendo:
  - Cabeçalho com logo e menu de navegação
  - Hero (chamada principal com foto da logo)
  - Cardápio em destaque, dividido em "Mais Vendidos" e "Deliciosos"
  - Sobre (resumo da história)
  - Contato (endereço, WhatsApp e horário)
  - Rodapé
- **`pages/cardapio.html`** — cardápio completo, com todos os produtos e seus
  tamanhos (200ml / 300ml / 500ml) e preços
- **`pages/contato.html`** — formulário de contato funcional, com validação
  client-side em HTML5
- **`pages/sobre.html`** — história expandida da Bibi *(em desenvolvimento)*

## Tecnologias utilizadas até o momento
- HTML5 semântico (`header`, `nav`, `main`, `section`, `article`, `footer`)
- CSS3 (variáveis de cor, Flexbox, Grid, media queries para responsividade)

## Estrutura de pastas
projeto-web/
├── index.html
├── /pages
│ ├── cardapio.html
│ ├── contato.html
│ └── sobre.html
├── /css
│ └── style.css
├── /js
│ └── script.js
├── /img
└── README.md


## Status atual
- ✅ Entrega N1: estrutura HTML5 semântica, CSS próprio (sem framework),
  layout com Flexbox/Grid, responsivo (testado em desktop, tablet e mobile)
- ⏳ `pages/sobre.html` — conteúdo ainda pendente
- ⏳ Entrega N2 (próxima etapa): Bootstrap, JavaScript, jQuery e refinamentos
  de validação do formulário
