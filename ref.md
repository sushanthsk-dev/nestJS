## **Nest JS**
### Day 1
#### What is Nest Js
    - Typescript Friendy
    - Solves architecture problem
    - Uses express JS
        - doesn't give a direction of how product should be structured
    - Abstraction of expressJS
    - Scalable & Maintainable
    - Modular structure
    - Dependency Injection
    - Angular for BE
#### Why Nest Js
    - Structure
    - Modularity
    - Typescript
    - GraphQL
    - Rest API
    - Documentation
    - Popularity/ Community

## NestJs project setup
    `npm i -g @nestjs/cli`
    `nest new project-name``

### App.module.ts
    - Module: is a class annotated with @Module decorator (decorator adds some metadata to the current class or function)
    Dependency injection to avoid who manages it all (e.g new ClassName())
### Auth.controller.ts
    - Controller handles request and response back to client
    We will use @Controller annotation for controller with parameter route name
    @Post, @Get can be used for handling different request method
    
### Auth.service.ts
    - Service related code and with the annotation @Injectable decorator to attach metadata