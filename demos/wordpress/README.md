# Wordpress DEMO
# Start
* In CLI: `docker-compose up`
* Background `docker-compose up -d`
* Navigate to: http://localhost:8000/

## Shutdown and cleanup
The command `docker-compose down` removes the containers and default network, but preserves your WordPress database.

The command `docker-compose down --volumes` removes the containers, default network, and the WordPress database.