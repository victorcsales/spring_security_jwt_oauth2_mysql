<img width="306" height="165" alt="image" src="https://github.com/user-attachments/assets/d58d1b05-ba94-4c2f-9556-65470277838b" />


# Spring Security 6 + Token JWT na prática! 

Neste projeto vamos utilizar o Spring Security 6 para implementar um sistema de autenticação e autorização com JWT para os apps Spring Boot, desenvolvendo um projeto do zero chamado Twitter Simplificado. Nele,criaremos um sistema de autenticação e autorização com token JWT, com um controle de acesso granular através de ROLES (perfis de acesso), utilizando as annotations de segurança (@PreAuthorize, etc) nas controllers, utilizando integração com um banco de dados MySQL.
Tecnologias utilizadas.

* Java 21 
* Spring Boot 
* Spring Security 6 
* OAuth2 Resource Server 
* Integração com Banco de Dados MySQL via Docker

 Projeto:

Sem implementação da camada de segurança:
<img width="922" height="620" alt="image" src="https://github.com/user-attachments/assets/f99b32c6-a0a7-4322-aabe-288bc91f8620" />

Implementação da camada de segurança:
<img width="922" height="620" alt="image" src="https://github.com/user-attachments/assets/010eec09-b503-4a46-9804-42ba2c68454b" />

Uso de criptografia antissimétrica:
<img width="922" height="620" alt="image" src="https://github.com/user-attachments/assets/99ad116c-af88-4e5c-bd67-8a5f93857d8f" />

Fluxo de Autenticação – Token JWT:
<img width="922" height="620" alt="image" src="https://github.com/user-attachments/assets/7c38e1d4-4e10-4282-ac34-d1e5743e1ea7" />

Fluxo de Autorização – Token JWT:
<img width="922" height="620" alt="image" src="https://github.com/user-attachments/assets/28d3d859-ce51-4998-a998-68e3cc6f39f6" />

Gerando o projeto:
<img width="922" height="620" alt="image" src="https://github.com/user-attachments/assets/347399f9-e34f-448e-a297-63d3304448a8" />

Projeto importado para IDE:
<img width="922" height="620" alt="image" src="https://github.com/user-attachments/assets/55603cf0-6586-43f5-bfb0-7a645a0dfd11" />

Partes essenciais do projeto:

Gerando Chaves:
<img width="922" height="620" alt="image" src="https://github.com/user-attachments/assets/4e02dd41-9986-4b6e-a3b9-6e910f5f0c7e" />

Comandos:
/resources/
/resources$ openssl genrsa > app.key
/resources$ openssl rsa -in app.key -pubout -out app.pub
writing RSA key


Gerando chave via postman:
<img width="922" height="620" alt="image" src="https://github.com/user-attachments/assets/74f47591-e011-4fc3-b43c-f90a9f57ef19" />

Chave descriptografada:
<img width="922" height="620" alt="image" src="https://github.com/user-attachments/assets/e1c06e6e-7a92-4bcb-b05a-1c9c83b4edfa" />

Teste Projeto:
<img width="922" height="620" alt="image" src="https://github.com/user-attachments/assets/40520805-4a5c-4b37-bfa9-93f9023f6b78" />


