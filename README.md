# ds-department-employee
Desafio resolvido

Implemente as funcionalidades necessárias para que os testes do projeto abaixo passem:
https://github.com/devsuperior/bds03

Collection do Postman:
https://www.getpostman.com/collections/9c19a0ad21eb8a7d864a

Este é um sistema de funcionários e departamentos com uma relação N-1 entre eles:
Neste sistema, todas as rotas são protegidas. Usuários ADMIN podem ler e alterar recursos,
enquanto que usuários OPERATOR podem apenas ler.

## UML Project
![UML 1](/images/uml-user-role-to-employee-department.png)

Validações de Employee:
=================
<!--ts-->
* Nome não pode ser vazio
* Email deve ser válido
* Departamento não pode ser nulo
<!--te-->

Passos para resolver:
=================
<!--ts-->
* Modelo de dados User-Role
* Incluir infraestrutura de validação ao projeto
* Incluir infraestrutura de segurança ao projeto
* Implementar as funcionalidades
<!--te-->


