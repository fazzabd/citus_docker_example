# citus_docker_example
This is an example of how to implement Citus local cluster at docker, using yaml file to set the configuration

Run command :

`docker-compose -f docker-compose-citus.yml -p citus up --scale worker={{number-of-worker}} -d`
