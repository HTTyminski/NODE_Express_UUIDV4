# NODE_Express_UUIDV4
GET | POST | PUT | DELETE

node.js desenvolvimento back end usa o v8engine em javascript
npm dependencias  gerenciadores de pacotes
node c++ libuv treds
non blocking I/O 
nao precisa retornar todas a listagem de uma vez

framework
expressJs
micro framework
micro serviço

AdonisJs
NestJs - 
conceito api rest
GET busca informação ------------------ corpo da requisição   nap aprensenta na url
POST criar criar novo usuario --------- corpo da requisição
PUT altera 
DELETE delete

HEAD autorização e informação localizacao etc

JSON javascript object notation

HTTP Code XXX 3 digitos 
1XX informação

2XX Success
 200 :Success
 201 :Created

3XX Redirecionamento
  301:Movido permanente
  302:Movido

4XX Cliente Error - logado permissao
  400 bad request
  400 unauthorized
  404 not found

5XX erro no servidor
 500 internal server error

yarn add express -D
yarn add nodemon -D

metodos HTTP

GET - buscar informação do Backend.
POST - Criar uma informação no backend
PUT/PATCH - Alterar uma informação no backend
DELETE - Deletar uma informação do backend
 recursos- acessar recursos apos /recurso
insominia
http://localhost:3333 base_url

Tipos de parametros PRINCIPAIS:

QUERY params:
      filtros e paginação,listagem
      base_url/projects?title=React&owner=Henrique

ROUTE params:
      identificar recursos na hora de atualizar ou deletar
    
    const params = request.params;
    console.log(params);                     
          
           ou

	desestruturação.

   const {id} = request.params; 
   console.log(id);
	

REQUEST BODY params:
 conteudo na hora de criar ou editar um recurso(front-formulario crair usuario email senha cpf)
 vem estrura em JSON

yarn add uuidv4  = universal unique id
Filtros
