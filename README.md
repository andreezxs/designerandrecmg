# 🎨 Portfólio de Design Gráfico | @designerandrecmg

Este é o código-fonte da página de **Portfólio Pessoal** de **@designerandrecmg**. O objetivo do site é funcionar como um **cartão de visitas digital** para exibir projetos, serviços e a filosofia criativa do designer.

É uma *landing page* moderna, focada em performance e experiência visual, utilizando cores de alto contraste e animações sutis para engajar o visitante.

## ✨ Tecnologias & Bibliotecas Utilizadas

O projeto é uma página estática (HTML/CSS/JS) que utiliza as seguintes ferramentas:

| Categoria | Recurso | Propósito |
| :--- | :--- | :--- |
| **Framework CSS** | [**Tailwind CSS**](https://tailwindcss.com/) | Estilização rápida e responsiva, aplicada diretamente no HTML. |
| **Animação** | [**AOS (Animate On Scroll)**](https://michalsnik.github.io/aos/) | Efeitos de transição e animação ao rolar a página para dar vida aos projetos. |
| **Ícones** | [**Feather Icons**](https://feathericons.com/) | Ícones vetoriais simples e elegantes. |
| **Animações Lottie** | [**LottieFiles**](https://lottiefiles.com/) | Animações vetoriais leves para os ícones de serviço. |
| **Efeito de Fundo** | [**Vanta.js (GLOBE)**](https://www.vantajs.com/) | Efeito de fundo 3D interativo na seção de destaque (`#hero`). |
| **Tipografia** | [**Google Fonts (Poppins)**](https://fonts.google.com/specimen/Poppins) | Fonte geométrica **Poppins**, escolhida pela clareza e apelo moderno. |

## 🎨 Design System e Estilo Visual

O design adota uma paleta em preto e branco com cores de alto destaque para criar uma estética moderna e impactante.

### Cores Principais

| Nome da Classe | Variável CSS | Código Hexadecimal | Propósito |
| :--- | :--- | :--- | :--- |
| **Destaque Verde** | `.text-highlight-green` | `#A4FA3C` | **Cor Principal de Ação (CTA)**, destaque visual no Hero e links. |
| **Destaque Laranja** | `.text-highlight-orange` | `#FA553C` | Destaque secundário e contraste. |
| **Fundo** | `body` | `#FFFFFF` (Branco) | Fundo principal clean. |

### Tipografia

A fonte principal utilizada é a **Poppins**, que é importada do Google Fonts e definida para todo o corpo da página, garantindo um visual unificado em todos os dispositivos.

```css
font-family: 'Poppins', sans-serif;
```

## 🏗️ Estrutura do Portfólio (Seções)

O portfólio é organizado em seções que guiam o visitante da apresentação inicial (Hero) até o contato:

| ID da Seção | Propósito | Conteúdo Principal |
| :--- | :--- | :--- |
| **`#hero`** | **Primeira Impressão** | Título principal, slogan e botões de navegação. |
| **`#sobre`** | **Filosofia do Designer** | Texto sobre a abordagem criativa e propósito do trabalho. |
| **`#servicos`** | **O que é Oferecido** | Apresentação dos serviços (Identidade Visual, Redes Sociais, Promocionais) em cards animados. |
| **`#portfolio`** | **Galeria de Projetos** | **Exibição dos trabalhos** com miniaturas e links para o portfólio completo no Behance. |
| **`#contato`** | **Conecte-se** | **Chamada para Orçamento via WhatsApp** e links para redes sociais (Behance e Instagram). |


## 🛡️ Proteção de Conteúdo

O código-fonte inclui um script JavaScript para tentar **desencorajar a cópia** fácil do conteúdo ou design, bloqueando:

  * O menu de contexto (botão direito do mouse).
  * Teclas de atalho como `Ctrl+C`, `Ctrl+X`, `F12` e `Ctrl+Shift+I/J`.


## 🚀 Como Visualizar

Para ver o portfólio, basta abrir o arquivo HTML em seu navegador.
