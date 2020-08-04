<h3 align="center">
	<img width="300px" src=".github/logo.svg" alt="Proffy"/>
  <br/>
	<span>
		Uma aplicação que conecta pessoas que querem aprender com pessoas dispostas a ensinar!
	</span>
</h3>


# Indice 
- [Sobre](#sobre)
- [Tecnologias usadas](#tecnologias)
- [Resultados](#resultados)
- [Como usar?](#comousar)

<a id="sobre"></a>
## :bookmark: Sobre
<p>
Este repositório contém o backend desenvolvido para a aplicação Proffy, um projeto desenvolvido a partir da trilha <b>omnistack</b> ao longo da semana da 2ª edição do evento <b>Next Level Week</b>, evento promovido pela <a href="https://rocketseat.com.br">Rocketseat</a> que aborda diversos conteúdos relacionados a programação. A ideia do aplicativo é fornecer uma interface web que permita que usuários cadastrem sua disponibilidade para ensinar ou vejam pessoas que possam ensiná-lo nos mais variados assuntos.
</p>

<a id="tecnologias"></a>
## :rocket: Tecnologias
<p>
Este projeto foi desenvolvido utilizando-se das tecnologias abaixo:
</p>

- TypeScript
- Node.js
- Express
- Knex.js

<a id="resultados"></a>
## :heavy_check_mark: Resultados
<p>Ainda em progresso!</p>

<a id="comousar"></a>
## :fire: Como usar?
<p>Para executar este projeto em sua máquina local existem alguns requisitos básicos. Você deve ter o Node.js instalado na sua versão mais recente e um gerenciador de pacotes Yarn ou NPM.</p>

Clone este repositório
```sh 
git clone https://github.com/higorpo/proffy-backend.git
```

Instale as dependências do projeto
```sh 
yarn
```

Crie o banco de dados
```sh 
yarn knex:migrate
```

Inicie o servidor
```sh 
cd ../web
yarn start
```
