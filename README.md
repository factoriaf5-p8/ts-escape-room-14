# Typescript Labs

## Lab 14: Inheriting Interface Properties

file: `/src/14-extends.problem.ts`

Here we have a `User`, `Post`, and `Comment` that all share an `id` property:

```ts
interface User {
  id: string;
  firstName: string;
  lastName: string;
}

interface Post {
  id: string;
  title: string;
  body: string;
}

interface Comment {
  id: string;
  comment: string;
}

```

There are tests in place to ensure that all of the `id` values are the same.

Challenge
Your challenge is to do some refactoring to DRY out this code.

Consult the TypeScript docs to determine how you can share the id property without writing the same line of code repeatedly.