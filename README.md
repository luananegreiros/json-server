# Desafio

Modelar uma API com [json-server](https://github.com/typicode/json-server) que represente os posts do [Better Programming](https://betterprogramming.pub/archive), onde cada post possui as informações necessárias para preencher as regiões a seguir:

- autor
- foto do autor
- data do post
- título do post
- descrição
- imagem

Crie 3 posts, sendo 2 posts de um mesmo autor.

<br>

## Critérios de sucesso do desafio

1. Usando o [Tabbed Postman](https://chrome.google.com/webstore/detail/tabbed-postman-rest-clien/coohjcphdfgbiolnekdpbcijmhambjff/related?hl=pt-br) ao realizar um GET para [http://localhost:3000/posts](http://localhost:3000/posts), deverá retornar 3 posts, sendo 2 do mesmo autor


2. Usando o [Tabbed Postman](https://chrome.google.com/webstore/detail/tabbed-postman-rest-clien/coohjcphdfgbiolnekdpbcijmhambjff/related?hl=pt-br) ao realizar um GET para [http://localhost:3000/authors](http://localhost:3000/authors), deverá retornar 2 autores.

<br>

<h2> 3. Considerando nosso cenário de uma api de posts, o que as seguintes requisições HTTP fazem? </h2>

<h3> GET http://localhost:3000/posts/1 </h3>

GET solicita ao servidor os dados do objeto de id 1, localizada na rota posts.

<h3>  2. DELETE http://localhost:3000/posts/1 </h3>

Nesse caso, serão deletados os dados do objeto de id 1, da rota posts. 

<h3> 3. POST [http://localhost:3000/posts](http://localhost:3000/posts) </h3>

Será criado um objeto dentro da rota posts, com suas as propriedades e valores.

<br>

<h2> 4. Qual a diferença entre PUT e PATCH? </h2>

- 

<br>

<h2> 5. Segundo a documentação do json-server e considerando a modelagem que você fez, qual seria a requisição necessária para retornar todos os posts de um determinado autor? </h2>

- 