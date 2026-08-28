<div align="center">

#  Zig Presidente 2026 — Campanha Eleitoral Canina 

**A plataforma digital oficial, satírica e ultra-premium do candidato canino mais sério, honesto e elegante do Brasil para as eleições de 2026.**

[![Versão](https://img.shields.io/badge/versão-1.0.0-2E8B57?style=for-the-badge&logo=googlechrome&logoColor=white)](https://github.com/carlosguedes-dev/site-zig)
[![Licença](https://img.shields.io/badge/licença-MIT-00ff88?style=for-the-badge)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![Feito com Amor](https://img.shields.io/badge/Feito_com-MUITO_AMOR_-ff0055?style=for-the-badge)](https://github.com/carlosguedes-dev)

---

 **[Acessar o Projeto Ao Vivo / Demonstração Online](https://carlosguedes-dev.github.io/site-zig/)**

---

<p align="center">
  <img src="https://images.unsplash.com/photo-1537151608828-ea2b11777ee8?q=80&w=1200&auto=format&fit=crop" alt="Banner Campanha Zig Presidente 2026" width="80%" style="border-radius: 20px; box-shadow: 0 10px 30px rgba(46, 139, 87, 0.4);">
</p>

</div>

---

##  Sobre o Projeto

O **Zig Presidente 2026** é uma aplicação web multi-página que une **sátira política inteligente** com o que há de mais refinado no design de interfaces web de luxo (*Luxury Dark Mode & Institutional Branding*). O projeto apresenta a campanha presidencial de "Zig", um cão candidato cuja missão é revolucionar o país com propostas audaciosas como a *Bolsa Petisco*, a *Operação Lava-Pata* e o *PL do Banho Voluntário*.

Além do humor e da criatividade narrativa, a plataforma foi concebida como um exercício avançado de UI/UX Design e Front-End Nativo. O layout simula o rigor visual e o peso de uma campanha eleitoral de altíssimo nível, utilizando um esquema de cores escuro e cinematográfico inspirado nas cores da bandeira nacional — Verde Floresta Profundo (`#1a3323`), Ouro Oliva (`#c5a059`) e Azul Marinho Sólido. 

Para elevar a estética visual ao patamar de produções audiovisuais e fotográficas profissionais, o projeto implementa uma **textura dinâmica de ruído (*Grain / Noise Overlay*)** gerada via SVG injetado no próprio CSS, dispensando imagens de fundo pesadas. Combinado a contadores numéricos animados no scroll, *Glassmorphism* em cards legislativos e uma navegação fluida, o site oferece uma experiência interativa memorável e divertida.

---

##  Principais Funcionalidades

-  **Design System Institucional Cinematográfico**: Paleta de cores rigorosa e exclusiva (Verde Floresta, Ouro Oliva e Azul Marinho), com gradientes radiais complexos que simulam iluminação de estúdio profissional.
-  **Textura Fotográfica Dinâmica (Grain Overlay)**: Filtro de ruído (*noise*) em tempo real aplicado via CSS e SVG puramente procedural, conferindo textura tátil e sensação de fotografia analógica a todas as páginas.
-  **Animações de Scroll & Contadores Numéricos**: Sistema acionado via `IntersectionObserver API` em Vanilla JS que revela seções suavemente e anima estatísticas de campanha em tempo real conforme o avanço do usuário.
-  **Arquitetura Multi-Página Clássica**: Navegação institucional completa estruturada em 4 páginas distintas: Home Institucional (`index`), Biografia & Linha do Tempo (`sobre`), Plataforma de Leis Satíricas (`projetos`) e Canal de Denúncias/Contato (`contato`).
-  **Glassmorphism & Componentes Interativos**: Barras de navegação translucentes com `backdrop-filter: blur(16px)`, botões de rolagem animadas com `@keyframes` e formulário de contato funcional com feedback de envio simulado na interface.

---

##  Tecnologias Utilizadas

Este projeto foi construído "do zero" e sem a utilização de frameworks robustos, mantendo controle absoluto sobre cada pixel do design, animação e performance do navegador:

- **HTML5 Semântico Multi-página**: Estruturação acessível com uso rigoroso de tags semânticas (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`), atributos ARIA e marcação limpa.
- **CSS3 Vanilla Avançado**: Utilização em larga escala de Custom Properties (`:root`), Grid Layout, Flexbox, sobreposições com pseudo-elementos (`::before`, `::after`), filtros de desfoque e geradores de vinheta visual.
- **JavaScript Vanilla (ES6+)**: Modularização de scripts para controle responsivo do menu hamburguer mobile, transição de opacidade e estilo do cabeçalho ao rolar a página, e lógica de contadores assíncronos.

---

##  Estrutura de Arquivos

```text
site-zig/
│
├── img/             # Imagens ilustrativas, logotipos, ícones e fotografias da campanha do Zig
├── background.jpeg  # Imagem de fundo principal de alta resolução com tratamento estético de campanha
├── contato.html     # Página com formulário interativo de contato, comitê e painel de denúncias
├── index.html       # Home page institucional com manifesto, hero section e números de impacto
├── main.js          # Lógica JavaScript (menu mobile, IntersectionObserver, reveal e contadores)
├── projetos.html    # Plataforma legislativa com propostas satíricas (Bolsa Petisco, Lava-Pata)
├── sobre.html       # Biografia completa do candidato Zig, experiência e linha do tempo da carreira
├── style.css        # Folha de estilos robusta com variáveis CSS, textura grain e glassmorphism
├── README.md        # Documentação oficial e manifesto técnico da campanha (este arquivo)
├── CONTRIBUTING.md  # Guia para contribuições e alistamento de desenvolvedores no comitê
└── LICENSE          # Licença MIT de código aberto
```

---

##  Como Executar o Projeto

Por ser estruturado de forma nativa e sem necessidade de compilação ou build steps, o projeto pode ser executado instantaneamente em qualquer sistema operacional:

1. **Opção 1: Direto no Navegador (Acesso Imediato)**
   - Faça o clone do repositório em seu terminal ou baixe o arquivo `.zip`:
     ```bash
     git clone https://github.com/carlosguedes-dev/site-zig.git
     ```
   - Acesse a pasta `site-zig/` e dê um **duplo clique** em qualquer um dos arquivos `.html` (por exemplo, `index.html`) para visualizar a campanha diretamente no seu navegador web favorito.

2. **Opção 2: Com VS Code & Live Server (Experiência Ideal)**
   - Abra a pasta do projeto no [Visual Studio Code](https://code.visualstudio.com/).
   - Instale a extensão **Live Server** em seu editor.
   - Clique com o botão direito no arquivo `index.html` e selecione **"Open with Live Server"**. Isso ativará a navegação entre as páginas com recarregamento em tempo real a cada modificação no código.

3. **Opção 3: Publicação Online Gratuita via GitHub Pages**
   - Com os arquivos no GitHub, acesse as **Configurações (Settings)** do repositório.
   - Navegue até a aba **Pages**, selecione a branch principal (`main` ou `master`) na pasta raíz `/ (root)` e salve.
   - Compartilhe o link gerado com todos os seus amigos para apoiar a campanha mais animal do Brasil! 

---

##  Como Contribuir

Quer fazer parte do comitê de campanha do Zig? Se você tem propostas legislativas engraçadas para animais de estimação, melhorias na responsividade ou novas interações de UI/UX, consulte nosso arquivo [CONTRIBUTING.md](CONTRIBUTING.md) e envie o seu *Pull Request*!

---

##  Licença

Este projeto está distribuído sob a licença de código aberto **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<div align="center">
  <p>Feito com todo o carinho e dedicação por <a href="https://github.com/carlosguedes-dev">Carlos Guedes</a> </p>
  <p><b>Por um Brasil com mais petiscos, carinhos e honestidade canina! </b></p>
  <p><i>*Nota: Este site tem fins puramente cômicos e de portfólio. Nenhum gato foi ferido durante o desenvolvimento deste código.*</i></p>
</div>
