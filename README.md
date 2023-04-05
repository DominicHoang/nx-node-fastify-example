# NX with Fastify App

This proof of concept project demonstrates the use of NX workspace with Fastify app.

1. Generate new NodeJS app
`npx nx generate @nrwl/node:application fastify-app --docker --no-interactive`
2. build app
`nx run fastify-app:build:production`
3. build docker
`nx run fastify-app:docker-build`


