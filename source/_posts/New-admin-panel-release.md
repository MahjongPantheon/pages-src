---
title: New admin panel release
date: 2023-04-20 13:32:47
tags:
---
New administration panel and private area (codename "Forseti") has been released. Let's see what's new.

### Login/signup functionality moved to new service

You can no longer login or signup with Rheda. But there will be a link to "Personal area" instead:

![](/images/forseti/rheda-login.png)

Following that link when not logged in will open login form. Also there is a password recovery link under the login form.

![](/images/forseti/forseti-login.png)

If you're not registered, you may follow the "Sign up" link in left column to create your account. 

![](/images/forseti/forseti-signup.png)

After you fill the form and submit it, the confirmation email will be sent to your address. Follow the link in the email to get to confirmation page.

![](/images/forseti/forseti-confirm-email.png)

When logged in, you can edit your profile details after following the "My profile" link in left menu.

![](/images/forseti/forseti-profile-edit.png)

You can create events in "Manage events" page. Click "Create new event" button in the top of the page and fill the form. You need to enter basic information on the first table. First, select type of new event, depending on which second configuration tab will vary. Second, choose ruleset template. The rules checkboxes and values on third and fourth tabs will be set according to selected ruleset. Please note that ruleset template selection resets all you fine tuning you made before. Third, fill timezone and event description - markdown syntax is supported for the description.

![](/images/forseti/new-event-local.png)

On local event settings tab you may select series length and minimal games count

![](/images/forseti/local-event-tab.png)

On online event settings tab you should fill the tenhou.net lobby number, other fields are optional

![](/images/forseti/online-event-tab.png)

Tournament settings tab allows to set session duration and ending policy. Also there are two checkboxes which change tournament logic: "Team tournament" checkbox enables team rating table and additional tab in "Manage players" page where you can set team names for each player; "Seating is defined in advance" checkbox enables predefined seating mode, which enables additional tab in players management (to set player local IDs) and an additional page in event settings called "Predefined seating" where event seating script is defined. Also all automated seatings are disabled in this mode.   

![](/images/forseti/tournament-event-tab.png)

You can fine-tune the ruleset on third tab of event settings - there's quite much settings.

![](/images/forseti/ruleset-tuning.png)

You can enable or disable some yaku on the last tab, also some yaku-related rules are defined there.

![](/images/forseti/yaku-tuning.png)

After clicking on "Save changes" button, you will be redirected to own event list. A menu under "Actions" button allows event management actions. Also there is a button allowing to hide or show the event on ratings service main page.

![](/images/forseti/event-menu.png)

Clicking "Manage games" in the menu will bring you to the games control page. If it's a tournament, there will also be tournament controls in the top of page.

![](/images/forseti/tourn-control.png)

The "Manage players" page allows excluding players from next game and promoting them to administrators. Also there is a "Replace player" button next to player title.

![](/images/forseti/manage-players.png)

Clicking the replace button will show the replacement dialog, where you should choose the replacement player.

![](/images/forseti/replacements.png)

After the replacement is selected, the dialog is closed and replacement player is shown next to player title. Remove the replacement by clicking the cross link.

![](/images/forseti/replacement-remove.png)

Clicking the "Penalties" button in left menu will bring you to the page where arbitrary penalty can be applied. Note that reason is mandatory.

![](/images/forseti/penalties.png)

Note two buttons in left lower corner. One is there to change language (btw, we're looking for translators!), and the another one enables the dark mode.

![](/images/forseti/langs.png)
![](/images/forseti/dark-mode.png)

We hope new personal area and administration panel will be much more convenient for players and event administrators. Please let us know about any found bugs or inconsistencies in our support channels in [Discord (EN)](https://discord.gg/U5qBkexfEQ) or in [Telegram (RU)](https://t.me/pantheon_support). Good luck!
