# Name TBD
  - Tech: Unity
  - Platform: Android / IOS

# Game
  - Era: Roman Age
  - Type: RPG / Management / ?Fantastic?
  - Turn by turn
  
# Main Goal
The goal of the player will be to survive the last Barbarian attack. In order to reach this attack, he will have to transform his initial small encampment into the new Rome. In order to do so, he will have to go through different levels of city.
  
# City Levels
When the player gains a level, new technologies and new events will be unlocked.
  - Encampment (5-30 people)
  - Small village (30-100 people)
  - Village (100-500 people)
  - Town (500-1000)
  - City (1000-2000)
  - The new Rome (2000+)
  
To gain a level, the player will have to pay a tribute to the person reigning over the area where the city is located. At some point, the player should be powerfull enough to beat him in a war. The player will have to chose if he wants to keep paying this tribute or if he wants to defeat him and take the control of the area.
    
# In Game Loop
One turn will be one season. Every turn the player will have to make two choices which will have an impact on the big event. There will be one big event per season and it will be positive or negative depending on what choices the player makes. The player's behaviour will be judged with four sliders:
  - Happy / Angry
  - Security / Crime
  - Diplomatic / Rude
  - Healthy / Unhealthy
  
In addition to these events, the player will have to manage different ressources that will influence on these sliders. These ressources are:
  - Population
  - Food
  - Army
  - Money
  
# Sliders
Each slider will vary between 0% and 100%. When a slider goes below 50% related bad events will be unlocked. In the opposit, when a slider goes above 60% related good events will be unlocked. In order to continue his game, the player will have to maintain each of his sliders as close to 60% as possible. Impact of the event will depend on the sliders status.
- Happy / Angry: Represents how your population is feeling. Wars, food, money and health will change this slider.
- Security / Crime: Represents how your population behaves. Army, happyness and money will change this slider.
- Diplomatic / Rude: Represents how other countries feel about you. Army, wars and overall power will change this slider.
- Healthy / Unhealthy: Represents how healthy your population is. Food, money and buildings will change this slider.

# Ressources
Ressources are as important as sliders. They will higly affect the slider's status. In order to survive bad events, you will need enough of each ressources. 

# Background
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
  - Farming: Will give bonuses related to the food. More food producted, less population needed to product.
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

- The production building's (Farms, Barracks and Markets) bonus will also depend on how many citizen are working there. In order to have   a bonus the player will have to affect at least one citizen to this building. Then if he wants to affect more citizens to this           building, it's income will be multiplied by the amount of citizens. The maximum number of citizens per building will be of 5.

# Ideas
## City council
- Composed of 4 people. 1 for each ressource.
  - Prime Minister (population)
  - Farming Minister (food)
  - Army Chief (army)
  - Economy Minister (money)
  
The most the player have of one ressource, the more power the person represented by this ressource have. Every year, each one of them will give the player a mission. The difficulty of the mission will depend on how important the person is. Suceeding in the mission will increase the dedication of the person to the player while failing it will decrease it. If a very powerfull person doesn't have enough dedication to the player anymore, he will take control of the city and the player will lose the game. The more powerfull a counceler becomes, the more dedication will be needed for him not to betray the player.

## Houses
When the habitation level goes up the sanity and the tax income as well.

## Tax Income
As the title says.

# Technology Ideas
## Spying 
- 4 levels of spying. The higher the level of spying gets, the most precise the information you will have about your enemies. Will be in the bonus tree.
  - Level 0: No information at all.
  - Level 1: Rough estimation. Ex: 100-200 soldiers
  - Level 2: Precise estimation. Ex 100-150 soldiers.
  - Level 3: Very precise estimation. Ex 100-120 soldier

# Event Ideas
