# Natural-Selection-Simulation
## Leo Guagenti - 5/22/19
This is a basic simulation of how natural selection works in real life.<br>
Using simple variables that may mutate such as view distance, speed, view twitch, and some others, I was able to create an environment that favors 'organisims' with more favorable traits for the environment.<br>
The demo for the simulation can be found here --> https://leoguagenti.github.io/Natural-Selection-Simulation/

__Rules of the simulation:__<br>
* Every 'organisim' has a view distance, speed, travel direction, current food level, and a desired food level (needed to reproduce)<br>
* When an organisim reproduces, another organisim with slightly 'mutated' versions of the parent's genetics is produced<br>
* In order to reproduce, an organisim must find its way to food (represented by a small purple dot)<br>
* The organism may only see the food and travel toward it if the food is within the viewing distance of a given organism.<br>
* While searching for food, the organism's current food level decreases (supposedly due to movement energy). If the organisims food level reaches below the value 3, then the organism will die, spawning a food partical in its place.<br>
* The three numbers that appear by each organism represent (from top to bottom) Generation Number, Current Size, and Desired Size

__Where i'd like to take this:__<br>
Currently i'd like to implement a way for the organisims to eat one another and to flee when a larger organisim is within viewing<br>
