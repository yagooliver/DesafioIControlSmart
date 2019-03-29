Desafio

1) Você precisa criar uma Web API utilizando o Asp.NET com C#, que terá seus serviços consumidos por uma 
aplicação cliente que se conecta aos dispositivos e fará interação com o banco de dados.

2) Além da API Rest, crie um client que irá se comunicar com a WebApi enviando os dados do dispositivo acionado no client e registrar esses eventos
realizados no banco de dados. Exemplo:
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

3) API poderá também enviar comandos para acionar os dispositivos remotamente

Critérios para avaliação dos candidatos:
- Qualidade do código
- Utilização de conceitos de programação orientada a objetos(abstração, herança, polimorfismo e encapsulamento)
- Utilização de padrão de projetos
- Arquitetura da aplicação
- Respeito às boas práticas de programação como SOLID.
- Código limpo

OBS 1: Utilização de testes unitários é diferencial
OBS 2: Não será obrigatório criar o front end para API, mas poderá ser diferencial.
