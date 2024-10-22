# Will you catch the bug?

## Objective

The developer team has unfortunately introduced a bug in our application. Your goal is to find it, explain them how to reproduce it and write a test that catches it, so that we don't make the same mistake again in the future.

## How to run the application

This repository contains 2 folders:

- `app-working`: The application working correctly.
- `app-with-bug`: The application with a bug.

To run the application, you need to serve the content of the corresponding folder as a static site.

You can achieve this using the [`serve`](https://www.npmjs.com/package/serve) npm package:

### Install the package

```
npm install -g serve
```

### Serve the build as a static site

```
serve build-no-bug
```

or

```
serve build-with-bug
```

You can then access the site at http://localhost:3000/.

## Tasks

- Find the bug in `app-with-bug`.
- Write down a ticket for this bug in `ticket.md`, explain us how to reproduce it.
- Create a test that catches the bug, for instance using [Playwright](https://playwright.dev/) or [Cypress](https://www.cypress.io/).
  - The test should pass when run against `app-working`.
  - It should fail against `app-with-bug`.
- Explain how to run your test in this README.

## Deliverables

Make sure to include all source code in the repository.

## Evaluation criteria

- The bug is spotted.
- Autonomous test set up and implementation.
- The test works as expected.
- Explanations are clear.

## CodeSubmit

Please organize, design, test and document your code as if it were going into production - then push your changes to the master branch. After you have pushed your code, you may submit the assignment on the assignment page.

All the best and happy coding,

The ActiveViam Team
