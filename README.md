Entrega II – Experiências Práticas: Linguagem de Estilo (CSS3)

Projeto desenvolvido como parte das Experiências Práticas – Linguagem de Estilo do curso de Desenvolvimento Web, abordando Design System, Layouts Responsivos e Componentes Interativos com CSS3.
Objetivo

Construir uma interface moderna e responsiva utilizando boas práticas de CSS3, aplicando um sistema de design completo, tipografia hierárquica, paleta de cores, e componentes reutilizáveis.

Estrutura do Projeto

Entrega_II_CSS_Project_Final
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── img/
│   │   ├── banner-css3.png
│   │   ├── projeto1.jpg
│   │   ├── projeto2.jpg
│   │   └── projeto3.jpg
│   └── js/
│       └── script.js
└── README.md

Sistema de Design

Paleta de Cores (8 cores)
Nome	Hex	Uso
Primária	#0056D2	Links, botões principais
Secundária	#00ADEF	Destaques e ícones
Sucesso	#2ECC71	Feedback positivo
Atenção	#E67E22	Alertas leves
Erro	#E74C3C	Mensagens de erro
Neutro Claro	#F7F9FC	Fundo
Neutro Médio	#DDE1E7	Bordas e divisórias
Neutro Escuro	#1C1C1C	Texto principal

Tipografia Hierárquica

Título principal (h1) – 32px
Subtítulo (h2) – 24px
Seção (h3) – 20px
Texto padrão (p) – 16px
Detalhe / legenda – 14px
Espaçamento Modular
Sistema baseado em múltiplos de 8px:
8px, 16px, 24px, 32px, 48px, 64px

Layout Responsivo

Estrutura principal em CSS Grid (12 colunas)
Componentes internos utilizando Flexbox
5 breakpoints definidos para:
1440px (desktop grande)
1200px (notebook)
992px (tablet horizontal)
768px (tablet vertical)
480px (smartphones)

Navegação Interativa

Menu principal responsivo com submenu dropdown
Menu hambúrguer funcional em telas menores
Scroll suave entre seções

Componentes de Interface

Tipo	Descrição
Cards	Exibição de projetos e conteúdos
Botões	Estados: hover, focus, active, disabled
Formulários	Campos estilizados com validação visual
Feedbacks	Alerts e toasts simulados
Badges & Tags	Categorização de projetos

Imagens

O projeto inclui imagens ilustrativas (placeholders) simulando conteúdo real:
Banner principal
3 imagens de projetos
Tecnologias Utilizadas
HTML5
CSS3 (Grid, Flexbox, Variáveis Customizadas)
Google Fonts
Font Awesome (ícones)

