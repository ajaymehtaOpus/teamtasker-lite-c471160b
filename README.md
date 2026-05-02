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