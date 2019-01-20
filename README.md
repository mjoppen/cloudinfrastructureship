# cloudinfrastructureship
# Why
This is a nice picture for presentations for people who do not know a lot of microservices, container, orchestration.
I use it as one of the last agenda points as the big picture in the end of an overview presentation, where microservices, container and orchestration are explained. In this case the target audience is operations.
The goal is to get the teams, that deploy and operate the software, Security and Infrastrucutre to find themselfes in the cloud infrastrucutre world to erase fear and give them the possibility to take the next steps.

# What do the people have to know?
The people have to know on a really high level what a microservices, docker, kubernetes(pods, deployments, ingress) is.

# Text while drawing

This is Frank. Frank has a petting zoo in Minesota.
It´s the best petting zoo one can ever imagine, people from all over the United States come to visit his zoo but he is an enterpreneur and really wants to conquer the whole world with his petting zoo.
So he plans a tour to spots around the world with his first stop in Germany.

So he needs a boat. He drives to the boat using a truck. The captain greets him.
The first animals are transfered to the ship using a crane. 
There is a horse and a cat, but they don´t like each other so they are devided by a fence. They still hear and see each others.
Animals love to run around but that is not a good idea, so they are put in boxes. 
The boxes have windows so they still can breathe, hear and see what is around them.
Because the horse tends to be lonely, his friend the rabbit sits in a cage next to him.

Animals need food, so the boat has some animal keepers and food in a cold store with it.
Because the animals love food(the horse stole a lot of carrots for him and the rabbit out of the barn) and the animal keepers need their quiet time, they are stored below in different sections divided by a big wall. 

The harbour master checks the containers, so that no trafficers add rhinos or other endangered species to the ship.
Because the crane operator was drunk too often, he decided to replace him with a robot. Now there is a guy programming the robot.

So that the captain is not washed away by big waves, he has a cab.

The ship is now ready to go.

# Explaining (draw descriptions)
As you can imagine, the animals are not animals but applications.
The boxes in which the animals live are containers.
The fence between the horse and the cat is marking the app-pods and their services.


Frank is a product owner who wants to spread his product, the petting zoo is the version control system.
The truck and the crane resemble the build and deployment process, the harbour manager is a security scanner and all together they form the CI/CD suite with a pipeline.

The cab of the captain is the DDOS protection.

We are having three different systems devided by namespaces, the animals, the animal keepers and the food.

# Talking architecture(keep drawing descriptions):
We have an online shopping platform 
The animals form the first system, a web-frontend, where the horse and the cat form the apps A and B, the rabbit is a sidecar container for example a monitoring agent for A deployed in the same pod.

The animal keepers are a search engine searching over the food that is the product data of the products, that we are selling. 