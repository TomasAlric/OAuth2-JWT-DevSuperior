<div>

  <h1>Desafio sobre validação e segurança #2 </h1>
  
  Este é um sistema de eventos e cidades com uma relação N-1 entre eles:

  <img height="300px"  align="center" src=https://i.imgur.com/cUv8LrB.png>

Neste sistema, somente as rotas de leitura (GET) de eventos e cidades são públicas (não precisa de login). Usuários <b>CLIENT</b> podem também inserir (POST) novos eventos. Os demais acessos são permitidos apenas a usuários <b>ADMIN</b>.


Validações de City:
* Nome não pode ser vazio

Validações de Event:
* Nome não pode ser vazio
* Data não pode ser passada
* Cidade não pode ser nula
  
<br></br>
Collection do Postman: https://www.getpostman.com/collections/e1f59c905aeca84c1ebc

</div>
