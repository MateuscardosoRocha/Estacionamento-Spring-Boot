<h1>CRUD de Estacionamento de Carros em Apartamento</h1>
<p>Este é um projeto de CRUD (Create, Read, Update, Delete) desenvolvido em Spring Boot e Postgres, para gerenciar um estacionamento de carros em um prédio residencial.</p>

<h2>Configuração do Banco de Dados</h2>
<p> Antes de executar o projeto, é preciso configurar o banco de dados. Para isso, crie um banco de dados Postgres com o nome "parking-control-db" e execute o script </p>

<h2>Execução do projeto</h2>
<p>Clonando o repositório</p>
<p>git clone https://github.com/seu-usuario/nome-do-repositorio.git</p>
</br>

<p>Configure as propriedades do banco de dados no arquivo "src/main/resources/application.properties":<p>
<p>spring.datasource.url=jdbc:postgresql://localhost:5432/parking-control-db</p>
<p>spring.datasource.username=postgres<p>
spring.datasource.password=sua-senha

<br><br>

Acesse a aplicação em http://localhost:8080



<h2>Endpoints</h2>
<p><b>GET</b>  http://localhost:8080/parking-spot: lista todos os carros cadastrados<br></p>
<p><b>GET</b>  http://localhost:8080/parking-spot/ID: retorna os dados de um carro específico<br></p>
<p><b>POST</b>  http://localhost:8080/parking-spot: cadastra um novo carro<br></p>
<p><b>PUT</b>  http://localhost:8080/parking-spot/ID: atualiza os dados de um carro específico<br></p>
<p><b>DELETE</b>  http://localhost:8080/parking-spot/ID: remove um carro específico<br></p>

