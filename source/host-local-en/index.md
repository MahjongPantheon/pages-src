---
title: Hosting local games
date: 2019-10-09 23:08:39
---

### Hosting club games with Pantheon

#### 1. General.
- The system can work in two modes: club games mode and tournament mode. In club games mode there is no timer, no possibility to make automated seatings, but there is a possibility to add a player at any time.
- Club games rating is based on the sum of the player’s points from all of his games.
- Uma is 15000/5000 (can be changed).
- To log in from mobile devices default Pantheon address is used: https://m.riichi.top 

#### 2. Players registration
- For either tournament or club games administrator should register all players beforehand in the "Add player" page. To add a player to rating use the "Add to current rating" button.
- If the required player is not on the list, you should use a registration form at the bottom of the page. 
    - Fill the "Real name" field with the required player’s full name.
    - Fill the "System name" field with shortened login-like name, which in most cases should be formed as “the first letter of name + surname”, all on lowercase. For example, Alex Jones’s system name will be “ajones”.
    - If the system tells you that this system name is already in use, make it “two letters of name + surname” and so on.
- After all the players are registered, the administrator should go to the "Manage players" page, where he can find a list of confirmed and non-confirmed players.
    - For every non-confirmed player, there is a personal pin code. This pin code should be given to a player personally.
    - When player Logs in using his pin code his participation is confirmed automatically - after that player can be found in the rating table.
    - If a player has no mobile device to log in, the administrator can confirm his participation manually in "Manage players" page using a corresponding button near a player’s pin code.

#### 3. Games process
- In club games mode players can start games by themselves using the “New game” button on their mobile device. After that, a player should choose his opponents (note that there are only confirmed players on the list). It is also possible to randomly shuffle players’ starting winds before the start of the game.
    - In case players made a mistake regarding the seating or added a wrong player, they should ask the administrator to cancel the game. It can be done in the "Games control panel" page with the "Cancel game" button. This button would be available only if no hands were played yet (or all hands were canceled, see below).
- In case players have made a mistake in the hand submission, the administrator can cancel last submitted hand. It can be done in the "Games control panel" page with the "Cancel last played round" button.
    - Players should be informed that to correct such mistakes it is necessary to call for the administrator because he is the one making decisions about hand cancellations.
    - Note that there is no possibility to cancel the last hand in the game in club games mode for now. This may change in the future, but for now, players should be extra careful when they enter last hand results.
- In case player’s mobile device became inaccessible for some reason (low battery, for example), it is possible to reissue new pin code for a player during the outgoing game. This can be done by the administrator in the "Manage players" page using the "Reissue PIN" button for the required player.
    - Note, that when a player logs in using his pin code on one device, he will be automatically logged out on all other devices. There is no support for simultaneous login from several devices for now.
    - It is not recommended to use incognito mode in your mobile browser to avoid accidental logouts that can be fixed only by reissuing new pin code by the administrator. 


---------------------------

Big thanks to Pavel Bogachev for the translation of this guide.
