---
title: Hosting tournaments
date: 2019-10-09 23:08:27
---

### Hosting tournaments with Pantheon

#### 1. General.
- The system can work in two modes: club games mode and tournament mode. In tournament mode, there is a timer, a possibility to make automated seatings, but no possibility to add a new player at any moment of the tournament.
- Hanchan length is 90 minutes (can be configured). 
- For tournament, a set of predefined seating rules is available. Also, tournament can use manually-made seating.
- Tournament winner is determined by the largest number of points by the end of the tournament (including uma, chombo, etc.).
- Uma - 15000/5000 (can be configured).

#### 2. Players registration
- For either tournament or club games administrator should register all players beforehand in the "Add player" page. To add a player to rating use the "Add to current rating" button.
- If the required player is not on the list, you should use a registration form at the bottom of the page. 
    - Fill the "Real name" field with the required player’s full name.
    - Fill the "System name" field with shortened login-like name, which in most cases should be formed as “the first letter of name + surname”, all on lowercase. For example, Alex Jones’s system name will be “ajones”.
    - If the system tells you that this system name is already in use, make it “two letters of name + surname” and so on.
- If additional players appear on the day of the tournament, they should also be registered in the same manner.
- After all the players are registered, the administrator should go to the "Manage players" page, where he can find a list of confirmed and non-confirmed players.
    - For every non-confirmed player, there is a personal pin code. This pin code should be given to a player personally.
    - When player Logs in using his pin code his participation is confirmed automatically - after that player can be found in the rating table.
    - If a player has no mobile device to log in, the administrator can confirm his participation manually in "Manage players" page using a corresponding button near a player’s pin code.
- System won’t allow starting a tournament if the number of confirmed players is not a multiple of four. If needed, the tournament administrator can remove some players or add new players (substitute players). 
- System won’t allow to add or substitute a player after games have already started. 
    - If a player leaves the tournament before the tournament ends, his pin should be generated anew and given to the substitute player. After that, he should be penalized after each round depending on the tournament rules (more about penalties later). Please contact Pantheon administrator (Oleg Klimenko) in case you need to make a substitution after the tournament has already started.

#### 3. Tournament process
- Tournament game has 5 possible states: 
    - “Not started”: in this state, seating is generated (automatically or manually).
    - “Seating generated”: seating is prepared, but the timer is not running yet, “Start games” button is available.
    - “Started”: games are started, the timer is running. A button to reset the timer is available.
    - “Prefinished”: all games are finished, but there is still a possibility to cancel last rounds. “Finish” button is available.
    - “Finished” - same as “Not started”.
- Each player can see his table’s number in the bottom left corner of his mobile device.
- Timer and seating are available for each player on his mobile device and also to tournament administrator on "Timer and seating" page. This page can be shown to the whole tournament lobby using a video projector or any similar device.
- Games start when tournament administrator presses “Start timer” button.
- **!!!** Players should be explained what Yellow zone is. According to EMA rules, a signal sounds indicating that there are 15 minutes left before the end of the tour. This means that players can finish their current hand and play one more hand.
    - Yellow zone is issued for all tables simultaneously 15 minutes before the end of a round - that means you can finish no more than two hands. 
    - After first hand is submitted in Pantheon, the timer becomes Red, which means there is only one hand left before hanchan ends.
    - Red zone (unlike the yellow zone) is not simultaneously for all the tables - each table reaches it when it has submitted its first game.
    - Time as a whole (in administrator Timer page) is not affected by Yellow or Red zones.
- If needed, players can receive penalties (for example, for being late) in a range from 100 up to 20000 points - use “Penalties” page for that. 
    - Penalties can be seen for every player in statistics.
    - Penalty can only be issued during a game. If a round is already finished, it is impossible to issue a penalty before the start of the next round.
- Tournament administrator can monitor tables statuses on "Start games" page. Until all tables finished playing, the next round cannot be started.
- In case players have made a mistake in the hand submission, the administrator can cancel last submitted hand. It can be done in the "Games control panel" page with the "Cancel last played round" button.
    - Players should be informed that to correct such mistakes it is necessary to call for the administrator because he is the one making decisions about hand cancellations.
- In case player’s mobile device became inaccessible for some reason (low battery, for example), it is possible to reissue new pin code for a player during the outgoing game. This can be done by the administrator in the "Manage players" page using the "Reissue PIN" button for the required player.
    - Note, that when a player logs in using his pin code on one device, he will be automatically logged out on all other devices. There is no support for simultaneous login from several devices for now.
    - It is not recommended to use incognito mode in your mobile browser to avoid accidental logouts that can be fixed only by reissuing new pin code by the administrator. 

---------------------------

Big thanks to Pavel Bogachev for the translation of this guide.