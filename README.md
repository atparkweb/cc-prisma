# Setting up a containerized ORM project

1. [ ] Install Prisma CLI
		- brew: `brew install prisma`
		- npm:  `npm install -g prisma`
2. [ ] [Install Docker Engine](https://hub.docker.com/search?q=&type=edition&offering=community)
3. [ ] Launch Prisma and DB: `docker-compose up -d`
4. [ ] Setup config Prisma: `prisma init`
5. [ ] Deploy Prisma API: `prisma deploy`
6. [ ] Generate Prisma Client: `prisma generate`
7. [ ] Setup Node/NPM project
		- `npm init -y`
		- `npm i --save prisma-client-lib`
