# Desafio 01 - Backend com NodeJs
<div align="center">Projeto criado durante a participação do bootcamp da RocketSeat.🚀</div>
</p>
<div align="center"> <a href="#enunciado">O enunciado</a> | <a href="#funcio">Funcionalidades</a> | <a href="#project">Utilizando o projeto</a> | <a href="#import">Importando um workspace</a> | <a href="#license">License</a> </div>
</p>

Acompanhe meus relatos do bootcamp e plano de estudos em: [Meu Relato](https://www.notion.so/GoStack-Meu-relato-7073f9bd31a6432b9e626e89c663cd2e)

## <a id="enunciado">O enunciado</a>

Deverá ser construído uma aplicação para armazenar repositórios do seu portfólio, que irá permitir a criação, listagem, 
atualização e remoção dos repositórios, e além disso permitir que os repositórios possam receber "likes".
O template da aplicação foi disponibilizado e o desenvolvimento seguiu-se a partir do mesmo.

Mais informações do enunciado: [Enunciado do Desafio 01](https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/desafio-conceitos-nodejs)

## <a id="funcio">Requisitos</a>

* POST /repositories: A rota deve receber title, url e techs dentro do corpo da requisição, sendo a URL o link para o github desse repositório.
Ao cadastrar um novo projeto, ele deve ser armazenado dentro de um objeto no seguinte formato: 
{ id: "uuid", title: 'Desafio Node.js', url: 'http://github.com/...', techs: ["Node.js", "..."], likes: 0 }; 

* GET /repositories: Rota que lista todos os repositórios;

* PUT /repositories/:id : A rota deve alterar apenas o título, a url e as techs do repositório que possua o id igual ao id presente nos parâmetros da rota;

* DELETE /repositories/:id : A rota deve deletar o repositório com o id presente nos parâmetros da rota;

* POST /repositories/:id/like: A rota deve aumentar o número de likes do repositório específico escolhido através do id presente nos parâmetros da rota, a cada chamada dessa rota, o número de likes deve ser aumentado em 1;

Mais informações do enunciado: [Enunciado do Desafio 01](https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/desafio-conceitos-nodejs)

## <a id="project">Utilizando o projeto</a>
Para utilizar o projeto você deverá:
1. Fazer o clone do projeto;
2. Rodar o comando `yarn` no diretório do repositório;
3. Rodar o comando `yarn dev` no diretório clonado;

Pronto! Você pode utilizar a ferramenta que preferir para validar as APIs criadas.

A que eu utilizei foi o [Insomnia](https://insomnia.rest/).

## <a id="import">Importando um workspace</a>

Veja funcionando com o Insonmia importando o arquivo json: **Desafio01 - NodeJs.json** que esta na pasta raiz.

No Insomnia, você deverá: 
1. Criar um novo workspace 
2. Clicar na setinha pra baixo (essa aqui: ) 
3. Clicar em Import/Export
4. Selecionar a opção Import - From file
5. E visualizar as cinco rotas

## <a id="license">License</a>
O projeto possui licença [MIT](https://github.com/andreserudo/repositories_backend/blob/master/LICENSE).
