# API REST e RESTful

Uma API REST consiste em um conjunto de princípios arquiteturais voltados para o desenvolvimento de serviços web. Seu funcionamento baseia-se em operações bem definidas, conhecidas como métodos do protocolo HTTP, para facilitar a comunicação entre sistemas. Por sua vez, uma API RESTful segue os princípios REST de maneira mais rigorosa, tornando-se assim mais previsível e fácil de usar suas rotas e recursos.

## Diferenças entre REST e RESTful

Enquanto o REST apenas estipula um conjunto de diretrizes gerais, o RESTful implementa essas diretrizes de forma mais estrita, seguindo os padrões e convenções definidos pela arquitetura REST. Em outras palavras, uma API RESTful é a implementação completa e rigorosa dos princípios REST.

## HTTP Verbs

Os métodos HTTP, também conhecidos como verbos HTTP, são utilizados para indicar a ação que deve ser executada em um recurso. Os principais métodos incluem:

- **GET:** Recupera dados de um recurso.
- **POST:** Cria um novo recurso.
- **PUT:** Atualiza completamente um recurso existente.
- **PATCH:** Atualiza parcialmente um recurso existente.
- **DELETE:** Remove um recurso.

O uso adequado desses métodos permite que as APIs RESTful realizem operações específicas de forma intuitiva e eficiente.

## HTTP Status Code

Os códigos de status HTTP são retornados em resposta a uma requisição feita a um servidor. Eles fornecem informações sobre o resultado da operação solicitada. Alguns códigos comuns incluem:

- **200 OK:** Indica que a requisição foi bem-sucedida.
- **201 Created:** Informa que um novo recurso foi criado com sucesso.
- **204 No Content:** Sinaliza que a requisição foi processada com sucesso, mas não há conteúdo para ser retornado.
- **400 Bad Request:** Sinaliza que a requisição foi mal sucedida devido a um erro proveniente do cliente.
- **404 Not Found:** O servidor não consegue encontrar o recurso que foi solicitado pelo cliente.
- **500 Bad Request:** Sinaliza que a requisição foi mal sucedida devido a um erro proveniente do Servidor.

Esses códigos são essenciais para a comunicação entre o cliente e o servidor, permitindo uma compreensão clara do estado da operação realizada.

Autor do resumo: Danilo Pereira Pessoa - 01561356
