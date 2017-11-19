---
title: About Pantheon
date: 2017-04-08 22:04:38
---

Mahjong Pantheon is a bunch of web-based software tools to bring some automation to regular riichi mahjong tournaments & local games.

### Subsystems

- **Mimir** is a specialized backend database which supports JSON-RPC calls for data operations.
- **Tyr** is mobile web application, which uses Mimir as its backend to provide online game overview and automated scoring abilities for every player with handheld device.
- **Rheda** is simple dynamic web frontend to show Mimir's data pretty and conveniently. It includes rating tables, statistics, graphs, last games and also some tournament administration tools (this will change, though).

### Software stack

All Pantheon tools are supposed to be web-based applications, which run either in browser or on a server. Tyr is written almost entirely in Typescript, Mimir and Rheda are written in PHP (5.5+). Mimir supports MySQL, PostgreSQL and SQLite databases as its backend.

Installation instructions are still WIP (and so are Docker files for simpler development setup), but it should be pretty easy to install all three subsystems for anyone who is familiar with web development.

### People

Pantheon dream team and collaborators:

- [Oleg Klimenko](https://github.com/ctizen), Novosibirsk, Russia - **project lead**
- [Alexey Lisikhin](https://github.com/Nihisil), Irkutsk, Russia - **brave volunteer web developer**
- Darya Ilyina, Moscow, Russia - **QA assistant & Moscow club leader**
- Vitaly Borzonogov, Arkhangelsk, Russia - **QA assistant, Arkhangelsk club leader** (and also honorable first project donator ever :) )
- Maksim Veselov and all **Ivanovo** riichi club fellows, Russia - honorable donators to the project.
- Want your name to be listed here? **Join now**! :) We need volunteer web developers, QA engineers, tech writers and translators!
