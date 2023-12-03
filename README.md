# Atividade-Back
## Resumo sobre API REST e Implementação RESTful
### API REST
Uma API (Interface de Programação de Aplicações) REST (Representational State Transfer) é um conjunto de princípios arquiteturais que define como recursos web podem ser organizados e interagir. Essa abordagem é baseada em representações dos recursos e utiliza operações padrão do protocolo HTTP para realizar operações sobre esses recursos.

## Implementação RESTful
Uma implementação RESTful segue os princípios da arquitetura REST. Isso implica na exposição de recursos através de URIs (Uniform Resource Identifiers), a utilização de verbos HTTP adequados para operações específicas e o retorno de representações dos recursos em formatos como JSON ou XML.

## Verbos HTTP
Os verbos HTTP representam as ações que podem ser realizadas sobre os recursos. Os principais verbos são:

GET: Recupera informações sobre o recurso.
POST: Cria um novo recurso.
PUT: Atualiza um recurso existente.
DELETE: Remove um recurso.
Além desses, há outros verbos menos comuns, como PATCH, OPTIONS e HEAD, cada um com uma função específica.

## HTTP Status Code
Os códigos de status HTTP indicam o resultado da solicitação. Alguns códigos comuns incluem:

200 OK: Indica que a solicitação foi bem-sucedida.
201 Created: Indica que um novo recurso foi criado com sucesso.
204 No Content: Indica que a solicitação foi bem-sucedida, mas não há conteúdo para ser retornado.
400 Bad Request: Indica que a solicitação foi malformada ou contém parâmetros inválidos.
401 Unauthorized: Indica que é necessário autenticação para acessar o recurso.
404 Not Found: Indica que o recurso solicitado não foi encontrado.
