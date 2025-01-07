# [CRUD Web API com Angular 13 e .Net entity framework 6](https://youtu.be/hZuBfDyTRQ8)
by: Cursos Kane Chan

## Projeto com:
- .NET Core
    - EntityFramework
- Angular

## Migration
- cd ./TarefeiroAPI
- dotnet ef migrations add InitialCreate
- dotnet ef database update

- NOVA MIGRATION
    - dotnet ef migration add comentariosSize200
    - dotnet ef database update

## Front (Angular)
Com node instalado executar: `npm install @angular/cli`
- Criar projeto (`ng new TarefeiroFrontAngular`)
- Comando para criar os components: `ng g c tarefeiro`
    - `ng g c tarefeiro/show-tarefeiro`
    -  `ng g c tarefeiro/add-edit-tarefeiro`
    - Criando o service: `ng g service tarefeiro-api`
      
