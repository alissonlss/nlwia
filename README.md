<h1 align="center"> Shorts Summary </h1>

<p align="center">
Evento exclusivo e gratuito, promovido pela Rocketseat para ensino de tecnologias WEB.
</p>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como Executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

![banner](https://github.com/alissonlss/nlwia/assets/113796754/ecbf4827-00f5-45e0-8ce8-4f3e1613e8bd) 


## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:
- HTML e CSS
- JavaScript
- Node.js
- Vite
- Biblitecas e pacotes adicionais:
  `Axios` `Cors` `FFmpeg` `node-wav` `ytdl-core` `Lucide Icons`


## 💻 Projeto

Shorts Summary consiste em uma aplicação que utiliza IA para realizar a transcrição e resumo de vídeos Shorts do Youtube.


## 🧑‍💻 Como Executar

Você deve ter o `Node.js` instalado. Caso não tenha, [clique aqui e faça a instalação](https://nodejs.org). Depois, siga os seguintes passos:

- Clone este projeto, executando o seguinte comando:
  
  ```properties
  git clone https://github.com/alissonlss/nlwia.git
  ```
  
  _Você também pode baixar o arquivo em zip._
  
- Para entrar na pasta do projeto e instale as dependências necessárias execute:
  ```properties
  cd nlwia
  npm i
  ```
  
- Após concluir a instalação, inicie o servidor front-end local com:
  ```properties
  npm rum web
  ```
  _Acesse a aplicação no link que aparecer no console, podendo ser a seguinte: [`http://localhost:5173`](http://localhost:5173)._
  
- Abra um segundo terminal e inicie o servidor back-end com:
  ```properties
  npm rum server
  ```
  _Em caso de aparecer um erro no console indicando problema com o env, abra o package.json e troque o server para isso daqui:_
  
  > `"server":"set YTDL_NO_UPDATE=1 && node --watch --no-warnings server/index.js"`
  
  _E execute o comando anterior de novo._


## ✨ Layout

Você pode visualizar o layout do projeto através [DESSE LINK](https://www.figma.com/file/vPEY0k9wm9t8Ysf9SbqsfV/Shorts-Summary-%E2%80%A2-Trilha-Foundations). É necessário ter conta no [Figma](https://figma.com) para acessá-lo.


## :memo: Licença

Esse projeto está sob a licença [MIT](https://github.com/alissonlss/nlwia/blob/main/LICENSE).
