# TeamTasker Lite

## Installation

1. Clone the repository.
2. Navigate to the backend directory: `cd apps/backend`
3. Install dependencies: `npm install`
4. Copy the `.env.example` file to `.env` and fill in the required values.

## Migration

Run the following command to set up the database:
```
npm run migrate
```

## Running the Application

To start the application in development mode, run:
```
npm run dev
```

## Verification Commands

To verify the setup, run:
```
npm install
npm run migrate
node --check src/index.js
npm run build
```

## Environment Variables

Make sure to set the following environment variables in your `.env` file:
- `DATABASE_URL`: Your PostgreSQL connection string.
- `JWT_SECRET`: Secret key for JWT.
- `JWT_REFRESH_SECRET`: Secret key for refresh tokens.
- `PORT`: Port number for the application (default is 3000).