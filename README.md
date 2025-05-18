## Run the auth server

Install docker

Run the docker compose command to start the auth server

``` bash
docker-compose up -d
```

Import the configuration using Keycloak admin console
1. Open the Keycloak admin console at `http://localhost:8080/auth/admin/` 
2. Login with the admin / admin credentials
3. Select the realm
4. Go to the Clients tab
5. Click on the `Import` button
6. Select the clients/ json files and import each of them

## Run the sample Web Page

``` bash
# Install http-server globally
npm install http-server -g
http-server -p 5500
```

## Run Postman collection
1. Open Postman
2. Import the Postman collection from the postman/ folder