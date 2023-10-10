### How to start
1. `git clone https://github.com/joelhackinen/projecthub-test.git`
2. `cd projecthub-test`

#### in development mode
3. `cd react-app && yarn` (needed only when launching for the first time after cloning/pulling)
4. `cd ..`
5. `docker compose up -d --build`
6. application is running at http://localhost:8080/
  
#### ...and in production mode
3. `docker compose -f docker-compose.prod.yml up -d --build`
4. application is running at http://localhost:8080/
