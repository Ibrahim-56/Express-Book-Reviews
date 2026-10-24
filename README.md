# Express Book Reviews

A Node.js and Express learning project structured around a book-review API. The application code is in `final_project/`.

## Current status

This repository is an unfinished starter template. Several routes in `router/general.js` and `router/auth_users.js` still return a placeholder response, and the login, registration, and review workflows are not implemented. The `npm test` script is also a placeholder that exits with an error.

It is therefore not yet a completed book-review API and should not be presented as a production-ready application.

## Technology

- Node.js
- Express
- Express Session
- JSON Web Tokens

## Inspect the source

```bash
cd final_project
npm install
```

The current start script launches `index.js` on port 5000:

```bash
npm start
```

Starting the server does not mean the unfinished API routes work.

## Work required before showcasing as a completed project

- Implement registration, login, and authenticated review operations.
- Add validation and consistent error handling.
- Move session and token secrets to environment variables.
- Add automated tests for public routes, authentication, and review operations.
- Replace the placeholder test command and verify the suite from a clean checkout.
