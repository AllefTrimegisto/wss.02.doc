# wss.02.doc
Faça um projeto explicando como funcionam os métodos HTTP com exemplos de requisições, sua utilização e em qual momento cada um dos métodos devem ser utilizados. 
Além disso, descreva o que é WSDL, seu significado e sua função.

HTTP (Hypertext Transfer Protocol) é um protocolo de comunicação de aplicações da Internet que permite a troca de informações entre servidores e clientes. Ele é amplamente utilizado para acessar recursos da Web, como páginas da Web, imagens, vídeos e outros tipos de arquivos.

Os métodos HTTP são as ações que podem ser executadas em um recurso da Web. Alguns dos métodos HTTP mais comuns incluem:

    GET: Este é o método mais comum utilizado para recuperar informações de um recurso da Web. É utilizado para requisitar uma página da Web, imagem ou outro tipo de arquivo. Exemplo de requisição GET
    
    GET /index.html HTTP/1.1
Host: www.example.com

POST: Este método é utilizado para enviar informações ao servidor, como dados de formulário. Exemplo de requisição POST:

POST /form HTTP/1.1
Host: www.example.com
Content-Type: application/x-www-form-urlencoded
Content-Length: 37

username=john&password=doe

PUT: Este método é utilizado para atualizar informações em um recurso da Web. Exemplo de requisição PUT:

PUT /user/1 HTTP/1.1
Host: www.example.com
Content-Type: application/json
Content-Length: 45

{"username": "john", "email": "john@example.com"}

    DELETE: Este método é utilizado para excluir um recurso da Web. Exemplo de requisição DELETE:


DELETE /user/1 HTTP/1.1
Host: www.example.com

WSDL (Web Services Description Language) é uma linguagem de descrição de serviços da Web que descreve a interface de um serviço da Web, incluindo o endereço do serviço, a lista de operações que ele suporta e as regras de comunicação entre o cliente e o servidor. A função do WSDL é fornecer uma descrição clara e precisa dos serviços da Web disponíveis para clientes que desejam acessá-los. Dessa forma, o WSDL permite que desenvolvedores criem aplicações cliente que possam interagir com serviços da Web sem ter que conhecer a implementação detalhada do serviço.
