**1. Creating a Container & Communicating to the Web (WWW)**
`2. docker build -t favourite-node .
3. docker run --name favourites -d --rm -p 3000:3000 favourite-node`
4. WORKS!
5. docker ps => no container running
6. docker run --name favourites --rm -p 3000:3000 favourite-node - without detached container
7. MongoNetworkError: failed to connect to server [localhost:27017] on first connect
8. Not connecting to server
9. docker build -t favourite-node .
`10. docker run --name favourites -d --rm -p 3000:3000 favourite-node
11. docker ps => container running `