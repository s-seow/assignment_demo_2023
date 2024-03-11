# TikTok Assignment 2023

![Tests](https://github.com/TikTokTechImmersion/assignment_demo_2023/actions/workflows/test.yml/badge.svg)

This is the completed backend assignment of 2023 TikTok Tech Immersion.  It is about creating an Instant Messaging System using Golang, Protobuf, Kitex, Redis and Docker.

## To-Do

• Setup Database and establish connection with the RPC Server. Once this is setup, we will have 4 containers running - http-server, rpc-server, etcd-container, db-container.
 
• Update the business logic in handler.go - instead of using the placeholder areYouLucky(), we will be implementing our own logic here to a) send message and b) pull messages to/from the database.
 
• Manual Testing via Postman/Unit Testing/Tidy up README.md
 
• Rebuild the docker image via docker-compose build and then re-run the containers via docker-compose up, in order to reflect changes to the code.
