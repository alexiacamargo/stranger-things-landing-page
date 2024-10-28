<p align="center">
    <img width="300" src="https://raw.githubusercontent.com/alexiacamargo/stranger-things-landing-page/main/assets/images/banner/logo.svg" alt="Logo">
</p>

-------
A **Landing Page: Mundo Invertido** é uma página interativa que apresenta um universo alternativo inspirado no tema "Mundo Invertido" da série Stranger Things. Com um design vibrante e envolvente, a página utiliza elementos visuais cativantes e uma tipografia impactante para criar uma experiência imersiva para os visitantes. 

Este projeto foi criado como parte do bootcamp da DIO durante o Desafio Semana Front-End.

## 💻 Tecnologias
- HTML
- CSS
- JavaScript

## 🎨 Variáveis do Tema CSS
```css
/*** VARIABLES & THEMES ***/

:root {
  --primary-color: #cf0f0f;
  --primary-color-contrast: #ffffff;
  --field-background-color: #000;
}

.light-theme {
  --page-background: linear-gradient(
    180deg,
    #ffffff 0%,
    #ffffff 65%,
    rgba(255, 255, 255, 0.75) 100%
  );
  --header-background-color: #e3e3e3;
  --highlight-color: #000000;
  --featured-font-family: "Archivo", sans-serif;
  --character-top-image-src: url("../images/characters/kids-on-the-bike.svg");
  --character-top-image-color: #ffffff;
  --character-bottom-image-src: url("../images/characters/inverted-world-monster.svg");
  --character-bottom-image-color: #e5e5e5;
  --background-lamp-image: url("../images/backgrounds/lamps.png");
  --footer-background-color: #b5bbbf;
}

.dark-theme {
  --page-background: linear-gradient(
    180deg,
    #050000 0%,
    #130404 65%,
    rgba(19, 1, 1, 0.75) 100%
  );
  --header-background-color: #220f0f;
  --highlight-color: #ffffff;
  --featured-font-family: "Rubik Glitch", sans-serif;
  --character-bottom-image-src: url("../images/characters/kids-on-the-bike.svg");
  --character-bottom-image-color: rgba(255, 255, 255, 0.1);
  --character-top-image-src: url("../images/characters/inverted-world-monster.svg");
  --character-top-image-color: #000;
  --background-lamp-image: url("../images/backgrounds/lamps-inverted.png");
  --footer-background-color: #000;
}
```
