`docker build -t ci-node-app .`

`docker images`

`docker run -d -p 3000:3000 --name node-container ci-node-app`

`docker ps`

`docker logs node-container`
