# Portfólio digital de Eduardo da Silva Fontes

<p align="center">
    <img src="mgt/Eu.jpeg" alt="Eduardo Fontes" width=50% ali></img>
</p>

## Tecnologias utilizadas:
<div align="center">
<img src="https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white&color=ffa500">
<img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white&color=0496c7">
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white&color=4c4c4c">
<img src="https://img.shields.io/badge/Python-00000?style=for-the-badge&logo=Python&logoColor=white&color=0496c7">
<img src="https://img.shields.io/badge/Bootstrap-00000?style=for-the-badge&logo=Bootstrap&logoColor=white&color=7e3887">
</div>

## Portfólio Digital:

### Versão Desktop:
<img src="/mgt/Portfolio-DigitalDesk.gif">

### Versão Mobile:
<img src="/mgt/Portfolio-DigitalMob.gif" width="460px" height="813px">


## Como Rodar
> _Este documento terá as informações necessárias para que você consiga rodar a aplicação devidamente._
## Tutorial de Instalação:

1. [Git](https://git-scm.com/downloads): Utilize o git para poder clonar o repositório.

2. [Python](https://www.python.org/downloads/): Será necessário o python para rodar o ambiente virtual, e será por meio dele, utilizado o Microframework Flask, que está incluso no requirements.txt

## Na prática:

<details>
  <summary><b>Clonando Repositório</b></summary>

  Para clonar o projeto e utilizá-lo em seu computador, siga os seguintes passos:
  
  1. Crie uma pasta onde deseja armazenar nosso projeto, e então abra-a e clique no url da pasta, após isto, escreva em cima do url `cmd`, para abrir o prompt de comando. E então execute o comando abaixo:
  
  > _Obs.: Caso você esteja no LINUX, a parte de escrever "cmd" não irá funcionar, então clique com o botão direito na pasta que você criou e selecione a opção "Abrir no terminal"_

  
  ```
  git clone https://github.com/DuuhZero/PortfolioDigital.git
  ``` 

</details>
<br>

<details>
  <summary><b>Instalando Ambiente Virtual</b></summary>

  1. Após a clonagem, clique com o botão direito em cima da pasta "api", após isto selecione a opção de abrir com o Terminal, e insira os seguintes comandos :

  ```
  python3 -m venv venv
  venv\Scripts\activate
  pip install -r requirements.txt
  ```

  > _Caso você esteja em LINUX, digite os comandos desta maneira:_<br>
  `python3 -m venv venv`<br>
  `source venv/bin/activate`<br>
  `pip install -r requirements.txt`

</details>
<br>

<details>
  <summary><b>Executando Aplicação</b></summary>

  1. Ainda dentro do ambiente virtual, execute o seguinte comando:
  ```
  flask run
  ```
  > _Também é possivel executar pelo próprio arquivo app.py, onde no seu editor de texto você seleciona:_<br>
  `Executar Arquivo do Python`<br>
  ou<br>
  `"Clique no botão de play "▶️"`<br>

  2. Por fim, entre no link que aparecerá no cmd copiando e colando ele no seu navegador de preferência.

  3. Após finalizar o uso do nosso site, para sair do ambiente virtual, no terminal, execute o atalho `Ctrl+C` para finalizar o serviço do Flask, e então execute o seguinte comando:
  ```
  deactivate
  ```

</details>
