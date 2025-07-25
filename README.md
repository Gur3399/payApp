-- To Run The project
** Install Dependencies**
npm install

Then Seed the DB after Migrating  in the packages/db folder

npx prisma migrate dev
npx prisma db seed


--------time to run the project in the root folder
npx turbo build
npm turbo run dev

