# 🎬 YouTube Grid Layout

Projeto educacional desenvolvido como desafio de **CSS Grid Layout**, inspirado na organização visual da página inicial do YouTube e na referência do Figma fornecida.

## 📌 Objetivo

Praticar a criação de uma página com cabeçalho, menu lateral e grade de vídeos usando HTML semântico e CSS, com foco no CSS Grid Layout.

## 🛠 Tecnologias utilizadas

### HTML5
Define a estrutura e o conteúdo. Elementos como `header`, `aside`, `nav`, `main`, `section` e `article` organizam a página semanticamente e facilitam sua compreensão.

### CSS3
Controla a aparência: cores, tipografia, dimensões, espaçamentos, alinhamento e adaptação para diferentes tamanhos de tela.

### CSS Grid Layout
É a tecnologia central do desafio. `display: grid`, `grid-template-columns`, `grid-template-rows` e `grid-template-areas` organizam as regiões da página e distribuem os cartões de vídeo em colunas. `gap` define o espaçamento entre os elementos.

### Flexbox
É útil para alinhar itens em uma única direção. No projeto, pode ser usado em componentes do cabeçalho, como o alinhamento do logotipo e dos controles, enquanto Grid organiza a estrutura geral.

### SVG (Scalable Vector Graphics)
Os ícones do cabeçalho e do menu são desenhados com SVG diretamente no HTML. Como são vetoriais, permanecem nítidos em diferentes tamanhos e não precisam de arquivos de imagem externos.

### Media Queries
As regras `@media` ajustam o layout em telas menores, reduzindo o número de colunas e adaptando espaçamentos para celulares e tablets.

## 📂 Estrutura do projeto

```text
youtube_grid/
├── index.html
├── style.css
├── README.md
└── img/
    ├── avatar-perfil.jpg
    ├── avatar-canal.jpg
    ├── avatar-canal-2.jpg
    ├── video-dados.jpg
    ├── video-scrum.jpg
    ├── video-machine-learning.jpg
    ├── video-project-planning.jpg
    └── video-python.jpg
```

## 📷 Como executar

1. Baixe ou extraia o projeto.
2. Mantenha `index.html`, `style.css` e a pasta `img/` na mesma estrutura.
3. Abra `index.html` em um navegador moderno.

Não é necessário instalar dependências nem iniciar um servidor para visualizar a página.

**Para funcionar totalmente offline:** as imagens precisam estar salvas na pasta `img/` e os atributos `src` do HTML devem apontar para esses arquivos locais. Se algum `src` ainda usar um endereço `https://...`, substitua-o pelo caminho local correspondente.

## 🚀 Conceitos de Grid praticados

- `display: grid`: ativa o CSS Grid no elemento.
- `grid-template-columns`: define as colunas.
- `grid-template-rows`: define as linhas.
- `grid-template-areas`: nomeia e organiza regiões do layout.
- `grid-area`: posiciona elementos nas áreas definidas.
- `repeat(4, minmax(0, 1fr))`: cria quatro colunas flexíveis de largura equivalente.
- `gap`, `row-gap` e `column-gap`: definem os espaços entre os itens.
- `minmax(0, 1fr)`: ajuda a impedir que o conteúdo force uma coluna a ultrapassar o espaço disponível.

## 📱 Responsividade

O CSS usa media queries para reorganizar a interface conforme a largura da tela: quatro colunas em telas grandes, menos colunas em telas intermediárias e uma coluna em telas estreitas.

## 🔹 Como personalizar

- **Adicionar vídeos:** duplique um elemento `<article class="video-card">` no `index.html` e altere a miniatura, o título e as informações.
- **Trocar imagens:** salve os arquivos em `img/` e atualize os caminhos dos atributos `src`.
- **Trocar ícones:** substitua os elementos SVG no HTML por outros SVGs.
- **Ajustar o layout:** altere colunas, espaçamentos e pontos de quebra no `style.css`.

## 📚 Observação

Este é um projeto de estudo inspirado na interface do YouTube; não é um produto oficial. Os conteúdos e as imagens são ilustrativos.

## 👨‍💻 Autoria

Projeto de estudo para praticar HTML, CSS e, principalmente, **CSS Grid Layout**.

Por: Alexandre Freitas
Instagran: @alefreitas.tech
