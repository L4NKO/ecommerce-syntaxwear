# 👟 SyntaxWear - Tênis e Sneakers Online

Seja muito bem-vindo(a) ao repositório do **SyntaxWear**! Este é um projeto de e-commerce de tênis e sneakers moderno, elegante e totalmente responsivo, desenvolvido como parte do meu aprendizado no curso **DEV QUEST 2.0 (Dev em Dobro)**. 

O objetivo deste projeto é aplicar conceitos avançados de estruturação de páginas web com **HTML5 semântico** e estilização moderna com **CSS3**, utilizando técnicas como Flexbox, CSS Grid e variáveis CSS estruturadas por componentes.

---

## 📌 Índice

- [👟 SyntaxWear - Tênis e Sneakers Online](#-syntaxwear---tênis-e-sneakers-online)
  - [📌 Índice](#-índice)
  - [🚀 Funcionalidades e Seções do Site](#-funcionalidades-e-seções-do-site)
  - [🎨 Design e Identidade Visual](#-design-e-identidade-visual)
  - [💻 Tecnologias Utilizadas](#-tecnologias-utilizadas)
  - [📁 Estrutura de Pastas do Projeto](#-estrutura-of-pastas-do-projeto)
  - [🛠️ Como Executar o Projeto Localmente](#️-como-executar-o-projeto-localmente)
  - [🧠 O que Aprendi com este Projeto](#-o-que-aprendi-com-este-projeto)
  - [👤 Autor](#-autor)

---

## 🚀 Funcionalidades e Seções do Site

O site foi construído focado na experiência do usuário (UX), garantindo fluidez tanto em computadores quanto em celulares (responsividade).

1. **Cabeçalho Dinâmico (Header)**:
   - Menu hambúrguer interativo para celulares, utilizando a técnica de `checkbox hack` em CSS puro (sem JavaScript).
   - Navegação por categorias principais (*Masculino*, *Feminino*, *Outlet*).
   - Links úteis rápidos (*Nossas lojas*, *Sobre*) e ícones amigáveis para *Minha Conta*, *Ajuda* e *Carrinho*.

2. **Seção Hero**:
   - Um banner principal impactante com imagens otimizadas para desktop e celular.
   - Chamada de ação atrativa ("Transforme qualquer passo em presença.") com botões elegantes de "Ver modelos" e "Comprar".

3. **Seção de Categorias**:
   - Cards visuais interativos para quatro categorias de tênis: **Casual**, **Esporte**, **Moderno** e **Futurista**.
   - Efeitos de hover e overlay que escurecem e destacam os botões ao passar o mouse.

4. **Grid de Produtos em Destaque**:
   - Utilização de **CSS Grid** para criar uma galeria de produtos assimétrica e estilosa.
   - Destaque principal para o modelo premium **Krypton One** com chamadas de compra rápidas para os públicos feminino e masculino.

5. **Rodapé Completo (Footer)**:
   - Área para inscrição em Newsletter de ofertas.
   - Links para as principais redes sociais (*Instagram*, *WhatsApp*, *TikTok*, *Facebook*).
   - Menu de navegação secundária organizado e estruturado.

---

## 🎨 Design e Identidade Visual

O design do SyntaxWear foi construído com base em uma paleta de cores moderna e tipografia limpa, configuradas através de **Variáveis CSS** no arquivo `css/variables.css`:

* **Fonte Principal**: `'Ubuntu', sans-serif` (importada diretamente do Google Fonts para dar um visual moderno e legível).
* **Paleta de Cores**:
  * **Cor Primária**: `#1a1a1a` (Preto profundo para elegância e sofisticação).
  * **Cor Secundária**: `#f5f5f5` (Cinza claro para fundos suaves e contraste confortável).
  * **Cor de Destaque (Accent)**: `#ff6600` (Laranja vibrante para atrair o olhar aos botões importantes e links ativos).

---

## 💻 Tecnologias Utilizadas

Este projeto foi construído utilizando as melhores práticas de desenvolvimento front-end para iniciantes:

* **HTML5**: Estruturação semântica de todo o conteúdo (utilizando tags como `<header>`, `<main>`, `<section>`, `<nav>`, `<footer >`, `<form>`, entre outras).
* **CSS3**: 
  * Variáveis customizadas (`:root`) para facilidade de manutenção de cores e fontes.
  * Flexbox para alinhamentos rápidos, barra de navegação e rodapé.
  * CSS Grid para a criação da galeria assimétrica de produtos.
  * Arquitetura modular de estilos (estilos divididos em componentes separados para melhor organização).
  * Media Queries para adaptação perfeita do layout a telas de celulares e tablets.

---

## 📁 Estrutura de Pastas do Projeto

A organização dos arquivos segue as boas práticas de desenvolvimento de software, facilitando a leitura do código:

```text
ecommerce-syntaxwear/
├── index.html          # Arquivo principal com a estrutura HTML do site
├── README.md           # Documentação do projeto (este arquivo!)
├── css/                # Pasta contendo os estilos do site
│   ├── base.css        # Estilos globais e regras de layout do corpo do site
│   ├── reset.css       # Limpeza de margens e padrões dos navegadores
│   ├── variables.css   # Definição de fontes, cores e variáveis CSS reutilizáveis
│   └── components/     # Estilos modulares focados em partes específicas do site
│       ├── footer.css  # Estilos específicos do rodapé
│       ├── header.css  # Estilos específicos do cabeçalho e menu de navegação
│       ├── hero.css    # Estilos específicos do banner principal
│       ├── product-category.css  # Estilos dos cards de categorias
│       └── product-grid.css      # Estilos do grid de produtos em destaque
└── images/             # Pasta contendo todas as imagens e ícones do site
    ├── banners/        # Banners otimizados para desktop e mobile
    ├── icons/          # Ícones em formato SVG (carrinho, usuário, redes sociais)
    ├── logo/           # Logotipo da marca SyntaxWear
    └── products/       # Imagens de tênis utilizadas no grid e categorias
```

---

## 🛠️ Como Executar o Projeto Localmente

Para abrir o projeto na sua máquina e ver o site funcionando, siga as instruções simples abaixo:

1. **Baixe ou clone este repositório**:
   Se você tiver o Git instalado, execute no terminal:
   ```bash
   git clone https://github.com/SEU-USUARIO/ecommerce-syntaxwear.git
   ```
   *Caso não tenha o Git, você pode clicar no botão verde **Code** (no GitHub) e selecionar **Download ZIP**, depois é só extrair os arquivos.*

2. **Abra o projeto no VS Code** (ou outro editor de sua preferência).

3. **Inicie o Live Server**:
   - Se você usa o VS Code, recomendo instalar a extensão chamada **Live Server**.
   - Com o arquivo `index.html` aberto, clique com o botão direito no editor e selecione **Open with Live Server**.
   - O site se abrirá automaticamente no seu navegador padrão no endereço local (geralmente `http://127.0.0.1:5500`).

4. **Alternativa simples**:
   - Basta navegar até a pasta do projeto no seu computador e dar um duplo clique no arquivo `index.html` para abri-lo diretamente em qualquer navegador!

---

## 🧠 O que Aprendi com este Projeto

Como um programador iniciante em transição de carreira, este projeto foi um marco importante no meu aprendizado! Durante o desenvolvimento, pude consolidar os seguintes conhecimentos:

* **HTML Semântico**: Entendi que o HTML vai além de usar apenas `<div>`. Utilizar as tags corretas melhora a acessibilidade para leitores de tela e otimiza o SEO (ranqueamento no Google).
* **CSS Fluído e Layouts Modernos**: Dominar o **Flexbox** e o **CSS Grid** me permitiu estruturar layouts complexos sem precisar de frameworks pesados, entendendo a lógica de eixos e grid-templates.
* **Organização Modular de Estilos**: Aprendi que separar o CSS em componentes (`header.css`, `footer.css`, etc.) torna o código muito mais fácil de ler, debugar e dar manutenção no futuro.
* **Responsividade sem JavaScript**: Criei um menu hambúrguer funcional usando apenas a propriedade CSS `:checked` combinada com seletores de irmão (`+` ou `~`), o que foi um excelente desafio de lógica de CSS.

---

## 👤 Autor

Desenvolvido com carinho por **Alan Camargo**!

Se você quiser trocar ideias sobre programação ou se conectar comigo:

* **LinkedIn**: [LinkedIn](https://www.linkedin.com/in/alanscamargo/)
* **GitHub**: [@Alan Camargo](https://github.com/L4NKO)
* **E-mail**: alancamargo.dev@gmail.com

---
*Este projeto foi desenvolvido como parte dos meus estudos no ecossistema Dev Quest / Dev em Dobro.* 🚀
