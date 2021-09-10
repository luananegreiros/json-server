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

<h4>

1. Usando o [Tabbed Postman](https://chrome.google.com/webstore/detail/tabbed-postman-rest-clien/coohjcphdfgbiolnekdpbcijmhambjff/related?hl=pt-br) ao realizar um GET para [http://localhost:3000/posts](http://localhost:3000/posts), deverá retornar 3 posts, sendo 2 do mesmo autor

<br>

2. Usando o [Tabbed Postman](https://chrome.google.com/webstore/detail/tabbed-postman-rest-clien/coohjcphdfgbiolnekdpbcijmhambjff/related?hl=pt-br) ao realizar um GET para [http://localhost:3000/authors](http://localhost:3000/authors), deverá retornar 2 autores.

</h4>

<br>

<h3> 3. Considerando nosso cenário de uma api de posts, o que as seguintes requisições HTTP fazem? </h3>

<h4> GET http://localhost:3000/posts/1 </h4>

GET solicita ao servidor os dados do objeto de id 1, localizada na rota posts.

<h4> DELETE http://localhost:3000/posts/1 </h4>

Nesse caso, serão deletados os dados do objeto de id 1, da rota posts. 

<h4> POST [http://localhost:3000/posts](http://localhost:3000/posts) </h4>

Será criado um objeto dentro da rota posts, com suas as propriedades e valores.

<br>

<h3> 4. Qual a diferença entre PUT e PATCH? </h3>

- 

<br>

<h3> 5. Segundo a documentação do json-server e considerando a modelagem que você fez, qual seria a requisição necessária para retornar todos os posts de um determinado autor? </h3>

- 