# Polar Analytics Technical Test

## Welcome

Thank you for taking the time to do this technical test. We tried to make it both fun and interesting, so we hope you'll like it. It has 2 different task blocks: one consisting of Backend work, and one consisting of Frontend work. Depending on what position you are applying to, you might not need to do both. If you decide to do only the front end block, you can simply mock the values that should be coming from the API.

It is ok if you cannot do all the tasks, but the code you decide to send us should be production ready.

At Polar, we work with React, NodeJs, and TypeScript. But for this test, feel free to use the tech you are the most confortable with; you will be judged on result and code quality, not on the tech stack.

Please try to not use third-party npm packages unless really necessary. We prefer an ugly UX than a copy-paste from Material UI.

Please, push your work to a **private** git repo, and share it with us:

- scalpweb@gmail.com
- charbel@polaranalytics.co

**[IMPORTANT]** It should contain a README file explaining how to run your code.

Thanks again, and have fun!

# FaST Inc

Congratulations! You've been chosen to work at the new Emon Lusk's start up, FaST Inc (standing for Fast Spatial Travel Incorporated).

Engineers have recently found a way to travel faster than light between different points of the Universe, called Space Doors, via a new type of engine called BaguettePropulsers. Those engines are using a very special type of fuel, a french cheese called Camembert: to travel from one space door to another, you need to feed your BaguettePropulser with one or more Camembert. It is a fantastic opportunity for humanity (and Camembert producers)!

As the new software engineer, you'll be in charge of building an API and a User Interface to help space pilots traveling through the Universe.

# Travel API

On start up, your API should load a JSON file containing the mapping of all the different Space Doors available in the Universe. Each Space Door can be connected to 0 or many Space Doors, for a given cost in Camembert. You can find an exemple of this JSON file in this repo: `space-time-continuum.json`. Feel free to edit it if you feel like doing so. In real situation, it would probably contain a lot more Space Doors...

You are free to organize and build your API the way you want, but it should be able to do the following operations via HTTP endpoints:

- get the entire universe mapping,
- for a given start Space Door and a given amount of Camemberts, list all the accessible Space Doors;
- for a given start Space Door and a given end Space Door, get the path between those 2 locations that is the cheapest in Camemberts;

We expect your API to deal with any possible error properly.

# Travel UX

In their Spacecrafts, pilots have access to a User Interface. It helps them to feed their BaguettePropulsers and to find their way through the Universe. A Spacecraft starts at a random position in the Universe.

You are free to organize and build your User Interface in any way you want, but it should give its users the ability to:

- visualize the Universe mapping,
- see where they can go with a given amount of Camemberts,
- visualize a path between 2 Space Doors,
- move to another Space Door (if possible).

Note: we are not applying to a designer position, so it's ok if the UX is not beautiful. However, it should be practial.
