<img src="https://github.com/crudjs/crudjs/blob/master/crudjs-logo.png?raw=true" width="240px">

# CrudJS
Helps you build an awesome Node.js-based API

## Intro

There are dozens of Node.js frameworks out there. Same is true for databases and the rest of the pieces. If you want to build an API these days, it gets increasingly difficult to choose a specific tech stack to start working with.

In other words, **CrudJS** intends to be the [TodoMVC](http://todomvc.com) of Node.js-based APIs.

### API details

In a few words, the CrudJS is a basic blog API, with entities such as 'entries' (like posts), 'authors' and 'categories', and with basic create/update, read and delete capabilities for each entity. 'Entries' should be considered the main entity.


### You can use CrudJS...
- For comparing between different Node.js API frameworks: how their code looks like, which code style you like the most, which is the most performant and/or stable...
- For code reference when hacking something.
- As a boilerplate for starting a new cool project.

## Flavors
- [REST + Nest.js + Postgres](https://github.com/crudjs/rest-nestjs-postgres) - currently at version 1.0.0-alpha.1
- Fastify + RethinkDB - coming soon
- Express.js + MongoDB + Mongoose - coming soon
- Hapi.js + DynamoDB + Dynamoose - coming soon
- Koa - coming soon
- Serverless - coming soon
- Micro
- ...

## Versioning
The idea is to build new features incrementally on every CrudJS flavor. Hence, you can expect each version to have the same set of features across all the flavors.

Please note that the scopes for versions > 1.0.0 is still tentaive.

### ^1.0.0
- Basic CRUD functionality for `entries`, `authors` and `categories`.
- Ability to get all entries for a specific author.
- Ability to get all entries for a specific category.
- Protected POST and DELETE methods for every endpoint.
- Unit tests.
- Auto-generated Swagger definition file.

### ^2.0.0
- Readers can "cheer" an entry (anti-SPAM measures needed.)

### ^3.0.0
- Realtime capabilities (new cheers notifications...)

## Contributing

Of course, the project is open to contributions. Just leave a note!