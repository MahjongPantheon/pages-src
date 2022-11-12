---
title: About Pantheon
date: 2022-11-12 16:04:38
---

Mahjong Pantheon is a set of web-based software tools to automate regular riichi mahjong tournaments & local games.

### Subsystems

- **Mimir** is a specialized backend database which supports JSON-RPC calls for data operations.
- **Frey** is a backend for authorization and personal data management.
- **Tyr** is mobile web application, which uses Mimir as its backend to provide online game overview and 
automated scoring abilities for every player with handheld device. See [screenshots](#Tyr-screenshots).
- **Rheda** is simple dynamic web frontend to show Mimir's data pretty and conveniently. It includes rating
tables, statistics, graphs, last games and also some tournament administration tools.
See [screenshots](#Rheda-screenshots).

### Software stack

All Pantheon tools are supposed to be web-based applications, which run either in browser or on a server. 
Tyr is written almost entirely in Typescript, Mimir, Frey and Rheda are written in PHP (7.0+). Mimir and 
Frey use PostgreSQL database as its backend.

Production installation instructions are still WIP, but it should be pretty easy to install all four
subsystems for anyone who is familiar with php-related web development. Source code and development
environment setup instructions are available on [github](https://github.com/MahjongPantheon/pantheon).

### People

Pantheon dream team and collaborators:

- [Oleg Klimenko](https://github.com/ctizen) - **project lead**
- [Alexey Lisikhin](https://github.com/Nihisil) - **brave volunteer developer**
- [Pavel Bogachev](https://github.com/bogachev-pa) - **brave volunteer developer**
- [Galina Kapger](https://github.com/kovavka) - **brave volunteer developer**
- [Alexey Dergunov](https://github.com/alexeydergunov) - **brave volunteer developer**
- Daria Ilina, Moscow, Russia - **QA assistant & Moscow club leader**
- Vitaly Borzonogov, Arkhangelsk, Russia - **QA assistant, Arkhangelsk club leader** (and also honorable
first project donator ever :) )
- Maksim Veselov and all **Ivanovo** riichi club fellows, Russia - honorable donators to the project.
- Nina Bychkova and all **Novosibirsk** riichi club fellows, Russia - honorable donators to the project.
- All **Agari** Moscow riichi club fellows, Russia - honorable donators to the project.
- Ivan Tkachenko and all **Sarov** riichi club fellows, Russia - honorable donators to the project.
- Want your name to be listed here? [**Join now**](mailto:me@ctizen.dev)! :) We need volunteer web
developers, QA engineers, tech writers and translators! _Make sure to mention Pantheon in email subject
line - this will drastically reduce probability of occasionally moving your email into spam folder :)_

### Tyr screenshots

 ![](/images/Tyr1.png) 
 ![](/images/Tyr2.png) 
 ![](/images/Tyr3.png) 
 ![](/images/Tyr4.png) 
 ![](/images/Tyr5.png) 
 ![](/images/Tyr6.png) 
 ![](/images/Tyr7.png) 
 ![](/images/Tyr8.png) 

<a href="#top">Back to description</a>.

### Rheda screenshots

![](/images/Rheda1.png "Personal stats")

![](/images/Rheda2.png "Recent games")

![](/images/Rheda3.png "Rating table")

<a href="#top">Back to description</a>.

