# landing-page-com-grid-agencia-xyz
Estrutura inicial do Projeto de Landing Page com Grid do curso DevQuest.
# landing-page-flex-grid
# 📐 Como Usar CSS Grid e Flexbox Juntos

Este guia apresenta uma abordagem prática para combinar **CSS Grid** e **Flexbox** na construção de layouts responsivos, organizados e eficientes.

---

## 🔹 Por que usar Grid e Flex juntos?

Cada um tem pontos fortes diferentes:

- **Grid** é ideal para **layouts de página**, estruturas em **duas dimensões** (linhas e colunas).
- **Flexbox** é perfeito para **alinhamento** e distribuição de espaço em **uma única direção** (linha ou coluna).

Usar ambos permite criar layouts mais flexíveis e adaptáveis a diferentes tamanhos de tela.

---

## 🧩 Quando usar cada um?

| Situação                           | Melhor escolha      |
|-----------------------------------|---------------------|
| Layout geral da página            | CSS Grid            |
| Componentes dentro de seções      | Flexbox             |
| Alinhamento de itens em linha     | Flexbox             |
| Reorganização em múltiplas colunas | CSS Grid            |

---

## 📱 Responsividade

- Use `auto-fit` ou `auto-fill` no Grid para adaptação automática.
- No Flexbox, utilize `flex-wrap: wrap` para quebra de linha em dispositivos menores.

---

## ✅ Boas práticas

- Use **Grid** para o layout base da página.
- Use **Flex** dentro dos elementos Grid para melhor controle de alinhamento interno.
- Evite sobreposição desnecessária entre os dois sistemas no mesmo elemento.

---

## 🧪 Testes e DevTools

Use o **DevTools** do navegador para alternar entre modos de visualização e verificar como o layout se adapta em diferentes tamanhos de tela.

---

## 📎 Referências úteis

- [MDN Web Docs - Flexbox](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Flexible_Box_Layout)
- [MDN Web Docs - Grid](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Grid_Layout)
