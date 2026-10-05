# ⚔️ Leon Lionheart - O Santo do Sol

> Ficha de Personagem de RPG desenvolvida para a disciplina de Desenvolvimento Web.

---

## 📖 Sobre o Personagem & Universo

**Leon Lionheart** é um paladino sagrado e campeão da Ordem do Sol Dourado. Guiado pela luz solar, ele utiliza sua fé invocando chamas sagradas para proteger os fracos e expurgar as trevas do reino de Solaria.

Nesta ficha interativa, é possível visualizar a biografia do herói, suas estatísticas de atributos principais, suas habilidades e conquistas, além do seu inventário de equipamentos sagrados.

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

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica do conteúdo.
- **CSS3:** Estilização, variáveis (`:root`), animações, Flexbox, CSS Grid e Media Queries.
- **Font Awesome:** Ícones temáticos para atributos, habilidades e navegação.

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