# Doe Sangue! Doe Vida
![](https://img.shields.io/github/languages/count/Danieledias/cadastro-doadores-de-sangue) ![](https://img.shields.io/github/languages/top/Danieledias/cadastro-doadores-de-sangue) ![](https://img.shields.io/github/last-commit/Danieledias/cadastro-doadores-de-sangue)

O projeto DOE é um sistema de cadastro para doadores de sangue, desenvolvido na Maratona Dev pela Rocketseat.

Você sabia que uma simples doação de sangue pode salvar até 3 vidas?
No cenário brasileiro, a doação de sangue não se é uma prática tão corriqueira, apesar de sempre estarmos cientes que a doação de sangue é importante e, vermos várias campanhas, apenas 1.9% da população brasileira realiza a doação de sangue constantemente. Todos os dias são necessárias mais de 38.000 doações para que atenda a demanda dos hemocentros. Sendo assim, este projeto visa proporcionar o alcançe à mais pessoas por ser disponível na web e, maior facilidade para encontrar os tipos sanguíneos podendo entrar em contato com a pessoa via e-mail quando necessitar de doações de um determinado tipo.


![](https://github.com/Danieledias/cadastro-doadores-de-sangue/blob/main/doe.png?raw=true)

## Tecnologias
- HTML (estrutura);
- CSS (estilo);
- JavaScript (inteligência);
- Node.js (sevidor, motor de JavaScript);
- PostgreSQL (banco de dados).

## Execução
1. Faça o clone do repositório;
2. Instale as dependências do projeto npm install;
3. Rode o servidor com npm start ou nodemon server.js.


## Dependências
- express (framework para o node.js);
- nodemon (realiza auto-restart da aplicação ao salvar um arquivo modificado);
- nunjucks (template engine que permite manipular os conteúdos html de maneira mais fácil, intuitiva e dinâmica);
- pg (permite conexão com o banco de dados)

Você precisará instalar todas as dependencia do projeto encontradas no arquivo packge.json

para Instalar use o comando
```javascript
$ npm install {nome da dependencia}

```
na pasta raiz do projeto


## Instalação do Bando de Dados
Baixe no site oficial e instale o PostgreSQL

Baixe e instale o cliente visual PostBrid para manipular os bancos e as tabelas.
- crie um banco de dados chamado "doe"
- crie uam tabela chamada "donors"
- adcione 3 campos do tipo texto ('name','email','blood')

Configure com os dados do banco no arquivo server.js
```javascript
const db = new pool({   
user: 'postgres',   //seu nome de usuario    
password: '0000',   //seu password cadastrado    
host: 'localhost',  //host de acesso ao banco de dado    
port: 5432,         //a porta de comunicação com o BD    
database: 'doe'     //o nome do banco de dados criado
})
```
📝 Esse projeto está sob a licença MIT.
