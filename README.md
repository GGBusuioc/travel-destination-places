# travel-destination-places

ASP.NET Core 5 with Vue.js 3 Project

Throughout this project I've learned how to:

- Apply clean architecture to an ASP.NET Core 5, which improves the ability to build a highly scalable and testable application in the long term
- Handle any HTTP requests sent by any client-side applications and process and save them in any type of relational database using EF Core
- To apply CQRS, MediatR, and Pipeline Behavior. The MediatR package makes the CQRS pattern easy to do in ASP.NET Core. The Pipeline Behavior package allows you to run a number of methods, such as validations or loggings, in a command before and after a handler processes it
- Use the the FluentValidation package, a powerful library for validating your models
- Use the AutoMapper package, a library that allows you to map an object to another object by writing a few lines of code
- Implement the URI path versioning strategy and integrate with SwaggerUI
- Override ILogger with a structured logging framework named Serilog and save it in a database in order to easily query/investigate when debugging the application
- Integrate IdentityServer4 that integrates OAuth 2 and OpenID Connect
- Secure the app using the JWT. The application responds with a token, which has a payload of user information, to an authenticated request.
- Use Distributed Caching and implement it in the app via Redis

- Use Vuetify as an UI component library for my app to develop faster
- Lazy load pages to improve the loading speed of the app
