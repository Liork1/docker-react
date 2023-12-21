# Getting Started with docker frontend app

## uisng Docker

### `docker build -f Dockerfile.dev .`

Building an image based on the Dockerfile.dev

### `docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app 7918e9dcfed0192ff1e1cbef360aa8d66df42a8ac25ff03b2b409a59ff50434e`

#### variable:

`-p 3000:3000`: mapping the inner 3000 port to external port

`-v /app/node_modules`: don't refernecne theis folder to a local folder

`-v $(pwd):/app`: reference all folder inside the Print Working Directory (pwd) to app folder inside the container

`7918e9dcfed0192ff1e1cbef360aa8d66df42a8ac25ff03b2b409a59ff50434e`: image id creating in previous step


## using Docker Compose

run `docker-compose' up
