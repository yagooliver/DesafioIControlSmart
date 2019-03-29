# Desafio

Uma empresa deseja controlar dispositivos e receber os eventos desses dispositivos, essa aplicação será composta de uma API Rest e um serviço WCF para realizar a comunicação entre si.

# Web APi
1. Você precisa criar uma Web API utilizando o Asp.NET com C#, que terá seus serviços consumidos por uma 
aplicação cliente que se conecta aos dispositivos e fará interação com o banco de dados. API deverá enviar comandos para acionar os dispositivos remotamente via serviço
- Criar métodos de persistência e consulta dos eventos
- Criar métodos de envio de comandos para o serviço Client

# Serviço WCF
2. O serviço WCF enviará os dados do dispositivo acionado remotamente na Api e envia o evento realizar com o OK para a WebApi registrar no banco de dados, o registro só poderá efetuado após o retorno do serviço. Exemplo:
"Porta X acionada"
"Camera X ligada"

Em geral, todos os dispositivos tem seguintes atributos:
IP
MAC
Status (Ligado/ desligado)

e métodos de 
Liga
Desliga.

Crie as classes de dois dispositivos diferentes.
- Dispositivo portão, que além dos atributos genéricos, pode abrir e fechar
- Dispositivo câmera, que além dos atributos genéricos, possui uma flag que diz se o sensor de movimento está ativado ou não

# Critérios para avaliação dos candidatos:
- Qualidade do código
- Utilização de conceitos de programação orientada a objetos(abstração, herança, polimorfismo e encapsulamento)
- Utilização de padrão de projetos
- Arquitetura da aplicação
- Respeito às boas práticas de programação como SOLID.
- Código limpo

*OBS 1: Utilização de testes unitários é diferencial
*OBS 2: Não será obrigatório criar o front end para API, mas poderá ser diferencial.
