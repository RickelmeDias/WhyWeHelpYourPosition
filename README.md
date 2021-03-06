<h1 align="center">๐ค WHY WE HELP YOUR POSITION ๐</h1>

</br>

<div align="center"><img src="./assets/logo_whywehelpyourposition.png" /></div>

<h3 align="center"> ENGLISH </h3>

> This API was created for a challenge by me (Rickelme), the API searches for the customer's website on google and returns an email to the same informed if he has a good position in the search engine.

<h3 align="center"> PORTUGUรS </h4>

> Essa API foi criada para um desafio por mim (Rickelme), a API busca pelo site do cliente no google e retorna um e-mail para o mesmo informado se ele tem uma boa posiรงรฃo no buscador.

</br>
<div align="center">

<h3> Techs: </h3>
<img src="https://img.shields.io/badge/Nodejs-black?&logo=Node.js&logoColor=green" />
<img src="https://img.shields.io/badge/Typescript-black?&logo=typescript&logoColor=blue" />
<img src="https://img.shields.io/badge/Express-black?&logo=Express&logoColor=white" />
<img src="https://img.shields.io/badge/SQLite-black?&logo=SQLite&logoColor=blue" />
<img src="https://img.shields.io/badge/Jest-black?&logo=Jest&logoColor=red" />
<img src="https://img.shields.io/badge/Supertest-black?&logo=&logoColor=green" />
<img src="https://img.shields.io/badge/TypeORM-black?&logo=&logoColor=green" />
<img src="https://img.shields.io/badge/MailTrap-black?&logo=&logoColor=green" />
<img src="https://img.shields.io/badge/TDD-black?&&logoColor=green" />
<img src="https://img.shields.io/badge/Basic SOLID/CLEAN CODE-black?&logo=&logoColor=green" />

</br>
<h3> Design: </h3>
<img src="https://img.shields.io/badge/HTML-black?&logo=html5&logoColor=red" />
<img src="https://img.shields.io/badge/CSS-black?&logo=css3&logoColor=blue" />
<img src="https://img.shields.io/badge/Canva-black?&logo=canva&logoColor=blue" />

</div>

</br>
<hr/>
</br>

## ๐ค ABOUT THE IDEA ๐ค

