#README.md

This is a companion repo for a blog post on Grafana.

# Notes

Inside docker compose containers are registered as though their container name is their hostname. 
`http://prometheus:9090`
The above is how you would access prometheus from another container inside docker compose.

# Running 

In the root of this repository run the `docker-compose up` command.

# Stopping
Run the `docker-compose down` command.