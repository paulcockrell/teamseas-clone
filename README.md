# TeamSeas Clone

A clone of the site [teamseas.org](teamseas.org) using NestJS, Prisma, Apollo, React

## Dependencies

1. Postgres

## To start dev services

This command uses the concurrent library to start multiple process
simultaneously, so that the NestJS server starts, Apollo graphQL generator
starts and the Prisma generator starts.

```
npm run dev
```

## Database commands

To seed the Database

```
npx prisma db seed
```
