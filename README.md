# Hello Prisma

Commands

npx prisma init --datasource-provider sqlite (file based db)
npx prisma studio (launches interactive gui db view)
npx ts-node script.ts (runs the example client script)
npx prisma migrate dev --name init (generates a migration and applies it)

When you change your schema, run migrate to change db.
`migrate` also runs `generate`, which updates the node_modules/@prisma/client  
^ the client gets generated locally in that other package - wild!
