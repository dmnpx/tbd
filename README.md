# Name TBD
  - Tech: Unity
  - Platform: Android / IOS

# Game
  - Era: Roman Age
  - Type: RPG / Management / Fantastic?
  - Turn by turn
  
# Main Goal
The goal of the player will be to survive the last Barbarian attack. In order to reach this attack, he will have to transform his initial small encampment into the new Rome. In order to do so, he will have to go through different levels of city.
  
# City Levels
When the player gains a level, new buildings, new ressources and new events will be unlocked.
  - Encampment (5-30 people)
  - Small village (30-100 people)
  - Village (100-500 people)
  - Town (500-1000)
  - City (1000-2000)
  - The new Rome (2000+)
    
# In Game Loop
One turn will be one season. Every turn the player will have to make two choices which will have an impact on the big event. There will be one big event per season and it will be positive or negative depending on what choices you make. Your behaviour will be judged with four sliders:
  - Happy / Angry
  - Security / Crime
  - Diplomatic / Rude
  - Healthy / Unhealthy
  
In addition to these events, the player will have to manage different ressources that will influence on these sliders. These ressources are:
  - Population
  - Food
  - Army
  - Money
  
# Classes
When beginning a new game, the player will have the choice between classes. Depending on which class he choses, different bonuses and maluses will have an impact on the player's sliders and ressources:
  - Warrior:
    - Bonus: More starting soldiers units and the player will have access to level 2 barracks from the beginning. The Security slider       will be at 75%.
    - Malus: Less starting money. The Diplomatic slider will be at 25%.
  - Farmer: 
    - Bonus: More starting food and access to level 2 farms. The Happy slider will be at 75%.
    - Malus: Less starting soldiers units. The Health slider will be at 25%
  - Rich Heir:
    - Bonus: More starting money and access to level 2 markets. The Diplomatic slider will be at 75%
    - Malus: Less starting population. The Happy slider will be at 25%
  - Normal:
    - Bonus: none
    - Malus: none
  - God Gifted (unlocked after losing five games):
    - Bonus: Starting with more of every ressource and access to all level 2 buildings. Every slider starts at 75%
    - Malus: None
  - Hardcore (unlocked after reaching New Rome twice without using the God Gifted class):
    - Bonus: none
    - Malus: Less of every ressource. Every slider starts at 25%
  
# Competence Tree
The competence tree will be divided in five parts:
  - Population: Will give bonuses related to the population. Making them more productive, healthy, happy and less hungry for example.
  - Farming: Will give bonuses related to the food. More food producted, less population needed to do food.
  - Army: Will give bonuses related to the army. Allow to product more units per turn, cheaper units.
  - Economy: Will give bonuses related to the money. More money produced per market, less people required in markets.
  - Bonus: These technology will be particular ones. They will cost a lot more but will give a big bonus. They could directly infect the   sliders.
  
The player will have different ways of obtaining new technologies. The easiest one is buying them with money. But he could also decide to buy them with other ressources. If he does so, it could have an impact on the sliders depending on what he uses and in what quantity. Some technologies will also be dropped after events.
  
# Buildings
- Before ending his turn, the player will be able to build new buildings that will be available in the next turn. The amount he will be able to build will depend on how many citizens are affected to building.

- When the new turn begins, the player will decide what he wants to turn the new buildings in. There are 4 choices:
  - Habitation: Will increase your population
  - Farms: Will increase your food
  - Barracks: Will allow the player to transform people in soldiers
  - Markets: Will increase your money
  
- The bonus given by a building will depend on the building's level. In order to improve a building, the player will have to unlock the   improvement via the technology tree. Once the improvement is unlocked, he will pay for each building he wants to improve.

- The production building's (Farms, Barracks and Markets) bonus will also depend on how many citizen are working there. In order to have   a bonus the player will have to affect at least one citizen to this building. Then if he wants to affect more citizens to this           building, it's income will be multiplied by the amount of citizens. The maximum of citizens per building will be of 5.
