
<h1 align="center">Landing Page GTA</h1>  


 
 [![NPM](https://img.shields.io/npm/l/react)](https://github.com/tedoidobr/Landing-Page-GTA/blob/main/LICENSE)

Este é um projeto de uma landing page para o jogo Grand Theft Auto V e GTA Online, 

desenvolvido como um exercício de
<img align="center" alt="HTML" height="15" width="25" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">HTML, <img align="center" alt="CSS" height="15" width="25" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">CSS   e <img align="center" alt="Js" height="15" width="25" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">JS .

 <h2 align="center">Objetivo</h2> 

O objetivo deste projeto é criar uma página web que apresente o jogo GTA V e GTA Online, mostrando as suas características, os seus gráficos, as suas plataformas disponíveis e o seu link de compra.

## Tecnologias utilizadas

- HTML<img align="center" alt="HTML" height="15" width="25" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">: linguagem de marcação para estruturar o conteúdo da página
- CSS<img align="center" alt="CSS" height="15" width="25" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">: linguagem de estilo para definir a aparência e o layout da página
- JS<img align="center" alt="Js" height="15" width="25" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">: JavaScript é uma linguagem de programação que permite criar conteúdo dinâmico e interativo em páginas web
- Fonte Chalet: fonte personalizada para o título e o texto da página, obtida do site https://fonts.cdnfonts.com/css/chalet
- Imagens: imagens do jogo e dos seus logos, obtidas da pasta src/imagens

<h2 align="center"> Estrutura do código </h2> 

O código HTML está dividido em três partes principais: o cabeçalho, o corpo e o rodapé.

- O cabeçalho contém a tag `<head>`, que define as informações gerais da página, como o título, a codificação, o favicon, os links para as fontes e os arquivos CSS.
- O corpo contém a tag `<body>`, que define o conteúdo principal da página, dividido em três seções: o cabeçalho, o conteúdo e o rodapé.
    - O cabeçalho contém a tag `<header>`, que define a área superior da página, com o logo da Rockstar Games, o logo do GTA V, o menu de navegação e o link para o suporte.
    - O conteúdo contém a tag `<main>`, que define a área central da página, com a imagem de fundo, o logo do GTA Online, o título, o texto e o botão de compra.
    - O rodapé contém a tag `<footer>`, que define a área inferior da página, com o logo da Rockstar Games, o texto de direitos autorais e os ícones das redes sociais.
- O rodapé contém a tag `<script>`, que define o código JavaScript para adicionar algumas funcionalidades à página, como o efeito de parallax na imagem de fundo e o scroll suave nos links de navegação.
- O O código JS tem apenas 4 linhas. As seguintes funções, vamos ver cada linha do código:
  - A primeira linha declara uma constante chamada botao e atribui a ela o resultado da função document.querySelector(".btn-plataforma"). Essa função seleciona o primeiro elemento HTML que tenha a classe btn-plataforma e retorna uma referência a ele. Nesse caso, o elemento é um botão que mostra as plataformas disponíveis para o jogo.
  - A segunda linha declara uma constante chamada elementoPlataformas e atribui a ela o resultado da função document.querySelector(".btn-plataforma .plataformas"). Essa função seleciona o primeiro elemento HTML que tenha a classe plataformas e que seja descendente do elemento com a classe btn-plataforma. Nesse caso, o elemento é uma lista não ordenada ( ul ) que contém os itens ( li ) com as imagens das plataformas.
  - A terceira linha usa o método addEventListener para adicionar um evento de clique ao elemento botao. Esse método recebe dois argumentos: o tipo do evento ("click") e uma função que será executada quando o evento ocorrer (() => {elementoPlataformas.classList.toggle("ativo");}). Essa função é uma função de seta, que é uma forma concisa de escrever funções em JavaScript.
  - A quarta linha usa o método classList.toggle para alternar a classe ativo no elemento elementoPlataformas. Esse método recebe um argumento: o nome da classe ("ativo"). Se o elemento já tiver essa classe, o método a remove. Se o elemento não tiver essa classe, o método a adiciona. Essa classe é definida no arquivo CSS e tem um efeito de mostrar ou esconder o elemento, usando a propriedade display.
- Portanto, o que esse código faz é o seguinte: quando o usuário clica no botão de plataformas, ele verifica se a lista de plataformas está visível ou não. Se estiver visível, ele a esconde. Se estiver escondida, ele a mostra. Isso cria um efeito de abrir e fechar o menu de plataformas.

<h2 align="center"> Instruções de uso</h2> 

Para usar este projeto, você precisa ter um navegador web atualizado e um editor de texto de sua preferência. Você pode seguir os seguintes passos:

- Faça o download ou o clone deste repositório para o seu computador
- Abra a pasta do projeto no seu editor de texto
- Abra o arquivo index.html no seu navegador web
- Aproveite a página e explore os seus elementos

<h1 align="center">Autor</h1> 

[Daniel Angeli](https://github.com/tedoidobr) - Analista de redes. Amante de tecnologia, estudante de programação. Atualmente focado em Java e JavaScript.
<div align="center"> 
  <a href="https://instagram.com/tedoido" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "mailto:tedoido@gmail.com.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/daniel-armindo-angeli-06aa37282/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href="https://github.com/tedoidobr" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>
</div>



## Licença

Este projeto está licenciado sob a 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/tedoidobr/Landing-Page-GTA/blob/main/LICENSE)
