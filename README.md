# ADVENT-Flex
Colossal Cave Adventure for the FLEX with some fixes 

## Background
This was an original port that was made for Introl C compiler. It was designed to work on Introl C compilers. The original author (Joseph M Aulicino) did couple of modification including saving and loading the game. It was tested on /09 computers 

Unfortunately this did not work as the assumption made by Joseph was not valid for those computers but it is not valid for FLEX. So in this modified version , we changed the save function as the memory addresses for the variables aren't in sequence. Therefore, we had to store them individually and load them back

Additionally FLEX only stores in upper case. To make it easier for users to play the game, we made all the save/load files to be in Upper Case 


###  TO DO
Implement get all to grab all the items
Skip the tutorial when you load the game 
