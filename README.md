# Rappi Challenge Process Interview, 2020

Este es el repo del video acerca del challenge de Rappi para su proceso de reclutamiento como iOS Software Engineer en México 🇲🇽

Video del repo: https://youtu.be/5qXzjUyYf1k


## Challenge

*"Team Formation 2"*

FC Codelona is trying to assemble a team from a roster of available players. They have a minimum number of players they want to sign, and each player needs to have a skill rating within a certain range.
Given a list of players' skill levels with desired upper and lower bounds, determine how many teams can be created from the list.

**Example**

skills = [12,4,6,13,5,10]

minPlayers = 3

minLevel = 4

maxLevel = 10

- The list includes players with skill levels [12,4,6,13,5,10]
- They want to hire at least 3 players with skill levels between 4 and 10, inclusive
- Four of the players with the following skill levels {4,6,5,10} meet the criteria
- There are 5 ways to form a team of 3 players: {4,5,6}, {4,6,10}, {4,5,10}, {5,6,10}, and {4,5,6,10}


## Tests

**1**

skills = [6, 4, 8, 7, 5, 2]

minPlayers = 2

minLevel = 3

maxLevel = 10

**2**

skills = [248, 779, 392, 727, 561]

minPlayers = 2

minLevel = 3

maxLevel = 1000

**3**

skills = [4, 8, 5, 6]

minPlayers = 2

minLevel = 7

maxLevel = 8

**4**

skills = [4, 8, 5, 6]

minPlayers = 2

minLevel = 5

maxLevel = 7

## Resultados

26

11

0

1
