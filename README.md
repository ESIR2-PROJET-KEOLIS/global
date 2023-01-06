# Keolis Simulation App System

## Development launcher

- Clone this repository with all the submodules. (you may need to create a personal key configured to be authorized to read and write for this github organization)
- Package the project processing-storage-unit with `mvn package`. This will generate a jar file in the target folder.
- Create a .env file in frontend folder with the following content:
```
MAPACCESSTOKEN: pk.eyJ1IjoiamVhbmJvbWJldXIiLCJhIjoiY2xiY2VwbTR5MDN0bTNvbTlnbjVlejBvaiJ9.GI7swTCiubp19sXemS4NIw
```
- Run the docker compose file with : `docker-compose up`

## Production launcher
Not ready for now.