# ✨ Pseudo-elementos Criativos — Lista Estilizada com CSS

Este projeto demonstra como usar **pseudo-elementos** (`::before` e `::after`) para criar efeitos visuais em uma lista HTML.  
Ele exibe combinações de **café + comida** e adiciona marcadores personalizados e textos extras estilizados.

---

## 🎯 Objetivo do Projeto

- Mostrar o uso prático de pseudo-elementos CSS.
- Criar uma lista mais visual, elegante e organizada.
- Destacar itens específicos com etiquetas como “1º destaque”, “2º melhor”, etc.

---

## 🧩 Tecnologias Utilizadas

- **HTML5**
- **CSS3**
  - `::before` para adicionar um marcador ➤ personalizado.
  - `::after` para adicionar observações sobre cada item.
  - Classes específicas (`.destaque`, `.melhor`, `.delicia`) para textos adicionais.

---

## 📌 Funcionamento

### ✔️ `::before`
Adiciona automaticamente uma seta estilizada antes de cada item:

```css
li::before {
  content: "➤";
}
