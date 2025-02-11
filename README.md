# Chips Challenge

## Description
Birds eye tile game inspired by [Chips Challenge](https://en.wikipedia.org/wiki/Chip%27s_Challenge) written in Java for the 2022 SWEN225 Group project.

## Demo

![](./readmeAssets/chipsChallengeDemo.gif)

## My module: Persistency
Persistency handles saving and loading games, this was done by utilising the Jackson Xml serialization and deserialization library and attaching custom serializer and deserializer to main game entities in order to save and load them into the game, then using a Facade esque pattern where other modules can simply call load and save methods.

## Setup / Install / Run
First clone the repo and open in chosen ide.

Start the game by running nz.ac.vuw.ecs.swen225.gp22.app.Main from your chosen IDE.

To play the Game select from level 1 choose "Start Game", to Load a game choose "Load game" and to play a recorded game choose "Load recording".

The keys for this game are the up, down, left and right arrow keys.

To keys for Replay of Recorded Game once Recording is loaded:
"-" to decrease Automatic ReplaySpeed, "+" to increase Automatic ReplaySpeed
"." to replay one single step forward at a time with each press
"," to replay one single step backwards at a time with each press


If the game does not compile, please make sure the Project structure for the Modules looks like this:

![](./readmeAssets/Libraries_example.png)

And the Libraries looks like this:

![](./readmeAssets/Modules_Example.png)



The Gource video can be found here: https://www.youtube.com/watch?v=_bWZLoOOn_U
