# Ignite_Trilha_ReactJS_Desafio-02_ComponentizacaoDaAplicacao
Ignite ReactJS - Desafio 02 Refatoração da página de listagem de filmes de acordo com o gênero

###


### Execução
Para executar o projeto deve baixar o repositório e usar o comando yarn para baixar as dependências
- no visual studio code, para rodar o projeto yarn server para executar o servidor fake com os movies, genres e / correspondente a home, utilizando a porta 3333
- depois usar o comando yarn dev em outro terminal para abrir o cliente.
- no navegador o cliente estará utilizando a porta localhost:8080 

### Atividades desenvolvidas
- o segundo desafio foi a refatoração de uma página de listagem de filmes
- a estrutura geral veio no template
- o código da sidebar e da listagem de filmes estava no App.tsx, o principal desafio foi separar os códigos para os componentes e depois no App, na chamada da sidebar e da content responsável pela listagem, coloquei uma variável com o id do filme para que ao mudar uma categoria de filme na sidebar(componente filho) o App(pai) percebesse e repassasse a informação do novo id para o componente filho content responsável por listar os filmes de determinda categória.
 

##### Descrição do desafio
- Desafio: Componentizando a aplicação
Nesse desafio iremos dividir uma aplicação em componentes afim de isolar as responsabilidades e facilitar a manutenção do código.


### Tela de execução
<img src="https://github.com/josegcmoraes/Ignite_Trilha_ReactJS_Desafio-02_ComponentizacaoDaAplicacao/blob/main/execucao.png" width="640" height="520">

