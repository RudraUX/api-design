npm i typescript ts-node @types/node prisma --save-dev
npx prisma init
npx prisma format
npm i @prisma/client --save
npx prisma migrate dev --name init

//reset bd
npx prisma migrate reset
