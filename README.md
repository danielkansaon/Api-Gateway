# Api-Gateway
O repositório consiste em uma Api Gateway construída com o Ocelot

Link Lambda Function: https://

<b>Documentação API-Gateway</b>

Primeiramente, é necessário iniciar as APIs localizadas:

- https://github.com/danielkansaon/Api-Livraria
- https://github.com/danielkansaon/Api-Autenticacao
- https://github.com/danielkansaon/Api-Cartao-Credito

As APIs acima já estão configuradas em suas respectivas portas. Após essa etapa, inicie a API-Gateway. Após iniciar, basta realizar uma requisição nos caminhos abaixo para acessar os recursos.

- http://localhost:5000//api/publico/v1/livro - ["Get"]
  
- http://localhost:9000/publico/v1/auditoria/{idusuario} - ["Get"]

- http://localhost:9002/public/v1/api/cartao_credito/{idusuario}/{numerocartao} - ["Get"]
