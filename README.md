# Asinos API

A NestJS project initialized with custom API prefix configuration.

## Setup

1.  Install dependencies:
    ```bash
    npm install
    ```

2.  Ensure `.env` file exists with the following configuration:
    ```env
    API_PREFIX=api
    API_VERSION=v1
    PORT=3000
    ```

3.  Run the application:
    ```bash
    # development (HMR - Recommended)
    npm run start:hmr
    
    # development (Standard Watch)
    npm run start:dev

    # watch mode
    npm run start:dev

    # production mode
    npm run start:prod
    ```

## API Endpoint

The global prefix is configured dynamically. By default:
`http://localhost:3000/api/v1`
