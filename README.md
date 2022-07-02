# docker-compose-ecs-test
Testing deploying from docker-compose.yml -> ecs

# Resources
[Docker docs on compose to ecs](https://docs.docker.com/cloud/ecs-integration/#install-the-docker-compose-cli-on-linux)


# Commands

Docker compose commands work the same locally (and in CI) as they do on AWS. e.g

## Command to run in ECS:
`docker --context myecscontext compose up`

## Command to run locally: 
`docker compose up`

## Logs

`docker --context myecscontext compose logs -f`

My version of this (might be) available [here](http://docke-loadb-1f34yn6zqt1t3-1572820821.us-west-1.elb.amazonaws.com/)