๐ค [QUAL A IDEIA DO PROJETO?](#ideia-do-projeto)


</br>

## ๐ DOCUMENTATION ๐

๐ [DOCUMENTACAO EM PORTUGUES](#DOCUMENTACAO-EM-PORTUGUES)


</br>

## ๐ RESULTS ๐

๐ [RESULTADOS DO PROJETO](#resultados-do-projeto)


</br>
<hr/>
</br>

## IDEIA DO PROJETO

### Trazer interatividade com o cliente
O projeto tem a ideia de trazer mais interatividade do cliente com a HubLocal, empresa que propรดs os desafio, seguindo com o tema proposto:

>" Explique por que as empresas devem ter a acesso e serem clientes da HubLocal "

### Como trazer interatividade com o cliente?
Para trazer essa interatividade HubLocal e Cliente, a API **WHY WE HELP YOUR POSITION**, faz uma anรกlise de acordo com os dados enviados pelo cliente sobre a posiรงรฃo dele hoje na web. Essa API busca pelo site do cliente atravรฉs de duas palavras chave digitadas.

### Qual a importรขncia dessa interatividade?
ร nesse momento que entra o diferencial da API e sua interatividade com o cliente. O cliente visualizando toda inteligรชncia por trรกs do sistema de identificar o posicionamento digital de seu negรณcio, logo percebe a importรขncia que estar bem posicionado traz para o negรณcio.

### Como fazemos a interatividade?
Para o cliente visualizar essa importรขncia, รฉ enviado em poucos segundos, apรณs a consulta do serviรงo, um e-mail personalizado de acordo com a posiรงรฃo atual do cliente no mapa digital (atravรฉs de buscador, como o Google).

### Porque esse serviรงo torna a experiรชncia do cliente interessante?
A API recebe apenas 5 campos, o que torna a experiรชncia do usuรกrio (cliente) muito simples e dinรขmica, alรฉm de receber um e-mail personalizado e bem formatado. Os campos que o cliente deve digitar sรฃo campos bastante diretos e ao mesmo tempo flexiveis, isso faz com quel o cliente completar as etapas e se aproximaar mais da hub, pois ele tambรฉm fica interessado em saber seu posicionamento digital.

### Como esse e-mail fortace os laรงos com o cliente?
Nesse e-mail vai uma breve explicaรงรฃo sobre o porque o cliente precisa ter uma localizaรงรฃo digital bem controlada e definida, consequentemente o porque deve fazer parte da HubLocal, em baixo tem um botรฃo para levar diretamente a uma pรกgina de interesse da HubLocal, como um atendimento direto ou sua pรกgina princial.

</br><hr/></br>

## DOCUMENTACAO EM PORTUGUES

</br>

## Configuraรงรตes iniciais para rodar o serviรงo
Esse projeto de API รฉ um projeto node, onde foi utilizado o yarn, entรฃo รฉ fundalmente fazer a instaรงรฃo do yarn.

### Configurando Yarn
Instale o yarn:

```sh
npm install --global yarn
```

Apรณs instalar o yarn, faรงa a instalaรงรฃo de todos as dependencias do projeto, usando o comando:

```sh
yarn install
```

### Configurando MailTrap
Esse projeto utiliza o `mailtrap` para fazer os testes e envio de e-mail, entรฃo รฉ fundamental ter uma conta no `https://mailtrap.io/` para esse serviรงo funcionar de forma adequada.

Apรณs criar sua conta no **Mailtrap**, crie um arquivo ambiente chamado: `.env`,
esse arquivo receberรก as credenciais de login do serviรงo.

### Configurando .env
```env
MAIL_USER=myUser123
MAIL_PASS=myPass123
```

Onde obter as credenciais? Clique na seta abaixo:

<details>
<img src="./assets/documentation_images/mailtrap_credentials.png">
</details>
</br>

### Configurando porta do serviรงo
Se vocรช estiver utilizando a porta **3334** do seu sistema, aconselho mudar a porta dessa API no arquivo `server.ts`.

</br><hr/></br>

## Banco de dados

Para que o projeto funcione em mais ambientes e sempre precisar ficar instalando diversos outros sistemas, utilizei o **SQLite**, pois jรก funciona bem para o desenvolvimento e demonstraรงรฃo.

Esse banco de dados nรฃo requer uma porta e nenhum software previamente instalado, porรฉm precisamos criar o arquivo de banco de dados `db.sqlite`, como foi nomeado nesse projeto, para criar o arquivo jรก deixei pronto um script no node, basta executar:

```sh
yarn migrations
```

Se tudo der certo vocรช terรก um arquivo `db.sqlite` na pasta `/data`.

</br><hr/></br>

## Executando os testes

Foi aplicado no projeto conceitos SOLID/Clean Code que venho estudando, tambรฉm apliquei TDD, que sรฃo os testes de funcionalidades, caso tenha interesse vocรช pode executar os testes e saberรก se estรก tudo funcionando como deveria.

Esse teste, testarรก inclusive sua autenticaรงรฃo do serviรงo **mailtrap**, enviando uma mensagem de teste. Para executar os testes automatizados, basta digitar em seu terminal:

```sh
yarn test
```

</br><hr/></br>

## Executando o serviรงo por completo

Se conseguimos passar por todas essas etapas sem problemas a API jรก estรก pronta para funcionar, inclusive essas funcionalidades abaixo deverรฃo funcionar normalmente:

1. Envio de e-mail personalizado
> Esse e-mail estarรก indicando se seu site se encontra bem posicionado no buscador google (E-mail chegarรก no mailtrap);

2. Salvar dados no bando de dados
> Os dados enviados para fazer essa busca no google e o e-mail serรฃo adicionados ao seu banco de dados `db.sqlite`;

Para testar se essas funcionalidades estรฃo funcionando, vamo iniciar o serviรงo com o seguinte comando:

```sh
yarn start
```

</br><hr/></br>

## Enviando a requisiรงรฃo na API

Esse serviรงo possui um unico end-point, que serรก responsรกvel por receber a requisiรงรฃo de busca: `http://localhost:3334/findme`

<table>
<tr>
<td>ENDPOINT</td> <td>http://localhost:3334/findme</td>
</tr>
<tr>
<td>METODO</td> <td>POST</td>
</tr>
<tr>
<td>BODY</td> <td>
    {
        "name": "Rick",
        "email": "email@email.com",
        "first_keyword": "Comprar",
        "second_keyword": "Carro",
        "website_url": "meusite.com"
    }
</td>
</tr>
<table>

```json
    {
        "name": "Rick",
        "email": "email@email.com",
        "first_keyword": "Comprar",
        "second_keyword": "Carro",
        "website_url": "meusite.com"
    }
```

</br><hr/></br>

## Como funciona a API

Ao enviar a requisiรงรฃo, esse serviรงo irรก pegar as keywords, fazer uma busca na primeira pรกgina do google pelo seu website, se ele encontrar na primeira pรกgina significa que vocรช possuรญ um bom posicionamento e รฉ possivel ajudar a mantรช-lo!

Caso nรฃo tenha encontrado na primeira pรกgina, vocรช deverรก estar entre as prรณximas, isso nรฃo รฉ tรฃo bom para o posicionamento digital, entรฃo podemos ajudar a melhorar.

</br><hr/></br>

## Resultados do projeto

Abaixo irei mostrar os resultados do projeto, por exemplo: Imagens do e-mail enviado (as **2** personalizaรงรตes, mas รฉ possรญvel fazer **n** e-mails personalizados), Print do banco de dados armazenando as informaรงรตes da requisiรงรฃo e o terminal do TDD.

</br>

Primeiro iniciei o serviรงo `yarn start` e agora vem os resultados:

</br>

### Requisiรงรฃo para o end-point do serviรงo

Essa requisiรงรฃo eu fiz com suas chaves bem especificas para encontrar meu portfolio na primeira pรกgina de pesquisa.
<details>
    <img src="./assets/results_image/01-post-good-position.png" />
</details>

A requisiรงรฃo foi um sucesso, logo o email chegou.

</br>

### E-mail que chegou para meu posicionamento em relaรงรฃo essas chaves.

<details>
    <img src="./assets/results_image/02-mailtrap-message.png" />
</details>

Esse foi o e-mail enviado pelo serviรงo e recebido pelo cliente.
Como o e-mail foi enviado, os nossos dados de consulta devem estar no banco de dados SQLite armazenado.

</br>

### Resultado no banco de dados SQLite.
<details>
    <img src="./assets/results_image/03-database-archive.png" />
</details>

</br>

Como foi possivel observar funcionou direitinho, agora รฉ a sua hora de testar a outra mensagem! ๐๐๐ป

Estou a disposiรงรฃo para ajudar com o que for necessรกrio, qualquer dรบvida sรณ buscar meu contato atravรฉs do meu perfil do Github.

</br><hr/></br>

## Developer / Desenvolvedor

> Developer who created this project. ๐

<div align="center">
<p align="center">
<img src="https://avatars.githubusercontent.com/u/43411893?s=400&u=c1a306f43d649c6c7e92cda85709ba604b20406b&v=4" width=115><br>
<a href="https://github.com/RickelmeDias">Rickelme Dias</a>
</p>
<div>