# INSTALLATION.md

## Backend Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Alex1-stack-dev/MeetSpectatorLive.git
   ```
2. Change directory:
   ```bash
   cd MeetSpectatorLive/backend
   ```
3. Install the required dependencies:
   ```bash
   npm install
   ```
4. Set up environment variables by creating a `.env` file in the root of the backend directory with the following keys:
   ```
   DB_HOST=
   DB_USER=
   DB_PASS=
   ```
5. Start the backend server:
   ```bash
   npm start
   ```

## Frontend Setup Instructions
1. Change to the frontend directory:
   ```bash
   cd MeetSpectatorLive/frontend
   ```
2. Install the required dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables by creating a `.env` file in the frontend directory.
4. Start the frontend application:
   ```bash
   npm start
   ```

## HY-TEK Integration
- Follow the HY-TEK API documentation for integration setup.
- Ensure that API keys are stored in the environment configuration.

## Database Configuration
1. Install the database software (MySQL, PostgreSQL, etc.) based on your requirements.
2. Create a new database:
   ```sql
   CREATE DATABASE meetspectator;
   ```
3. Set the database credentials in your `.env` file as mentioned above.
4. Run migrations to set up the database schema:
   ```bash
   npm run migrate
   ```

## Troubleshooting
- **Common Issues:**
  - Ensure that all required services (database, backend, frontend) are running.
  - Check the console for error messages and ensure all environment variables are correctly set.
- **Resources:**
  - Consult the logs for the backend and frontend applications for more details on errors.