# Desafio

Uma empresa deseja controlar dispositivos e receber os eventos desses dispositivos. Foi decidido que a melhor solução para eles, seria a criação de uma aplicação cliente que seria executado como um Windows Service, e uma Web API para prover métodos de acionamento dos dispositivos.

# Web APi
Você precisa criar uma Web API utilizando o Asp.NET com C#, que terá seus serviços consumidos por uma 
aplicação cliente que se conecta aos dispositivos e fará interação com o banco de dados. API deverá enviar comandos para acionar os dispositivos remotamente via serviço
- Criar métodos de persistência e consulta dos eventos
- Criar métodos de envio de comandos para o client Windows Service

# Windows Service
O Windows Service enviará os dados do dispositivo acionado remotamente pela Api e envia o evento de OK de volta para API para registrar o evento no banco de dados, o registro só poderá efetuado após o retorno do serviço. Exemplo de eventos:
- "Porta X acionada"
- "Camera X ligada"

Em geral, todos os dispositivos tem seguintes atributos:
- IP
- MAC
- Status (Ligado/ desligado)

Métodos:
- Liga
- Desliga

Crie as classes de dois dispositivos diferentes.
- Dispositivo portão, que além dos atributos genéricos, pode abrir e fechar
- Dispositivo câmera, que além dos atributos genéricos, possui uma flag que diz se o sensor de movimento está ativado ou não

# Critérios para avaliação dos candidatos:
- Qualidade do código(Código limpo)
- Utilização de conceitos de programação orientada a objetos(abstração, herança, polimorfismo e encapsulamento)
- Utilização de padrão de projetos
- Arquitetura da aplicação
- Respeito às boas práticas de programação como SOLID.

# Observações
- Utilização de testes unitários é diferencial.
- Não será obrigatório criar uma interface Web ou utilização de um framework SPA, mas poderá ser diferencial.
