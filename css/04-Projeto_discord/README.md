# 💬 Discord — Recriação da Página Inicial

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsivo](https://img.shields.io/badge/Design-Responsivo-5865F2?style=for-the-badge)
![Mobile First](https://img.shields.io/badge/Mobile-First-23272A?style=for-the-badge)

## 📌 Sobre o projeto

Este projeto consiste na recriação educacional da página inicial do **[Discord](https://discord.com/)**, utilizando exclusivamente **HTML5 e CSS3**.

O objetivo é reproduzir elementos visuais característicos do site, explorando conceitos fundamentais do desenvolvimento front-end, como estruturação semântica, organização de conteúdo, responsividade e adaptação de layouts para diferentes dispositivos.

O desenvolvimento foi realizado com foco na abordagem **Mobile First**, priorizando a experiência em dispositivos móveis e ampliando progressivamente o layout para tablets, notebooks e computadores.

O projeto também utiliza imagens armazenadas localmente, permitindo visualizar a página sem depender de serviços externos para carregar seus recursos visuais.

---

## 🎯 Objetivos do projeto

- Praticar a construção de páginas utilizando HTML5 semântico.
- Aplicar conceitos de CSS3 para estilização e organização visual.
- Desenvolver layouts responsivos com a abordagem Mobile First.
- Utilizar Flexbox e CSS Grid para organizar elementos.
- Trabalhar com Media Queries para adaptar a página a diferentes resoluções.
- Organizar arquivos HTML, CSS e imagens em uma estrutura de projeto.
- Aplicar princípios básicos de acessibilidade.
- Desenvolver uma página que funcione offline, sem dependências externas de execução.

---

## 🛠️ Tecnologias utilizadas

### 🔹 HTML5

Utilizado para construir a estrutura e organizar o conteúdo da página.

Foram empregados elementos semânticos para representar as diferentes áreas do site, facilitando a compreensão do documento pelos navegadores e pelas tecnologias assistivas.

Principais elementos utilizados:

- `<header>` — cabeçalho da página.
- `<nav>` — áreas de navegação.
- `<main>` — conteúdo principal.
- `<section>` — agrupamento de conteúdos relacionados.
- `<figure>` — organização de ilustrações.
- `<footer>` — rodapé da página.
- `<h1>` a `<h2>` — hierarquia dos títulos.
- `<a>` — links e botões de navegação.
- `<img>` — exibição das imagens.

### 🔹 CSS3

Responsável pela apresentação visual e pela adaptação dos elementos às diferentes dimensões de tela.

Principais recursos utilizados:

- Variáveis CSS com `:root`.
- Flexbox para alinhamento e distribuição dos elementos.
- CSS Grid para organização do rodapé.
- Media Queries para responsividade.
- `clamp()` para dimensionamento flexível da tipografia.
- `min()` e `max-width` para controlar a largura do conteúdo.
- Pseudoclasses como `:hover` e `:focus-visible`.
- Transições para efeitos visuais.
- `prefers-reduced-motion` para respeitar preferências de movimento do usuário.

### 🔹 Design Responsivo

O layout foi planejado para se adaptar a diferentes dispositivos, evitando que o conteúdo ultrapasse a largura da tela ou fique inacessível em telas menores.

A implementação utiliza unidades relativas, imagens flexíveis e regras CSS específicas para diferentes larguras de viewport.

### 🔹 Mobile First

A abordagem Mobile First consiste em desenvolver primeiro a apresentação para dispositivos móveis e, posteriormente, adicionar melhorias para telas maiores.

Neste projeto, o CSS inicial prioriza layouts em coluna, espaçamentos adequados e botões acessíveis. As Media Queries ampliam e reorganizam os elementos conforme aumenta a largura disponível.

---

## 📱 Responsividade

O projeto utiliza os seguintes pontos de adaptação como referência:

| Largura | Aplicação |
|---|---|
| Abaixo de 600 px | Layout inicial para celulares. |
| A partir de 600 px | Ajustes para celulares grandes e tablets. |
| A partir de 900 px | Organização horizontal para telas maiores. |
| A partir de 1200 px | Melhor aproveitamento do espaço em monitores grandes. |

Esses valores são referências de layout, não limitações dos dispositivos. A apresentação depende também da largura disponível e do conteúdo.

---

## 📂 Estrutura do projeto

```text
Discord/
│
├── index.html
├── style.css
├── README.md
│
└── imagens/
    ├── logo-discord.png
    ├── hero-mobile.png
    ├── destaque-01.png
    ├── destaque-02.png
    ├── destaque-03.png
    └── destaque-04.png
```

### 📄 Descrição dos arquivos

| Arquivo ou pasta | Finalidade |
|---|---|
| `index.html` | Contém a estrutura semântica e o conteúdo da página. |
| `style.css` | Define as cores, a tipografia, o layout e a responsividade. |
| `README.md` | Documenta o projeto e as tecnologias utilizadas. |
| `imagens/` | Armazena os recursos visuais utilizados na página. |
| `logo-discord.png` | Identidade visual utilizada no cabeçalho e no rodapé. |
| `hero-mobile.png` | Ilustração principal da página. |
| `destaque-01.png` | Ilustração da primeira seção de conteúdo. |
| `destaque-02.png` | Ilustração da segunda seção de conteúdo. |
| `destaque-03.png` | Ilustração da terceira seção de conteúdo. |
| `destaque-04.png` | Recurso visual adicional do projeto. |

---

## ▶️ Como executar o projeto

Não é necessário instalar dependências ou configurar um servidor.

1. Baixe ou clone o repositório.
2. Extraia os arquivos, caso estejam compactados.
3. Abra a pasta `Discord`.
4. Localize o arquivo `index.html`.
5. Abra-o em um navegador atualizado.

O CSS e as imagens são carregados a partir dos arquivos locais do projeto.

**Observação:** o acesso ao site oficial do Discord e a outros links externos depende de uma conexão com a internet. A visualização local da página não depende dessa conexão.

---

## ♿ Acessibilidade

Durante o desenvolvimento, foram aplicadas algumas práticas para melhorar a experiência de navegação:

- Uso de elementos HTML semânticos.
- Textos alternativos nas imagens.
- Identificação das áreas de navegação.
- Indicação visual do foco para navegação por teclado.
- Respeito à preferência do usuário por movimento reduzido.
- Uso de títulos para organizar hierarquicamente o conteúdo.

Essas práticas contribuem para a acessibilidade, embora não representem uma certificação de conformidade com todas as diretrizes existentes.

---

## 💡 Aprendizados

Este projeto permite exercitar conhecimentos importantes do desenvolvimento front-end:

- Separação entre estrutura HTML e apresentação CSS.
- Uso correto de elementos semânticos.
- Organização de arquivos e diretórios.
- Criação de layouts com Flexbox e Grid.
- Desenvolvimento responsivo com Media Queries.
- Aplicação do conceito Mobile First.
- Utilização de imagens locais.
- Cuidados básicos com acessibilidade e usabilidade.

---

## 👨‍💻 Desenvolvedor

**Alexandre Freitas**

📲 Instagran: **[@alefreitas.tech](https://www.instagram.com/alefreitas.tech/)**



Projeto desenvolvido para fins educacionais e para praticar conceitos de HTML5 e CSS3.

🔗 **Portfólio no GitHub:**  
https://github.com/alefreitas-tech

Se este projeto foi útil para seus estudos, considere visitar o repositório, acompanhar outros projetos e compartilhar o conhecimento com outros desenvolvedores.

---

## ⚖️ Créditos e observações

Este é um projeto independente, desenvolvido para fins educacionais, inspirado na apresentação visual do site do Discord.

Não é um produto oficial, não possui vínculo comercial com a empresa e não representa uma reprodução integral de todas as funcionalidades da plataforma original.

Os nomes e as marcas mencionados pertencem aos seus respectivos proprietários.

---

**Desenvolvido com HTML5, CSS3 e dedicação ao aprendizado de desenvolvimento web.** 🚀