# 🐾 Zig Presidente — Campanha 2026

![Status](https://img.shields.io/badge/Status-Online-success?style=flat-square&logo=github)
![Tech Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20Vanilla%20CSS%20%7C%20JavaScript%20%7C%20Design%20Premium-blue?style=flat-square)

Bem-vindo ao repositório da campanha presidencial canina mais séria do Brasil. Este projeto é uma **sátira política** desenvolvida como um exercício de criação de interfaces premium, explorando paletas de cores complexas, texturas dinâmicas e animações de scroll.

O design simula o rigor e a estética de uma campanha eleitoral de alto nível, utilizando um esquema de cores escuro, cinematográfico, inspirado sutilmente na bandeira do Brasil (verde floresta, ouro oliva, azul marinho), com aplicação de *grain/noise* para textura fotográfica.

🔗 **Acesse a campanha:** [carlosguedes.github.io/site-zig](https://carlosguedes.github.io/site-zig/) *(Ajuste o link após o deploy)*

---

## ✨ Features Principais

- **Design System Premium (CSS Puro):** Uso de paletas escuras rigorosamente extraídas da imagem-tema, com aplicação de `radial-gradient` para criar *blobs* de cor que imitam iluminação dramática.
- **Textura Dinâmica (Grain Overlay):** Um SVG injetado via CSS gera uma textura de ruído fotográfico em toda a interface, substituindo a necessidade de imagens de fundo pesadas.
- **Animações de Scroll (Reveal):** Uso de `IntersectionObserver` em Vanilla JavaScript para animar elementos, contadores numéricos e seções suavemente à medida que o usuário rola a página.
- **Glassmorphism:** Efeitos sutis de desfoque de fundo (`backdrop-filter`) em cartões e no cabeçalho, garantindo profundidade e uma sensação moderna.
- **Responsividade Pixel-Perfect:** Layouts adaptáveis via CSS Grid e Flexbox, garantindo excelente navegação desde o mobile até monitores ultrawide.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído "do zero" para manter controle absoluto do design e performance, dispensando frameworks robustos:

- **HTML5 Semântico:** Estruturação clara do conteúdo, garantindo acessibilidade (botões descritivos, atributos `aria`).
- **CSS3 (Vanilla):** Uso massivo de Custom Properties (`:root`), pseudo-elementos (`::before`, `::after`) para sobreposições de cor e *vignettes*, além de `@keyframes` para microinterações (como o botão de rolagem da hero section).
- **JavaScript Vanilla:** Lógica modularizada para o funcionamento do menu mobile, transição de estilos no header ao rolar, e observadores de interseção para lazy-loading e gatilhos de animação.

## 📂 Estrutura das Páginas

O projeto não é uma Single Page Application (SPA), mas um site institucional multi-página clássico:

- `index.html`: Home page com a *Hero Section*, números de impacto e manifesto do candidato.
- `sobre.html`: Biografia do Zig, com contadores animados de experiência e uma linha do tempo detalhando sua trajetória.
- `projetos.html`: Propostas satíricas (Bolsa Petisco, Operação Lava-Pata, PL do Banho Voluntário) estruturadas com *tags* coloridas por categoria legislativa.
- `contato.html`: Formulário de contato funcional (UI simulada com feedback assíncrono de sucesso) e painel social de denúncias.

## 🚀 Como Rodar Localmente

Por ser construído utilizando tecnologias nativas do navegador, a execução é imediata:

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/site-zig.git
   ```
2. Abra a pasta do projeto.
3. Utilize o **Live Server** (extensão do VS Code) no arquivo `index.html`, ou simplesmente abra o arquivo `index.html` diretamente em seu navegador web.

## 👨‍💻 Autor

**Carlos Guedes**
*Projeto de estudo focado em UI/UX, Design Premium e Front-End Nativo.*

- **E-mail:** carlosguedes0007@gmail.com
- **GitHub:** [carlosguedes-dev](https://github.com/carlosguedes-dev)

---
*Este site tem fins puramente cômicos e de portfólio. Nenhum gato foi ferido durante o desenvolvimento deste código.*
