# desafio-siapesq-estagio-2024-1

Prazo: 02/05/2024
## Frontend

Desenvolva uma aplicação web utilizando React e Leaflet que exiba um mapa interativo com marcadores de diferentes locais. Cada marcador deve exibir um popup contendo informações sobre o local, como nome, descrição e as coordenadas.

### Requisitos:

* A aplicação deve ser desenvolvida utilizando React e Leaflet.
* É necessário ter uma tela para cadastrar usuário e uma tela de login
* O mapa só pode ser acessado aṕos o usuario fazer o login
* O mapa deve ser centrado em uma localização inicial específica (Rio Grande)
* Deve ser possivel adicionar e excluir um local
* Ao clicar em um marcador, um popup deve ser exibido contendo informações sobre o local correspondente.
* O código deve ser organizado e limpo, seguindo as boas práticas de desenvolvimento.

## Backend 
  Desenvolva uma REST API que sirva os casos de uso da aplicação frontend
### Requisitos:
* Endpoints:
  * Para cadastro de usuários(nome,email,senha)
  * Para realizar login
  * Utilize JWT para bloquear usuários não logados de acessarem as rotas protegidas
  * **Rotas Protegidas por Token**:
    * Para cadastro de local(nome,descrição,latitude,longitude)
    * Para deletar local
    * Para listar locais
  * Utilize um banco de dados relacional(postgresql,mysql,etc)

### Entrega
* Faça uma fork desse projeto e criei uma branch com o seu nome e sobrenome(exemplo: patrick-souza)

* **Lembre-se de colocar um readme.md explicando como rodar o projeto** 

* Siga o padrão do [**EXEMPLO**](https://github.com/PatrickFS18/desafio-siapesq-estagio-2024-1)
  
### Dúvidas
Em caso de dúvida abra um issue no repositório do desafio






