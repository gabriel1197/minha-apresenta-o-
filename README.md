<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Gabriel?</title>
    <link
      rel="shortcut icon"
      href="imagens/favicon (1).ico"
      type="image/x-icon"
    />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="container">
      <h1>BEM VINDO A MINHA APRESENTAÇÃO!</h1>
      <h2 class="meio">Quem sou eu?</h2>
      <img
        src="imagens/288274020_554474606120045_7277515280136093546_n00.jpg"
        alt="uma foto minha"
        class="imagem"
      />
      <h2>Minha apresentação!</h2>
      <p>
        meu nome é <strong>luiz gagriel</strong>, eu sou estundade de ciencias
        de tecnologia, estou estudando linguagens de marcações e estou estudando
        linguagens de programações. Atualmente estou estudando na onebitcode!
      </p>
      <div>
        <h2>Linguagens que estudos</h2>
        <ul>
          <li>HTML5</li>
          <li>CSS</li>
          <li>TYPESCRIPT</li>
          <li>JAVASCRIPT</li>
          <li>REACTJS</li>
          <li>SQL</li>
          <li>SASS</li>
          <li>BOOTSTRAP</li>
        </ul>
      </div>
      <div>
        <h2>Meus trabalhos</h2>
        <div class="cards">
          <img
            src="imagens/pexels-cottonbro-3843282.jpg"
            alt="foto de em breve"
          />
          <img
            src="imagens/pexels-alleksana-4271927 (2).jpg"
            alt="foto de em breve"
            width="260px"
          />
          <img
            src="imagens/pexels-cottonbro-3843282.jpg"
            alt="foto de em breve"
          />
        </div>

        <h2>Como me achar?</h2>
      </div>
      <nav>
        <li class="facebook">
          <img src="imagens/icone-facebook.png" alt="icone-facebook" /><a
            href="https://www.facebook.com/luizgabriel.pimentaferreira/"
            rel="external"
            target="_blank"
            >/Luiz Gabriel</a
          >
        </li>
        <li class="github">
          <img src="imagens/icone-github.png" alt="icone-github" /><a
            href="https://github.com/gabriel1197"
            rel="extenal"
            target="_blank"
            >/gabriel1197</a
          >
        </li>
        <li class="linkedin">
          <img src="imagens/icone-linkedin.png" alt="icone-linkedin" /><a
            href="https://www.linkedin.com/in/luiz-gabriel-435610250/"
            rel="external"
            target="_blank"
            >/Luiz Gabriel</a
          >
        </li>
        <li class="twitter">
          <img src="imagens/icone-twitter.png" alt="icone-twitter" /><a
            href="https://twitter.com/LuizGabrielPim5"
            rel="extenal"
            target="_blank"
            >/l_gabriel.88</a
          >
        </li>
      </nav>
    </div>
    
    body {
  font-family: Arial, Helvetica, sans-serif;
  font-size: larger;
  background-color: #b7daf1;
  background-attachment: fixed;
  background-position: 50% right;
  margin-top: 0px;
}

h2,
h1 {
  text-shadow: 1pt 1pt 1pt #fa84d5;
}

.meio {
  text-align: center;
  text-shadow: 1pt 1pt 1pt #fa84d5;
}

.imagem {
  margin-left: 12em;
  box-shadow: 5pt 5pt 5pt;
}

p {
  text-align: center;
  text-align: justify;
}

.container {
  background-color: #fff;
  border-radius: 12pt;
  box-shadow: 5pt 5pt 20pt #ecb8dc;
  width: 600pt;
  margin: auto;
  padding: 80pt;
  font-family: Arial, Helvetica, sans-serif;
  margin-top: -70px;
}

.cards {
  display: flexbox;
  text-align: center;
  margin: 2px 2px 2px 2px;
}

.cards img:hover {
  transform: scale(0.9) translateY(-5px);
  cursor: pointer;
}

nav {
  margin-top: 1em;
  margin-bottom: 1px;
}
