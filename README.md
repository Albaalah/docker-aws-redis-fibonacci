# docker-aws-redis-fibonacci
A simple fibonacci app using complex architecture

### In main folder
To run fibonacci app with docker compose in development mode
 - To build and run
    `docker-compose up --build`
 - To only run if it is built
	 `docker-compose up`
 - To gracefully stop all containers
	 `docker-compose down`
 This will launch the app at [http://localhost:3050](http://localhost:3050)
### In each folder
To run docker in development mode for client, server, and worker
 - To build
    `npm run docker:build`
 - To run
	 `npm run docker: run`
