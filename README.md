# Desenvolvendo Sites Responsivos com Bootstrap 4

### Objetivo

Desenvolvimento de Currículum Online para o participante, no formato de Site Responsivo, utilizando o Bootstrap como framework front-end e hospedá-lo no [Github Pages](https://pages.github.com/).

![Personal Page](img/estrutura-da-pagina.jpg)

### Pré-requisitos para o Minicurso:

1. Criar uma conta no [Github](https://github.com).
2. Dê um fork neste repositório.
3. Crie um arquivo _.html_ com o seu nome na raiz do projeto.

### Cabeçalho

### HTML
    <div class="container">
      <div class="row cabecalho">
        <div class="col-sm-3">
          <div class="mainimage"></div>
        </div>
        <div class="col-sm-8">
          <h1>JHON DOE</h1>
          <h3 style="font-weight: 100;">Programmer</h3>
          <hr>
          <h3>About Me</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </div>
      </div>
    </div>

### CSS

    :root {
      --preto:   #5B5A5A;
      --cinza:   #C0B7AD;
      --amarelo: #F6D00A;
    }

    .mainimage {
      width: 256px;
      height: 256px;
      margin: 0 auto;
      background: url(../img/avatar.png);
    }

    .cabecalho {
      color: var(--white);
      padding: 10px 0 10px 0;
      background-color: var(--preto);
      border-bottom: 5px solid var(--amarelo);
    }

    hr {
      height: 5px;
      color: var(--amarelo);
      background-color: var(--amarelo);
    }
