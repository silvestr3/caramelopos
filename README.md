# Caramelo POS - Docker build

Complete docker build for Caramelo POS

- Backend: [https://github.com/silvestr3/caramelo2-api](https://github.com/silvestr3/caramelo2-api)
- Frontend: [https://github.com/silvestr3/caramelo2-public](https://github.com/silvestr3/caramelo2-public)

  ## How to start

This configuration will automatically spin up both the API and Web client, along with the PostgreSQL database to run the application on Docker containers. Make sure to have both Docker and docker-compose installed and available.

1. Build the containers:
```bash
docker-compose up --build -d
```

The application will be available on `localhost:3000`
