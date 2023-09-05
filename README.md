# citus_docker_example
This is an example of how to implement Citus at docker, using yml file to set the configuration

Run command :
docker-compose -f docker-compose-citus.yml -p citus up --scale worker={{number-of-worker}} -d