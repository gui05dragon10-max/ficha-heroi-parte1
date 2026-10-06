# 📁 Portfólio Pessoal - Front-End

Este é meu projeto desenvolvido durante a disciplina **Tecnologia Web - Engenharia da Computação**. Trata-se de um site de portfólio interativo com temática RPG (baseado no herói criado *Leon Lionheart - O Santo do Sol*), apresentando informações sobre o personagem, suas habilidades, conquistas, inventário e formulário de contato.

---

## 📌 Sobre o Projeto

Este site foi criado com o objetivo de aplicar na prática os conhecimentos de **HTML5**, **CSS3** (utilizando **CSS Grid** e **Flexbox**), **responsividade** e **publicação com GitHub Pages**.

O projeto foi dividido em duas fases:
- **Parte 1:** Estruturação HTML, estilização inicial e prototipagem no Figma.
- **Parte 2:** Ajustes de layout, responsividade para dispositivos móveis, organização do CSS e publicação online.

---

## 🧪 Funcionalidades

- **Seção Sobre o Herói:** Apresentação completa com imagem e lore do personagem.
- **Atributos & Habilidades:** Exibição estruturada das cartas de habilidades (*Golpe Luminoso*, *Proteção Divina*, *Escudo da Fé*, *Lâmina Purificadora*) utilizando layouts em Grid e Flexbox.
- **Páginas de Conquistas:** Links para páginas secundárias de desafios e locais (*Templo*, *Ruínas*, *Fortaleza*, *Minas-Gûl*).
- **Contato com a Guilda:** Formulário de envio de mensagens e contato.
- **Layout Responsivo:** Adaptação para telas desktop, tablet e mobile.

---

## 💻 Como Visualizar o Projeto

1. Baixe ou clone este repositório para o seu computador.
2. Navegue até a pasta do projeto.
3. Abra o arquivo `Index.html` diretamente no seu navegador de preferência.

*(Opcional: Você também pode acessar a versão publicada diretamente pelo link na seção de Acesso ao Projeto abaixo).*

---

## 🧰 Tecnologias Utilizadas

- **HTML5:** Estruturação semântica do conteúdo.
- **CSS3:** Estilização, variáveis (`:root`), animações, Flexbox, CSS Grid e Media Queries.
- **Font Awesome:** Ícones temáticos para atributos, habilidades e navegação.
- **Git + GitHub** (Controle de versão e hospedagem)
- **GitHub Pages** (Publicação da aplicação online)

---

## 🎨 Decisões de UI/UX (Design e Experiência do Usuário)

Neste projeto, foram aplicados conceitos fundamentais de interface e usabilidade para garantir uma navegação fluida e temática:

1. **Paleta de Cores e Contraste (Estética Temática):**
   - Utilização de tons de dourado (`gold`, `#d4af37`) sobre um fundo predominantemente escuro (`#1e1e1e`).
   - Essa escolha cria uma estética de RPG medieval/paladino e garante um alto contraste entre o texto e o fundo, facilitando a leitura (atendendo aos critérios de acessibilidade WCAG).

2. **Hierarquia Visual e Organização em Cards:**
   - As seções do site foram estruturadas em blocos visuais distintos utilizando **CSS Grid** e **Flexbox**.
   - O uso de ícones temáticos (Font Awesome) e barras de progresso estilizadas permite que o usuário identifique os atributos e habilidades do herói rapidamente.

3. **Responsividade e Feedback Visual:**
   - **Responsividade:** Uso de *Media Queries* no CSS para garantir que a interface se adapte perfeitamente a diferentes telas — 1 coluna em dispositivos móveis, 2 em tablets e 3 em computadores desktop.
   - **Feedback (Affordance):** Adição de efeitos de hover com transições suaves (`transition: 0.3s`) nos botões e cards, indicando ao usuário que esses elementos são interativos.

---

## 🔗 Acesso ao Projeto

- **GitHub Pages:** [Clique aqui para acessar o site]https://github.com/gui05dragon10-max/ficha-heroi-parte1.git

---

## 📸 Capturas de Tela

> ![Versão Desktop](./imagens/computador.png)

---

## 📄 Licença

Este projeto é de uso educacional, criado como parte da disciplina **Tecnologia Web**.

---

## 👩‍💻 Desenvolvido por

- Guilherme Soares de Almeida - RA: `266132`
- **Turma:** Engenharia da Computação / [2 Semestre de manhã]
- **GitHub:** https://github.com/gui05dragon10-max

---
## 📂 Estrutura do Projeto

```text
ficha-heroi/
├── index.html        # Página principal da ficha do herói
├── Gold.css          # Arquivo de estilos CSS
├── Templo.html       # Página detalhada da Conquista 1
├── templo-gold.css   # Estilo CSS da Conquista 1
├── Fortaleza.html    # Página detalhada da Conquista 2
├── fortaleza.css     # Estilo CSS da Conquista 2
├── Ruinas.html       # Página detalhada da Conquista 3
├── ruinas.css        # Estilo CSS da Conquista 3
├── Minas-Gûl.html    # Página detalhada da Conquista 4
├── Minas-Gûl.css     # Estilo CSS da Conquista 4
└── README.md         # Documentação do projeto
