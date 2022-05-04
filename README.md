# app_tempo.css
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;300&display=swap');

body, button, input, select, textarea {
    font-family: 'Poppins', sans-serif;
}

* {
    box-sizing: border-box;
}

html {
    margin: 0%;
}

:root {
    --dark-blue: #1d1d1d;  /* fundo preto do celular */
    --light-grey: #bfbfc1;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
    /* height: 100px; a linha no centro conforme o tamanho da tela */
}

h2, h4 { /*aproxima eles */
    margin: 5px;
}

h4 {
    font-weight: 300; /*muda a fonte do h4*/
} 

h1 {
    font-size: 80px; /*meche no espaço da font*/
    margin: 0%;

}

.iphone-container { /* div pai*/
    width: 350px;
    height: 700px;
    background: var(--dark-blue);
    border-radius: 45px;
    border: 20px solid #111;
    position: relative;
    color:  #fff;
    text-align: center;
    padding: 60px 10px 20px;
}

.iphone-container .notch { /*div pai--> notch*/
    width: 180px;
    height: 25px;
    background: #111;
    border-radius: 0 0 30px 30px;
    position: absolute;
    top: 0%;
    left: calc(50% - 90px);
}

.iphone-container .iphone-menu { /*div pai --> div do .iphone-container*/
    width: 90px;
    background: var(--light-grey);
    height: 2px;
    border-radius: 8px;
    position: absolute;
    bottom: 20px;
    left: calc(50% - 45px);
}

.iphone-container svg { /*svg serve para acessar o figura ou icones*/
    width: 100px;
    height: 100px;
    margin: 40px 0 20px;
}

.iphone-container .week-weather {
    color: var(--light-grey);
    margin-top: 60px;
    padding: 0 20px; /*definiu a posição exata*/
    text-align: left; /*mudou para o lado*/
    display: grid; /*separo as span*/
    grid-template-columns: 3fr 1fr;
    grid-row-gap: 1rem; /*separo as span*/
}
