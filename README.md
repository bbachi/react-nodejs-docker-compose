# react-nodejs-docker-compose
Example project on how to develop project on Docker Compose

See the tutorial [here](https://medium.com/bb-tutorials-and-thoughts/react-local-development-with-docker-compose-5a247710f997)

## Run locally

```shell
// install server side dependencies and start
cd api
npm install
npm run dev
// install react dependencies and start
cd my-app
npm install
npm start
```

## Run with Docker-compose

```bash
docker compose up -d
```
