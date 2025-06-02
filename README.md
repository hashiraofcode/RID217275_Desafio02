# 🚀 Projeto: Blog News – Desafio DNC RID #02

## 📚 Desenvolva um Blog Responsivo

## 🎯 Objetivo
> O objetivo do desafio é desenvolver um blog responsivo que se adapte a qualquer dispositivo, garantindo uma boa experiência do usuário a partir de um design funcional.

---

## 🔓 Execução do Desafio

Para resolver este desafio, analisei a interface proposta no protótipo do Figma e observei qual seria a melhor forma de organizar o layout da página, de forma que o código permanecesse adaptável entre diferentes aparelhos, **sem a necessidade de muitas media queries**.

Concluí que a melhor abordagem seria utilizar **CSS Grid Layout** para estruturar as seções principais e **Flexbox** para interfaces menos complexas. Para garantir responsividade com menos código, utilizei **medidas relativas** (`rem`, `%`, `vw`, `vh`, `dvw`, `dvh`) e a função `clamp()`.

Vale destacar que a construção do blog foi feita com **tags semânticas** (`header`, `main`, `section`, etc.) e com as **melhores práticas de acessibilidade**.

---

## 🔨 Tecnologias Utilizadas
- HTML5
- CSS3 (com Grid, Flexbox, Media Queries e unidades relativas)

---

## 📃 Critérios de Avaliação

- **Semântica:**  
  Tags semânticas HTML5 (`header`, `footer`, `section`, `nav`, etc.) foram aplicadas corretamente de acordo com o protótipo.

- **Unidades de Medidas:**  
  Todas as fontes, margens, paddings e espaçamentos utilizam unidades relativas (`rem`, `%`, etc.).

- **Componentes Responsivos:**  
  O layout utiliza Grid e Flexbox. `Media queries` foram aplicadas corretamente para ajustar a visualização em diferentes dispositivos.

- **Responsividade:**  
  O blog foi testado em uma variedade de resoluções, de **320px (mobile)** até **2560px (ultrawide)**, sem quebras ou distorções.

---

## 📷 Imagens do Projeto

### 💻 Desktop

<p align="center">
  <img src="assets/imgDesktop1.png" alt="Imagem do projeto" width="100%"/>
  <img src="assets/imgDesktop2.png" alt="Imagem do projeto" width="100%"/>
</p>

---

### 📱 Tablet

<p align="center">
  <img src="assets/imgTablet1.png" alt="Imagem do projeto" width="90%"/>
  <img src="assets/imgTablet2.png" alt="Imagem do projeto" width="90%"/>
</p>

---

### 📱 Mobile

<p align="center">
  <img src="assets/imgMobile1.png" alt="Imagem do projeto" width="90%"/>
  <img src="assets/imgMobile2.png" alt="Imagem do projeto" width="90%"/>
</p>

---

### 🥇 Extra

> Esta foi a nota de SEO obtida no teste realizado com o **Lighthouse** do Google:

<p align="center">
<img src="assets/seo.png" width="100%"/>
</p>

---

## 🔗 Link do Projeto Publicado

[🌐 Acesse o Projeto no Netlify](https://thenewsdevblog.netlify.app/)

---

✨ Obrigado por conferir! Se curtir, me segue no LinkedIn e confere os outros projetos também! 🚀
