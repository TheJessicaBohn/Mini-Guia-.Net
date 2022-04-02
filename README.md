# Mini-Guia-.Net com C#
Mini Guia .Net

## O que é o .Net:
- É uma plataforma opensource de desenvolvimento criada pela Microsoft, voltado para linguagens como C#, VB.NET e F#.

## O que é po C#
- é uma linguagem orientada a objetos, também criada pela Microsoft.
### OO - Orientação a Objetos:
- Classe:
- Metodo:
- Objeto:
##### 4 Pilares:
- Abstração: É uma tentativa de aproximar a programação da nossa vida real. É o que modela a regra de negócio.
  - Importante:
    - Identidade: toda classe tem uma identidade identificável, ex: Classe Pessoa;
    - Propriedades: Quais são as propriedades importantes para que eu possa abstrair, ex:nome, idade, etc.
    - Métodos: Verbos de ação, ex: Falar
- Encapsulamento: É uma boa prática de esconder a complexidade e proteger o código das classes, e utilizando apenas os métodos.
- Herança: Serve para reutilização de código, por meio de generalização.
- Polimorfismo: É quando invocamos um método para duas classes que herdam de uma classe anterior, de mesma assinatura porém com a execução diferente em cada classe herdada.

## O que é uma API:

## O que é uma API Restfull:
### Corpo de uma Controller
- Contoller: Ficam dentro de de uma uma pasta chamada Controller, e tem o o padrão de nome NomeClasseController.
  - ```[ApiController]```: essa notação indica que todos os tipos derivados servem o HTTP API Responses.
  - ```[Route("[controller]")] 1:33:00```
  - ```ControllerBase```: é uma classe que já existe dentro do .NET, que já possui métodos uteis para a Controller MVC, porém serm o suporte a View. Lembrar do ```using Microsoft.AspnetCore.Mvc```.
### Verbos:
Podemos associá-los ao CRUD e ao SQL.
- POST: Create e INSERT
- GET: Read e SELECT
- PUT: Update e UPDATE
- DELETE: Delete e DELETE
### Ferramentas para ser Restfull:
- Swagger:
