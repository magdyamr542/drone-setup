# Setting up a drone server with runners locally

1. Create Github Oauth. Setup from [here](https://docs.drone.io/server/provider/github/)
1. App is [here in github](https://github.com/settings/applications/2215417)
1. Configure ngrok to get a domain name Github can access. `ngrok http 8080`
1. Provide the .env variables that are used in the `docker-compose.yml`

### Running

- `docker-compose up`
