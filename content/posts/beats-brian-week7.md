---
tags: ["Brian Sandoval", "BEATS", "Week 7"]
---
## Week 7 blog

#### The overview

This week I was assigned to setting up the ecr as well as helping erik set up the ecs.  So far we were able to initialize the cluster on the aws console and set up the ecr environment to some extent. We had a bit of issue setting up the ecr or starting it off with the code that we were using was not being able to initially set up the ecs we had to make sure that the user data tag was being filled in with the shell that we were using. We were able to setup some services and roles but have not fully been able to create the necessary roles for the rest of our ecs. Afterwards we didn't have to much of an issue we were able to set up the repository although it is blank right now and we as well specified our domain url that it will be using. What me and Erik are currently stuck on is that we need to be able to get the docker image so that we can start testing our environment more in depth currently we are a bit stuck on what to move forward with. Currently I am trying to set more services and roles up just so we can progress further that way there is not as much work left after the docker image is available.  

#### Future Plans
We are hoping that the docker image is finished by this weekend since we are currently stumped on configuring the ecr. When setting up the ecr we want to be able to make sure that all our roles and services are specified and running on our ecr. Furthermore we want to finish both the ecs and ecr configurations so that Tyler can start deploying the lambda part since we are thinking that is what will take up moore of the time and a bit more of the challenging part.   
