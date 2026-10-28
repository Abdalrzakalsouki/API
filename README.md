# API

A collection of my small backend and REST API projects. Each one used to live in its own repository and was merged here with its full commit history.

## Index

| Project | Summary | Stack |
|---|---|---|
| [TasksAPI](TasksAPI) | Task manager REST API with user accounts. Sign-up, login and logout (JWT), avatar upload, and per-user task CRUD with filtering. Welcome emails go out through SendGrid. | Node.js, Express, MongoDB (Mongoose) |
| [Management-dashbored](Management-dashbored) | Task management API written in TypeScript. Express router with Mongoose task schema and model. | Node.js, Express, TypeScript, MongoDB |
| [BuildingRestAPI](BuildingRestAPI) | REST API for buildings with CRUD endpoints under `api/Building`, EF Core migrations and seed data. | ASP.NET Core, C#, Entity Framework |

## Running

- **TasksAPI**: `npm install`, then set `MONGODB_URL`, `JWT_SECRET` and `SENDGRID_API_KEY` as environment variables, then `npm start`.
- **Management-dashbored**: `npm install`, set `DATABASE_CONNECTION_URL` to your MongoDB connection string, then `npm run dev`.
- **BuildingRestAPI**: `dotnet run` from the project folder.

## History

Every folder keeps the commit history of its original repository (`git log -- TasksAPI`).
