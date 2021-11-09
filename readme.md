# readme

Repo containing docker compose and global test files
Camunda imgage is sourced directly or built in other repo
Controller is built as docker image in other repo


Docker compose docs: https://docs.docker.com/compose/

docker compose up

docker pull camunda/camunda-bpm-platform:latest

camunda
 - for running the processes

neo4j
 - for describing resources and their relation to tasks

controller
 - for executing the processes
 - used to queue events

mongo
 - for storing executing logs


## Test 1 
 - start compose
 - post simple process
 - execute process
 - check output