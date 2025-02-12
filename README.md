## Bootcamp da AVANADE - 2025

- FTP : Serve para transferência de arquivos.
- TELNET: Conecta remotamente a qualquer máquina (Gerenciamento de máquinas remotamente)
- WWW : Aplicação rodando dentro da internet


------

HTTP: Hypertext Transfer Protocol, é o protocolo fundamental usado na Web para transferência de dados. Quando um usuário acessa um site, o navegador envia uma solicitação envia uma solicitação HTTP para o servidor do site, que responde com os dados do site.


----------------------------------------------------------------------

Funcionamento de um Website 

1. Solicitação do Usuário: Tudo começa com o usuário inserindo um URL no navegador ou clicando em um link.

2. Resolução de DNS: O *URL* é traduzido em um endereço IP através de um sistema chamado DNS(Domain Name System).

3. Conexão com o servidor: O navegador utiliza o endereço IP para estabelecer uma conexão com o servidor que hospeda o site.

4. Resposta do servidor: O servidr processa a solicitação HTTP e envia de volta os aquivos que são geralmente o front do site (HTML, CSS, JS).

5. Renderização no navegador: O navegador interpreta todo esse front e exibe os site pras pessoas

----------------------------------------------------------------------

*O que é API ?*

    É um conjunto de regras e definições que permite diferentes aplicações de software ou componentes se comuniquem entre si.
    Funciona como um intermediário, permitindo que pedidos sejam feitos e respostas sejam recebidas entre diferentes sistemas de software.  

*Tipos de API*

- API RESTful

    Refere-se a APIs que seguem os princípios do REST (Representation State Transfer). São baseadas em padrões HTTP e utilizadas para interações web.

    *Características de APIs RESTful*

    ° Uso do métodos HTTP (GTE, POST, PUT, DELETE) para operações CRUD.
    ° Curva de aprendizado menor.
    ° Fácil de entender e implementar.

- API SOAP

    SOAP (Simple Object Access Protocol) é um protocolo que define um padrão para a troca de mensagens baseadas em XML.
    
    *Características de APIs SOAP*

    ° Protocolo baseado em XML para troca de informações.
    ° Independente de Linguagem e plataforma de transporte.
    ° Suporte para operações complexas e segurança avançada.

- API GraphQL

    Uma linguagem de consulta para sua API, e um servidor capaz de executar essas consultas, retornando apenas os dados especificados.

    *Características de APIs GraphQL*

    ° Permite que os clientes especifiquem exatamente quais dados querem.
    ° Eficiente na redução de solicitações e no tamanho dos dados transferidos.
    ° Flexível e fortemente tipada, facilitando a evolução das APIS.