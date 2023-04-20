---
title: Hosting a tournament
date: 2019-10-09 23:08:30
---

### Hosting a tournament with Pantheon

#### 1. Basics
- The system may work both in tournament mode and club rating mode. In tournament mode, there is timer, automatic seating generator, but players can't be added or removed any time.
- The game session lasts for 75 minutes (you can change this value if you want).
- There is automatic seating generation and also a predefined seating mode.
- The winner is defined by summary score of all games played.
- Uma is 15000/5000 (you can change it value if you want).
- Main address of admin panel - https://manage.riichimahjong.org . The list of events you are an administrator at will be there. Use "Actions" menu to get to the management page you need. When in particular event management mode, you can navigate between event management pages using menu in left column.

#### 2. Players management
- The tournament administrator should add to the event all tournament players in advance on "Manage players" page.
- To find a particular player, start typing his name/surname in the input field. You will see found players in dropdown menu. Selecting a player in the menu will add them to the event. Note that you will not see all added players immediately - you will need to refresh the page first.
- If a player can't be found, notify them about it - probably, they forgot to fill in theis name and surname in their profile.
- For each player there are several buttons in the list:
  - "Exclude from seating" - this button is useful if some of the players are not able to continue to participate and count of such players exceeds cound of available replacement players. You can exclude four or more players (e.g. whole table or several tables) from the tournament using this button. Also you can exclude from the tournament seating all the non-playing referees, who are still required to be in the list.
  - "Remove player" - this button is available when no games are played yet. You can remove from the list a player added by accident.
  - "Make an administrator" - this button gives a player access to the admin panel. Such player can cancel hands, start the timer, generate seatings and other. Non-playing referees are required to be given admin privileges, but they should be excluded from the seating.
- There is also a "Replace player" button to the right of player title, a dialog will pop up when it's pressed. You can select a replacement player (found by name/surname) for the player who can't participate in current session here. The player who has a replacement selected will achieve -30000 points in the end of game session no matter what score they gained during the game. If a player gets back to the tournament, the replacement should be nullified - please do it before "Confirm results" button is pressed, otherwise the player will still gain -30000 points for current game. Please don't set anyone who was already added to the rating as a replacement player - it may lead to unforeseen consequences.
- The system will not allow you to start the game session if the count of active players is not divisible by 4. If required, the administrator may remove someone from the tournament or add some additional players (there are "Replacement player 1-4" accounts for that).

#### 3. Running the tournament
- The tournament session may have following statuses:
  - "Not ready": players count is not divisible by 4, can't continue
  - "Not started": on this stage, you can generate a seating.
  - "Seating...": seating is in progress, please wait
  - "Seating ready": seating is generated, but timer was not started yet. You'll have a "Start timer" button, which you should press when all players have taken their seats. In case of some mistake during seating generation, there is a "Reset seating" button.
  - "Session started": games are started. There is a "Reset timer" button for some emergency situations.
  - "Ready to approve": all games are finished, but results are not confirmed. You still can cancel the last hand of any game. There is a "Confirm results" button to get to the next stage. After confirmation, new session begins with "Not started" status.
- When seating is ready, each player will see the table number in their mobile assistant (in the central part of the page).
- Timer and seating table are also can be found on "Timer and seating" page in the ratings service. Tournament administrators may show this page on some projector or big screen in the tournament hall, if there are any.
- Games are started by pressing the "Start timer" button. The tournament administrator should also give a clear signal for players to start the game.
- You can add some arbitrary penalties (e.g. for behavior or being late) in amount of 100 to 20000 game points. You can use the "Penalties" page for that.
  - Penalty reasons will be visible in player stats, it's a public information.
  - You can add a penalty only during the game. If a penalty occurs in spare time, you need to wait until next game session is started.
- The administrator can watch the tables state on "Manage games" page. You can't confirm the results until all tables are finished with their game sessions.
- If players have mistaken during logging the game, the administrator may cancel the last logged hand with a "Cancel hand" button on "Manage games" page.
  - Please notify the players clearly that they need to call the referee to cancel the hand, because only referee can make such decision.
