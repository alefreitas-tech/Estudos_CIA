# 🎬 Clone Página YouTube - Video Play

Projeto desenvolvido com HTML5 e CSS3 com o objetivo de praticar conceitos de estruturação de páginas, posicionamento de elementos, responsividade e organização visual inspirada na interface do YouTube.

---

## 📌 Objetivo do Projeto

O principal objetivo deste projeto foi aplicar na prática os conceitos fundamentais de desenvolvimento Front-End utilizando apenas HTML e CSS, criando uma interface semelhante a uma plataforma de vídeos.

O projeto simula:

- Barra superior de navegação;
- Área principal de vídeo;
- Informações do canal;
- Botões de interação;
- Descrição do vídeo;
- Sidebar com sugestões de vídeos;
- Layout responsivo para dispositivos móveis.

---

# 🛠 Tecnologias Utilizadas

- HTML5
- CSS3
- Flexbox
- Media Queries
- Google Fonts

---

# 📚 Conceitos CSS Aplicados

## 🔹 Flexbox

O Flexbox foi utilizado para organizar e alinhar os elementos da página de forma flexível e responsiva.

Principais propriedades utilizadas:

```css
display: flex;
justify-content: space-between;
align-items: center;
flex-direction: column;
gap: 20px;
```

O Flexbox foi aplicado em:

- Barra superior;
- Área de ações do vídeo;
- Organização da sidebar;
- Estrutura principal do conteúdo.

---

## 🔹 Responsividade com Media Queries

Foram utilizadas Media Queries para adaptar o layout em telas menores, como celulares e tablets.

Exemplo:

```css
@media (max-width: 700px)
```

No modo mobile:

- Os elementos passam a ficar empilhados;
- O vídeo ocupa toda a largura da tela;
- A sidebar é reorganizada verticalmente;
- Os textos e imagens são redimensionados.

---

## 🔹 Box Model

Foi utilizado o conceito de Box Model para controle de:

- espaçamento;
- margens;
- preenchimentos;
- tamanhos.

Exemplo:

```css
box-sizing: border-box;
```

---

## 🔹 Tipografia

A fonte utilizada foi a **Roboto**, importada diretamente do Google Fonts.

```css
@import url('https://fonts.googleapis.com/css2?family=Roboto');
```

---

## 🔹 Organização Visual

Foram utilizados recursos como:

- bordas arredondadas;
- espaçamentos;
- alinhamentos;
- contraste de cores;
- hierarquia visual;
- separação de conteúdo.

---

# 📱 Responsividade

O projeto possui adaptação para dispositivos móveis, ajustando automaticamente:

- Menu superior;
- Área de vídeo;
- Sidebar;
- Tamanho das imagens;
- Textos;
- Botões de interação.

---

# 🚀 Aprendizados

Durante o desenvolvimento deste projeto foi possível praticar:

- Estruturação semântica com HTML;
- Posicionamento com Flexbox;
- Criação de layouts responsivos;
- Organização de componentes visuais;
- Boas práticas de CSS;
- Separação de responsabilidades entre HTML e CSS.

---

# 📷 Preview do Projeto

<img src="imagens/preview.png" alt="Preview Projeto Video Play">

---

# 📂 Estrutura do Projeto

```bash
📁 projeto-video-play
│
├── index.html
├── style.css
├── README.md
└── 📁 imagens
```

---

# 👨‍💻 Autor

Alexandre Freitas / @alefreitas.tech

Projeto desenvolvido para fins de estudo e prática de CSS Responsivo e Flexbox.