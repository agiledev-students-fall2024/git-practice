# Git Practice

Article [link](https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud)

### Why I find this article interesting
I find this article interesting because we briefly touched up on the microservices architecture during the lecture, and I find this to be a very interesting application of microservices. The use of microservices at SoundCloud at a large scale demonstrated the pros and cons of using microservices, and how it can (potentially) be beneficial for a large scale application.

The article discussed how SoundCloud uses "BFF" (Backend for Frontend) to handle the different clients that SoundCloud has. This is interesting because it shows how SoundCloud uses microservices to handle the different clients that they have, and how they can scale their application to handle the different clients that they have.

The article also highlights both the benefits and drawbacks SoundCloud experienced when adopting microservices. One of the key benefits is scalability; by breaking down services into smaller, independently deployable components, SoundCloud could scale different parts of their system based on specific demand. This modularity also made it easier for teams to develop, deploy, and maintain services without impacting others, increasing overall agility, which speaks to the benefits of microservices in general.

However, the drawbacks of microservices became apparent as well. One major challenge SoundCloud faced is the complexity in managing their distributed systems. As the number of services grew, so did the difficulty in monitoring, debugging, and ensuring reliability across the system.