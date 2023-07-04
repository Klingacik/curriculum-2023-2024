# Angular a ASP.NET Core

- 1. polrok (16 týždnov, 80 školských hodín)

## Zhrnutie

Učebný plán je navrhnutý pre študentov strednej školy, ktorý zahŕňa výučbu Angularu pre front-end a ASP.NET Core pre back-end. Študenti si môžu zvoliť, či sa chcú špecializovať na front-end alebo back-end, ale pracujú spoločne v pároch (front-end a back-end) na tímovom projekte, kde aplikujú všetky naučené lekcie počas školského roka. Školský rok je rozdelený na 32 týždňov, pričom každý týždeň obsahuje 5 školských hodín. Učebný plán zahŕňa tématické oblasti ako základy Angularu a ASP.NET Core, prácu s komponentami, spracovanie dát, smerovanie, moduly, testovanie, pokročilé témy a tímový projekt. Celkový cieľ je poskytnúť študentom pevné základy v týchto technológiách a umožniť im ich praktickú aplikáciu prostredníctvom spolupráce na tímovom projekte.

## Lekcie

### Week 1: Setting up the environment

- **Front-end problem**: Understand the basics of Angular and set up a local development environment.
  - **Hint**: Install Node.js and npm. Use Angular CLI to create a new Angular project.
- **Back-end problem**: Understand the basics of ASP.NET Core and set up a local development environment.
  - **Hint**: Install .NET Core SDK. Use .NET CLI to create a new ASP.NET Core project.
- **Lessons**: Angular - Basics, Working with Angular CLI, ASP.NET Core - Basics, Working with .NET CLI
- **Acceptance criteria**: Both Angular and ASP.NET Core environments are set up and ready for development. You are able to create new projects.

### Week 2: Creating components and database structure

- **Front-end problem**: Create the main components of the application: HeroesListComponent, HeroDetailComponent.
  - **Hint**: Use Angular CLI commands `ng generate component HeroesList` and `ng generate component HeroDetail`.
- **Back-end problem**: Create the basic structure of the database in MS SQL using EF Core migrations.
  - **Hint**: Define a Hero model and use EF Core tools to create and apply a migration.
- **Lessons**: Angular - Components, EF Core - Migrations
- **Acceptance criteria**: You have HeroesList and HeroDetail components in Angular. The basic structure of the database is ready in MS SQL.

### Week 3: Implementing heroes list and Hero model

- **Front-end problem**: Implement displaying the list of heroes in HeroesListComponent.
  - **Hint**: Use *ngFor directive to display an array of heroes.
- **Back-end problem**: Create a Hero model and configure EF Core DbContext.
  - **Hint**: Define Hero class with necessary properties and include a `DbSet<Hero>` in your `DbContext` class.
- **Lessons**: Angular - Displaying data in the component, EF Core - Models and DbContext
- **Acceptance criteria**: The Angular application can display a list of heroes. The Hero model and DbContext are set up in the ASP.NET Core application.

### Week 4: Navigation and API endpoints

- **Front-end problem**: Implement functionality for navigation between different views.
  - **Hint**: Use Angular's Router module to configure and implement navigation.
- **Back-end problem**: Create API endpoints for retrieving and adding heroes.
  - **Hint**: Use ASP.NET Core's Controller classes and action methods to create API endpoints.
- **Lessons**: Angular - Navigation and Routing, ASP.NET Core - Creating APIs
- **Acceptance criteria**: The application allows navigation between different views and is able to add new heroes via API.

### Week 5: Directives and API enhancement

- **Front-end problem**: Work with Angular directives to show and hide elements and display hero data.
  - **Hint**: Use built-in Angular directives like `*ngIf` and `*ngFor` to manipulate the DOM.
- **Back-end problem**: Extend the API endpoints to allow deleting and updating heroes.
  - **Hint**: Add new action methods in your controller to handle HTTP DELETE and PUT requests.
- **Lessons**: Angular - Directives, ASP.NET Core - Extending APIs
- **Acceptance criteria**: The application can display, delete, and update hero details.

### Week 6: Details component and validation

- **Front-end problem**: Create the Detail component, which allows editing the details of a hero.
  - **Hint**: Implement two-way data binding for editable fields in your Detail component.
- **Back-end problem**: Implement validation rules and improve error handling in the API.
  - **Hint**: Use ASP.NET Core's model validation features and exception handling middleware.
- **Lessons**: Angular - Displaying and editing details, ASP.NET Core - Validation and error handling
- **Acceptance criteria**: The application allows editing hero details with validation rules and improved error handling.

### Week 7: Two-way data binding and shared services

- **Front-end problem**: Add the ability to update a model via two-way data binding.
  - **Hint**: Use `[(ngModel)]` directive for two-way data binding in your forms.
- **Back-end problem**: Create and use a shared service to assemble the heroes.
  - **Hint**: Create a service class that uses EF Core to interact with the database and inject it where needed.
- **Lessons**: Angular - Two-way data binding, ASP.NET Core - Shared services
- **Acceptance criteria**: The application allows model updates via two-way data binding and uses shared services for assembling heroes.

### Week 8: Advanced operations and API features

- **Front-end problem**: Implement front-end functionality for advanced operations like filtering and sorting.
  - **Hint**: Use Angular's Pipes and Directives to implement filtering and sorting of heroes on the client-side.
- **Back-end problem**: Create API endpoints for advanced operations like filtering and sorting.
  - **Hint**: Add parameters to your action methods and use LINQ to implement filtering and sorting.
- **Lessons**: Angular - Pipes and Directives, ASP.NET Core - Advanced API features
- **Acceptance criteria**: The application allows advanced operations like filtering and sorting, both on the client-side and via API calls.

### Week 9: User Interaction and Authentication/Authorization

- **Front-end problem**: Allow users to select a hero from the list and edit it in the detail view.
  - **Hint**: Use property binding to bind a selected hero to the detail view.
- **Back-end problem**: Implement authentication and authorization in the API.
  - **Hint**: Use ASP.NET Identity to add authentication and authorization. Configure and apply policies for controlling access to API endpoints.
- **Lessons**: Angular - User interaction, ASP.NET Core - Authentication and Authorization
- **Acceptance criteria**: The application allows users to select and edit a hero. The API has authentication and authorization set up, controlling who can access and modify data.

### Week 10: Formatting with pipes and deployment

- **Front-end problem**: Format data using pipes.
  - **Hint**: Use built-in Angular pipes and/or create custom pipes for data transformation.
- **Back-end problem**: Finish testing and debugging the API, prepare for deployment.
- **Hint**: Use unit testing and integration testing for the API. Prepare the application for deployment (environment variables, deployment scripts, etc.)
- **Lessons**: Angular - Pipes, ASP.NET Core - Preparation for deployment
- **Acceptance criteria**: The application is complete with data formatting, the database is optimized, and it's ready for deployment.