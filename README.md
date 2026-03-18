# Stateful Auth MongoDB Feature

This is a robust backend application built with Express.js, TypeScript, and MongoDB. It implements stateful authentication with Passport.js, featuring OAuth integrations (Google & GitHub).

## Features

- **Express & TypeScript**: Strongly-typed server architecture.
- **MongoDB & Mongoose**: Fast, flexible data storage.
- **Authentication**: Stateful sessions via `passport-google-oauth20` and `passport-github2`.
- **Validation**: Schema-based data validation using `zod`.
- **Media Uploads**: Handled with `multer` and `cloudinary`.
- **Email Delivery**: Powered by `nodemailer` and `resend`.
- **API Documentation**: Pre-configured automatic Swagger docs via `swagger-autogen` and `swagger-ui-express`.
- **Logging**: High performance logging with `pino` and `pino-pretty`.
- **Security**: Includes `helmet`, `cors`, and `express-rate-limit`.
- **Code Quality**: Enforced with `eslint`, `prettier`, and commit linting via `husky`.

## Scripts

- `npm run dev` - Starts the development server using `tsx`.
- `npm run build` - Builds the application into the `dist` directory.
- `npm start` - Starts the compiled production application.
- `npm run typecheck` - Runs the TypeScript compiler for type checking.
- `npm run docs` - Generates the Swagger documentation.
- `npm run format:check` / `npm run format:fix` - Checks/fixes Prettier formatting.
- `npm run lint:check` / `npm run lint:fix` - Checks/fixes ESLint errors.

## Getting Started

1. Clone the repository and install dependencies:
   ```bash
   npm install
   ```

2. Duplicate `.env.example` to `.env` and fill in your variables.

3. Run the development server:
   ```bash
   npm run dev
   ```
