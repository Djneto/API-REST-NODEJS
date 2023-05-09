Começo do projeto
npm init
npm install fastify
npm install -D typescript
npx tsc --init
npm install -D @types/node
npx tsc src/server.ts
node src/server.js
npm install tsx -D

"scripts": {
"dev": "tsx watch src/server.ts"
},

npm run dev

BD
npm install knex sqlite3

"scripts": {
//windows
"knex": "node --no-warnings --loader tsx ./node_modules/knex/bin/cli.js"
},

npm run knex -- -h
npm run knex -- migrate:make create-documents
npm run knex -- migrate:latest
npm run knex -- migrate:rollback

Variáveis de ambiente
npm i dotenv
npm i zod

testes
npm i vitest -D
npm i supertest -D
npm i -D @types/supertest
