This repository is mainly to explain the process of using docker-compose to deploy Multi-Tier voting application using a single docker-compose command.
services:
  1. VotingPage --- Frontend
  2. Redis   --- cache 
  3. Db  --- To store the vote
  4. Workerole -- To process the vote from redis-db.
  5. ResultPage  -- Frontend

* For docker images you can refer tejachittamuri repository in Dockerhub. I built the docker images from the src code and I pushed them to my dockerhub repository.

![image](https://user-images.githubusercontent.com/111578142/223795112-d943fd58-2fd9-4281-93f3-c24284cf5336.png)
![image](https://user-images.githubusercontent.com/111578142/223795211-d3a65060-dfd6-4bea-b942-642a1b6878f2.png)


Happy Learing :)

