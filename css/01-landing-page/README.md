📖 Sobre o Projeto

Este projeto tem como objetivo demonstrar na prática o uso de diversas propriedades e conceitos modernos de CSS3, aplicados na construção de uma página web estilizada, organizada e visualmente atraente.

O foco principal é apresentar:

Organização de layout com Flexbox
Uso de gradientes e imagens de fundo
Estilização de componentes (botões, seções, módulos)
Efeitos visuais (hover, sombras, bordas)
Estruturação visual com boas práticas

🎯 Objetivos
Demonstrar boas práticas de estilização com CSS
Criar uma interface moderna e centralizada
Trabalhar com efeitos visuais e interações
Aplicar organização e reutilização de estilos
🧩 Estrutura do CSS
🔄 Reset CSS

Utilizado para padronizar o comportamento entre navegadores, removendo estilos padrões.

Exemplo:
@import url(reset.css);

🖥️ Layout Principal (Body)
Centraliza todo o conteúdo da página
Utiliza Flexbox
Define cor de fundo geral

Principais propriedades:

display: flex
justify-content: center
align-items: center
background-color

📦 Container Geral
Limita a largura do conteúdo
Define fundo escuro
Define cor padrão do texto

Principais propriedades:

max-width
background-color
color

🔤 Tipografia
Títulos (H2)
Estilo moderno com letras espaçadas
Uso de caixa alta

Principais propriedades:

font-size
letter-spacing
text-transform
color
Parágrafos
Texto branco para melhor contraste

📐 Seções
Espaçamento vertical entre seções

Propriedade utilizada:
margin

🎨 Header (Topo da Página)
Funcionalidades:
Combinação de imagem com gradiente (overlay)
Melhor legibilidade do conteúdo
Centralização do conteúdo

Principais propriedades:

background-image com linear-gradient
background-size: cover
height
text-align

🖋️ Título com Gradiente
Efeito moderno de texto com gradiente
Uso de background-clip

Principais propriedades:

background com gradient
color: transparent
-webkit-background-clip

🧿 Logo Circular
Cria um container circular
Ideal para exibição de logotipo

Principais propriedades:

border-radius: 50%
width / height
margin auto


🔘 Botões
Botão padrão
Estilo moderno com borda em gradiente
Transição suave

Principais propriedades:

border-image
border-radius
transition
text-transform
Hover
Mudança de cor
Alteração de formato
Interatividade com o usuário


📚 Conteúdo de Curso
Container
Define largura do conteúdo
Centraliza textos
Lista de Módulos
Cards estilizados
Bordas arredondadas
Sombra interna (efeito de profundidade)

Principais propriedades:

border-radius
box-shadow (inset)
background-color
border

🌍 Seção com Parallax
Funcionalidades:
Efeito Parallax (imagem fixa)
Destaque visual da seção

Principais propriedades:

background-attachment: fixed
background-image
padding
Texto com Sombra
Cria profundidade visual no texto

Propriedade utilizada:

text-shadow

🧑‍💻 Seção Profissional
Centralização do conteúdo
Espaçamento entre elementos

🔻 Footer (Rodapé)
Funcionalidades:
Gradiente suave
Links estilizados
Organização centralizada

Principais propriedades:

background-image
text-align
padding
border-top

🚀 Tecnologias Utilizadas
CSS3
Flexbox
Gradientes (linear-gradient)
Pseudo-classes (:hover)
Box-shadow
Background effects (cover, fixed)

💡 Conclusão

Este projeto demonstra como o CSS pode ser utilizado para criar interfaces modernas, interativas e bem estruturadas, aplicando conceitos atuais e boas práticas de desenvolvimento front-end.

📌 Possíveis Melhorias
Implementar responsividade com Media Queries
Criar animações com @keyframes
Utilizar variáveis CSS (:root)
Melhorar acessibilidade