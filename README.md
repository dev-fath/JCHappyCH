## CLI

### run development server

```bash
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the
result.

### run production server

    1. build source files
    2. run server

```bash
yarn build && yarn start
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the
result.

### create static source file

```bash
yarn build
# static files are created in /.next/ directory
```

### DB Schema

```bash
# initialize database
yarn prisma:init

# create migration file
yarn prisma:migrate:dev

# clear all table data
yarn prisma:migrate:reset

#mark to resolve migration file
yarn prisma:run:resolve

#check migration file
yarn prisma:run:status

# deploy migration data to database
yarn prisma:run:deploy

# get database schema
yarn prisma:pull

# run migration flow
yarn prisma:run:migration

# open prisma studio
yarn prisma:studio
```

## Versions

- nextJS 13.1.6
- react 18.2.0
- sass 1.58.3
- prisma 4.11.0
- node 18.12.1

## code convention

- ESLint
- Prettier
