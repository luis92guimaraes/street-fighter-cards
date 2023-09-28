# Street Fighter Project


#### Esse projeto foi realizado com a mentoria do @Devemdobro, foi meu primeiro contato real com a programação e foi extremamente gratificante realiza-lo. O Projeto foi criado com as ferramentas HTML, CSS e JavaScript.

## Índice

- [Capturas de telas](#capturas-de-telas)
- [Links](#links)
- [Construído com](#construído-com)
- [O que aprendi](#o-que-aprendi)
- [Desenvolvimento contínuo](#desenvolvimento-contínuo)
- [Recursos úteis](#recursos-úteis)
- [Luis Fernando Guimaraes](#autor)

### Capturas de telas

#### Tela Desktop

<img src="./src/github/desktop.gif" alt="Tela desktop exibindo funcionalidades">

#### Tela Ipad

<img src="./src/github/ipad.gif" alt="Tela tablet exibindo funcionalidades">

#### Tela Mobile

<img src="./src/github/mobile.gif" alt="Exibindo responsividade no mobile">

### Links

- Site URL: https://luis92guimaraes.github.io/street-fighter-project/

### Construído com

<div style="display: inline_block"><br>
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">  
  <img align="center" alt= "Javascript" height="30" width="40" src=https://raw.githubusercontent.com/jmnote/z-icons/master/svg/javascript.svg     
</div>

### O que aprendi

Esse foi o meu primeiro projeto e primeiro contato real com a programação. Aprendi conceitos muito importantes de cada uma das ferramentas que utilizei no projeto como por exemplo utilizar o Hover e o uso correto do Flex pasra posicionar de forma correta os cards na página. Fez com que eu realmente entrasse de cabeça na área da tecnologia e me incentivou a buscar aprender cada vez mais e me tornar um ótimo Dev.

## Trechos de códigos

```
main {
    padding: 25px;
}

main .lista-streetfighters {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    justify-content: center;
}

main .cartao-streetfighters {
    display: flex;
    background-image: linear-gradient(to bottom, hsla(210, 100%, 56%, 0.756), hsla(203, 92%, 75%, 0.767), hsla(0, 0%, 100%, 0.718));
    width: 222px;
    padding: 15px;
    flex-direction: column;
    align-items: center;
    gap: 15px;
    border-radius: 15px;
}

.modo-escuro .cartao-streetfighters {
    background-image: linear-gradient(to bottom, hsla(282, 100%, 41%, 0.84), #e6e6fad9);
    color:#f5f5f5;
} 

.modo-escuro .cartao-streetfighters:hover {
    background-color: darkmagenta;
}
main .cartao-streetfighters:hover {
    background-color: #0000CD;
    transform: scale(1.02);
    cursor: pointer;
    transition: 0.2s ease-in-out;
}

main .cartao-streetfighters .informacoes {
    display: flex;
    justify-content: space-between;
    border: 2px solid #333333;
    border-radius: 8px;
}

main .cartao-streetfighters .informacoes span {
    padding: 5px;
    text-transform: uppercase;
    font-size: 17px;
}

main .cartao-streetfighters .gif {
    width: 100px;
    height: 100px;
}

main .cartao-streetfighters .origem-estilo {
    display: flex;
    gap: 20px;
    border-radius: 10px;
}

```

### Desenvolvimento contínuo

Pretendo continuar focado em construir um conhecimento sólido nessas linguagens. Ainda há muitos conceitos importantes para serem desenvolvidos. Estou buscando diariamente de forma gradativa aprender e me desenvolver cada vez mais.

### Recursos úteis

- [Mdn](https://developer.mozilla.org/en-US/) - O Mozilla Developer Network (MDN) desempenha um papel crucial ao fornecer recursos abrangentes e atualizados para desenvolvedores web em todo o mundo.
- [W3School](https://www.w3schools.com/css/default.asp) - Esse site sempre me ajuda a resolver qualquer problema relacionados a códigos de uma maneira fácil e muito rápida.
- [Dev em Dobro](https://www.youtube.com/@DevemDobro) - Este é um canal onde encontro muito material. Tem muito conteúdo relacionado ao desenvolvimento. Recomendo a todos que querem aprender sobre esse e outros conceitos relacionados.

## Autor

[Luis Fernando Guimarães](https://www.linkedin.com/in/luisfguimaraes/)