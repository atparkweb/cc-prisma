# Setting up a Prisma ORM project

1. Init NPM project: `npm init -y`
2. [ ] Setup config Prisma: `prisma init`
3. [ ] Set DATABASE_URL in .env file: `postgresql://USER:PASSWORD@HOST:PORT/DATABASE?schema=SCHEMA`
4. [ ] Write a model schema
5. [ ] Generate migration: `npx prisma migrate dev --name init`
6. [ ] Generate Prisma Client: `npx prisma generate`
