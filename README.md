This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

### <https://www.better-auth.com/docs/installation>

## Basic Login/ Register form with Better Auth

## Tech Stack Used

React-Hook Form
Zod
Shadcn
Better Auth
pg
dotenv
drizzle orm
tailwind
sonner

## Tips to know

"The model User not found error can be avoided by"

### 1. Adding  plugins: [nextCookies()] in the auth.ts as the last variable

### 2. Esuring the schema is exported from the schema.ts file and placed in the DizzleAdapter object in the auth.ts fle

## Steps

### 1. Install Next App

### 2. Install Better Auth

### 2. Set Better Auth environment variable (Secret) and better auth url(_localhost:3000)

### 3. Create a Better Auth Instance -- e.g Lib/auth.ts

### 4. Configure the DB and ORM

### 5.  Add Neon Database Serverless and dot env package

### 6.  Create Neon DB project

### 7.  Create DB folder with basic boilerplate drizzle.ts file. Create Empty schema.ts file

### 8. Create drizzle.config.ts file

### 9. Update the auth.ts file (Step 3) with basic auth file from documentation

### 10. Execute npx @better-auth/cli generate to populate the DB

### 11. Populate the empty schema.ts file with the created auth-schema.ts file generated from step 10

### 11. execute the command npx drizzle-kit-push. This will push the tables to the DB

### 12. Update the auth.ts file with the providers (email/password or scial providers)

### 13. Create the API route that is needed for server side calls app/api/auth/[...all]/route.ts

### 14. Create the auth-client.ts fle in the lib directory lib/auth-client.ts

### 15. Create Middleware.ts

### 16. Create Server Actions file

## UI

### 1. Imlement Shadcn

### 2. Use the Login Form from shadcn blocks

### 3. Use react Hook form to get data and send to the server
