# REST API with Node.js + Express.js + TypeScript

This sample demonstrates how to refactor the calculator API with MVC (Model View Controller) pattern and object-oriented programming. The refactored code uses Domain Object to represent business logic, Data Access Object (DAO) for data access, Data Mappers to convert between Domain Object and Data Transfer Object (DTO), and controller to coordinate workflows. The refactored code improves separation of concern and is more modular and maintainable.

### Pre-requisites

- [Node.js](https://nodejs.org/en/download) v18 or higher

### Instructions

1. Clone the repository with this branch.

```shell
git clone -b main <CLONE URL>
```

2. Install dependencies.

```shell
npm install
```

3. Run Express.js server.

```shell
# for Windows
npm run dev:win

# for Linux / macOS
npm run dev
```
