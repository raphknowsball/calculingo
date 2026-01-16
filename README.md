# Calcalingo

## Purpose 

This is a calculus tutoring webapp that I am developing in order to help my peers and I learn the concepts of calculus in a way that helps them determine and actively work on their weaknesses and concepts that they feel weak at. I was going to do this by using a RAG system where we put in a whole textbook (of the users choice) into the system and also an AI using the RAG system and the answers a user gives, or the questions they ask after a chapter to create new questions for them to reinforce those concepts.

## Timeline

I hope to get this finished before my final exams of my calculus course in June 2026!
In the future the webapp will be hosted on a domain but for now its still in development.

### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/bouzayenilyes/lingo.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=""
CLERK_SECRET_KEY=""
DATABASE_URL="postgresql://..."
STRIPE_API_KEY=""
NEXT_PUBLIC_APP_URL="http://localhost:3000"
STRIPE_WEBHOOK_SECRET=""
```

### Setup Drizzle ORM

```shell
npm run db:push

```

### Seed the app

```shell
npm run db:seed

```

or

```shell
npm run db:prod

```

### Start the app

```shell
npm run dev
```
