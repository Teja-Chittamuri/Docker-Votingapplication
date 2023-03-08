This repository is mainly to explain the process of using docker-compose to deploy Multi-Tier voting application using a single docker-compose command.
services:
  1. VotingPage --- Frontend
  2. Redis   --- cache 
  3. Db  --- To store the vote
  4. Workerole -- To process the vote from redis-db.
  5. ResultPage  -- Frontend

* For docker images you can refer tejachittamuri repository in Dockerhub. I built the docker images from the src code and I pushed them to my dockerhub repository.


Happy Learing :)

