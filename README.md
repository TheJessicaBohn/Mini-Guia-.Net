# Mini Guide .Net with C#
Mini Guide .Net 

## What is .Net?:
- Is an open source developer platform, created by Microsoft, for buildind many differents types of applications like C#, VB.NET e F#.

## What is C#?:
- Is an object-oriented language, also created by Microsoft.
### OO - Object orientation:
- Class:
- Method:
- Object:
##### 4 Pillars:
- Abstraction: attempt to bring programming closer to our real life. It is what models the business rule.
  - Important:
    - Identity: every class has an identifiable identity, eg.: Class Person;
    - Properties: what are the important properties for me, to abstract eg.: name, age, etc;
    - Methods: are the verbs that denote action. Eg.: Talk , walk;
- Encapsulation: It is a good practice to hide the complexity and protect the code of the classes, and using only the methods.    
- Inheritance: it suits for code reuse, through generalization.
- Polymorphism: It is when we invoke a method for two classes that inherit from a previous class, with the same signature but with different execution in each inherited class.

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

## Sources:
- https://dotnet.microsoft.com/en-us/learn/dotnet/what-is-dotnet
