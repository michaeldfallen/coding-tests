#Connect 4 Game Service
This coding test is to build a simple Connect 4 game.
The features of the service are documented as [User Stories]. There are some 
[technical requirements] that we require you adhere to. Finally we have some 
[expectations] that describes what we expect from you.

## Game Rules 

- The game is played on a vertically suspended seven column by six row grid.
- The game is for two players.
- Players choose a colour 
- Players take turns dropping a disc from the top into any non full column  
The pieces fall straight down occupying the next available space in the column
- If a column is full no further discs can be dropped into that column
- The objective is to get four of your coloured discs in a row: horizontally vertically or diagonally.


## User Stories 

*As a* Player  
I *need* to be able to start a game  
so *that* I can play Connect 4 with a friend

*As a* Player  
I *need* to be able to drop my colour disc into a non full column on a gameboard that my friend or I 
have started  
so *that*  I can participate in a game of Connect 4 with a friend

*As a* Player  
I *need* to be able to determine the outcome of the game  
so *that* I know if I have won , lost, or drawn.

*So that* games of Connect 4 can be played  
*the* Game service  
*will need to* enforce the rules of Connect 4

*So that* many people can play at the same time  
*the* Game Service  
*will need to* support multiple concurrent games


## Technical Requirements

- The test should be coded in Java 8.
- Clients will interact with the game service via a RESTful API.

## Expectations
All of these expectations are up to your own judgement. If you think you should,
you may deviate from these expectations but expect us to  challenge you on why you 
have made that change.

### We expect:
- Production quality code.
- A Readme that describes what you've built,any assumptions you've made  and details about your RESTful API.

### We don't expect:
- The game service to be deployed anywhere.
- A user interface.
- Any form of automated (AI) player for the game.
- Data to be persisted in a database
- Exhaustive documentation

We have expectations that we have not documented here. Use your best judgement.

[user stories]: #user-stories
[technical requirements]: #technical-requirements
[expectations]: #expectations
