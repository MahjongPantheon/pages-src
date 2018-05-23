---
title: About Pantheon
date: 2018-05-23 22:04:38
---

Mahjong Pantheon is a set of web-based software tools to automate regular riichi mahjong tournaments & local games.

### Subsystems

- **Mimir** is a specialized backend database which supports JSON-RPC calls for data operations.
- **Tyr** is mobile web application, which uses Mimir as its backend to provide online game overview and automated scoring abilities for every player with handheld device. See [screenshots](#Tyr-screenshots).
- **Rheda** is simple dynamic web frontend to show Mimir's data pretty and conveniently. It includes rating tables, statistics, graphs, last games and also some tournament administration tools (this will change, though). See [screenshots](#Rheda-screenshots).

### Software stack

All Pantheon tools are supposed to be web-based applications, which run either in browser or on a server. Tyr is written almost entirely in Typescript, Mimir and Rheda are written in PHP (5.5+). Mimir supports MySQL, PostgreSQL and SQLite databases as its backend.

 Production installation instructions are still WIP, but it should be pretty easy to install all three subsystems for anyone who is familiar with web development. Source code and development environment setup instructions are available on [github](https://github.com/MahjongPantheon/pantheon).

### People

Pantheon dream team and collaborators:

- [Oleg Klimenko](https://github.com/ctizen), Novosibirsk, Russia - **project lead**
- [Alexey Lisikhin](https://github.com/Nihisil), Irkutsk, Russia - **brave volunteer web developer**
- [Pavel Bogachev](https://github.com/bogachev-pa), Moscow, Russia - **volunteer developer**
- Daria Ilina, Moscow, Russia - **QA assistant & Moscow club leader**
- Vitaly Borzonogov, Arkhangelsk, Russia - **QA assistant, Arkhangelsk club leader** (and also honorable first project donator ever :) )
- Maksim Veselov and all **Ivanovo** riichi club fellows, Russia - honorable donators to the project.
- Want your name to be listed here? **Join now**! :) We need volunteer web developers, QA engineers, tech writers and translators!

### Tyr screenshots

 ![](/images/Tyr1.jpg) 
 ![](/images/Tyr2.jpg) 
 ![](/images/Tyr3.jpg) 
 ![](/images/Tyr4.jpg) 
 ![](/images/Tyr5.jpg) 
 ![](/images/Tyr6.jpg) 
 ![](/images/Tyr7.jpg) 
 ![](/images/Tyr8.jpg) 

<a href="#top">Back to description</a>.

### Rheda screenshots

![](/images/Rheda1.png "Personal stats")

![](/images/Rheda2.png "Recent games")

![](/images/Rheda3.png "Rating table")

<a href="#top">Back to description</a>.

