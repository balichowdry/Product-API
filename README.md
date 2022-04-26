# Building a REST API with NestJS and prisma + Postgres DB

This repository contains the starter project for the **Building a REST API with NestJS and Prisma with Postgres DB **  [Products API + SWAGGER DOC]
## Getting Started

1. Clone this repository

You can clone this repository with the following command:
```bash
git clone https://github.com/balichowdry/Product-API.git
```

2. Install dependencies

```bash
cd Product-API
npm install
```

3. Install NestJS CLI if you haven't already

```bash
npm i -g @nestjs/cli
```

4. npm run start:dev

Then Please hit the following URL's

# Product listing 
http://localhost:3000/products

# SWAGGER DOC FOR API
http://localhost:3000/api/


For any changes in the schema, please remove prisma/migration folder and run 
npx prisma migrate dev 

which will generate new schema
