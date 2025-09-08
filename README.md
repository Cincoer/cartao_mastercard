# 💳 Cartão Mastercard Interativo - Web

Este projeto recria um **cartão Mastercard digital em 3D**, utilizando **HTML5** e **CSS3**.
O cartão possui frente e verso, com efeito de **flip animation** (rotação 180°) ao passar o mouse, trazendo uma experiência realista.

---

## 📌 Funcionalidades

* **Frente do cartão**:

  * Logotipo da bandeira.
  * Chip ilustrativo.
  * Número do cartão.
  * Nome do titular.
  * Data de validade.
* **Verso do cartão**:

  * Faixa magnética.
  * Campo de assinatura com código de segurança (CVV).
  * Texto simulado para informações adicionais.
* **Efeito de rotação 3D** ao passar o mouse.
* Fundo com **elementos circulares degradê**, criando um ambiente moderno.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5** → Estrutura do cartão.
* **CSS3** → Estilização, glassmorphism e transformações 3D.
* **Google Fonts (Poppins)** → Tipografia.

---

## 📂 Estrutura de Arquivos

```
📦 Cartao-Mastercard
 ┣ 📂 css
 ┃ ┗ 📜 style.css
 ┣ 📂 img
 ┃ ┣ 📜 cartao.png      # Favicon
 ┃ ┣ 📜 logo.png        # Logo Mastercard
 ┃ ┗ 📜 chip.png        # Chip do cartão
 ┣ 📜 index.html
 ┗ 📜 README.md
```

---

## 🚀 Como Usar

1. Clone este repositório:

   ```bash
   git clone https://github.com/seuusuario/cartao-mastercard.git
   ```
2. Abra o arquivo **index.html** no navegador.
3. Personalize os dados do cartão (número, nome, validade, textos).
4. Substitua as imagens da pasta **img/** caso queira criar sua própria versão.

---

## 🎨 Personalização

* Alterar **cores do fundo** em `section::before` e `section::after` no `style.css`.
* Editar as informações de **nome, número e validade** direto no HTML.
* Trocar as imagens (`logo.png`, `chip.png`) para outras bandeiras/cartões.
* Ajustar dimensões do cartão em `.container { height / width }`.
