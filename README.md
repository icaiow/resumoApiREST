# resumoApiREST
Resumo sobre Api Rest e a implementação RESTFul e dos verbos http e http status code.


## API REST: Uma API REST (Interface de Programação de Aplicações baseada em Transferência de Estado Representacional) é um estilo arquitetônico para o desenvolvimento de serviços web que utiliza os princípios fundamentais da web. Algumas principais caracteristicas incluem:

-Estilo Arquitetônico  : A API REST segue um estilo arquitetônico que utiliza os princípios fundamentais da web, como HTTP, URI (Identificadores de Recursos Uniformes) e o conceito de representação de recursos.

-Recursos e URIs: Os recursos (dados ou serviços) são identificados por URIs, que são os endereços únicos dos recursos na web. Cada recurso pode ter diferentes representações (por exemplo, JSON ou XML).

-Operações HTTP: As operações padrão do protocolo HTTP (GET, POST, PUT, DELETE) são utilizadas para manipular recursos. Por exemplo, o método GET é usado para recuperar informações, o POST para criar um novo recurso, o PUT para atualizar um recurso existente e o DELETE para excluir um recurso.

-Sem estado definido: As APIs de REST não possuem estado definido, o que significa que cada solicitação precisa incluir todas as informações necessárias para processá-lo. Em outras palavras, as APIs de REST não requerem nenhuma sessão do lado do servidor. Os aplicativos do servidor não tem permissão para armazenar nenhum dado relacionado a uma solicitação de cliente.

-Capacidade de armazenamento em cache: Quando possível, os recursos devem ser armazenados em cache pelo cliente ou servidor. As respostas do servidor também precisam conter informações sobre as permissões de cache do recurso fornecido. O objetivo é melhorar o desempenho do cliente, além de aumentar a escalabilidade do servidor.

## API RESTful Conceito RESTful API: Uma API RESTful é uma abordagem para o desenvolvimento de APIs que segue os princípios do REST. Ela utiliza os métodos HTTP padrão (GET, POST, PUT, DELETE) para operações em recursos, identificados por URIs.

-Estado Stateless: A arquitetura é sem estado, o que significa que cada solicitação do cliente contém todas as informações necessárias, e o servidor não mantém informações sobre o estado do cliente entre as solicitações.

-Representação de Recursos: Os recursos são representados de forma consistente, geralmente em formatos como JSON ou XML. Isso facilita a interoperabilidade entre sistemas heterogêneos.

-Segurança: A AWS destaca a importância da segurança ao implementar APIs RESTful, enfatizando práticas seguras, como o uso de HTTPS para criptografar a comunicação.

## DIFERENÇAS ENTRE REST e RESTful API 

-REST é um estilo arquitetônico que define princípios gerais para o design de serviços web, enquanto RESTful API é uma implementação específica desses princípios em uma API particular. Uma API é considerada RESTful quando segue as boas práticas e convenções do REST. Portanto, "REST" refere-se ao estilo arquitetônico, enquanto "RESTful API" se refere a uma aplicação específica desses princípios na construção de serviços web.

## HTTP VERBS: Os HTTP verbs (métodos HTTP) são comandos utilizados em requisições HTTP para indicar a ação que deve ser realizada no recurso identificado. Cada verbo tem um significado específico e é associado a uma operação particular.

-GET, POST, PUT, PATCH, DELETE, HEAD, OPTIONS, TRACE, CONNECT

## HTTP STATUS CODE: Os códigos de status HTTP são códigos numéricos que indicam o resultado de uma solicitação HTTP entre um cliente e um servidor. Eles fornecem informações sobre o sucesso ou falha de uma operação, permitindo que os clientes e servidores comuniquem o estado da solicitação.

-PRINCIPAIS HTTP STATUS CODE:

100 - Continue: O servidor recebeu a solicitação inicial e o cliente pode continuar com a solicitação ou ignorar se já foi concluída.

200 - OK: A solicitação foi bem-sucedida.
201 - Created: A solicitação foi bem-sucedida, e um novo recurso foi criado como resultado.
204 - No Content: A solicitação foi bem-sucedida, mas não há conteúdo a ser enviado no corpo da resposta.

301 - Moved Permanently: A página solicitada foi movida permanentemente para outra localização.
302 - Found (ou Moved Temporarily): A página solicitada foi movida temporariamente para outra localização.

400 - Bad Request: A solicitação feita pelo cliente é inválida ou não pode ser processada pelo servidor.
401 - Unauthorized: O cliente deve autenticar-se para obter a resposta solicitada.
403 - Forbidden: O cliente não tem permissões para acessar o recurso.
404 - Not Found: O recurso solicitado não foi encontrado no servidor.

500 - Internal Server Error: Indica um erro interno no servidor que impediu a conclusão bem-sucedida da solicitação.
503 - Service Unavailable: Indica que o servidor não está pronto para manipular a solicitação. Pode ser devido a sobrecarga temporária ou manutenção do servidor.


 
   
   
   
Autor do resumo: Caio da Silva Nascimento - 01529409


