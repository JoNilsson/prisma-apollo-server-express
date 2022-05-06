# Prisma Apollo Server Express

Boilerplate Web Application project for setting up [Prisma](https://www.prisma.io/) with an [Apollo](https://www.apollographql.com/) GraphQL server and an [Express](https://expressjs.com/) frontend web server. 
  
**Prisma** is a database abstraction layer that provides a unified interface for access to different types of databases. It offers an easy-to-use API that can be used to query data from any connected database.  
  
**Apollo** is a *Node.js* based server that provides a back end for the GraphQL application. It is used here to connect databases and create the framework for creating APIs and microservices.  
  
**Express** is a Node.js web server. It provides a set of tools for building a front end web applications to interact with the application datastores via APIs.  
  
## Getting started  

1. Clone the repository

```
git clone https://github.com/JoNilsson/prisma-apollo-server-express.git
```

2. Install dependencies

```
cd prisma-apollo-server-express
yarn
```

3. Set up your database

Copy `.env.example` to `.env` and fill in your Prisma and database credentials

4. Run Prisma to generate the Prisma client

```
yarn run prisma:generate
```

5. Run the Apollo server

```
yarn start
```

The Apollo server is now running on `http://localhost:4000`.

Navigate to `http://localhost:4444` in your browser to access the GraphQL playground.

