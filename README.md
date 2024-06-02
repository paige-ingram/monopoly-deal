# monopoly-deal

A machine learning model to predict the winner of a 1 vs 1 Monopoly Deal game based on a number of input features.

## Description

This project was inspired by a heated discussion about whether the Monopoly Deal is a skill-based game or primarily luck. The luck advocate argued that the winner of a game can be predicted based on the number of 'wild property' cards, 'deal breaker' cards, and 'just say no' ('je refuse') cards that each player has in their hand throughout the duration of the game. To solve this dispute, we played 18 rounds of Monopoly Deal and kept track of these parameters and the winner of each game. 

# The Data

| Data label                       | Description                                                    |
| -------------------------------  | -------------------------------------------------------------- |
| game_id                          | arbitrary id to identify game                                  |
| A_win                            | boolean value to indicate whether player A won (1) or lost (0) |
| A_wild                           | number of 'wild property' cards player A had                   |
| A_db                             | number of 'deal breaker' cards player A had                    |
| A_refuse                         | number of 'just say no' ('je refuse') cards player A had       |
| B_wild                           | number of 'wild property' cards player B had                   |
| B_db                             | number of 'deal breaker' cards player B had                    |
| B_refuse                         | number of 'just say no' ('je refuse') cards player B had       |

Player A and player B were kept consistent throughout the rounds. Each player played to the best of the ability at all times. 

## The Game
![monopoly-deal](https://github.com/paige-ingram/monopoly-deal/assets/77078416/25389d6a-05aa-45e8-a83b-1a6fbeede564)

For more information about the rules of Monopoly Deal, click [here]([url](https://www.monopolydealrules.com/index.php?page=play)). 
