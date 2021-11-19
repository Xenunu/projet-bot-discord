# projet-bot-discord

﻿# projet-bot-discord


## Table of Contents
1. [General Info](#general-info)
2. [Foundation](#Foundation)
3. [Installation](#installation)
4. [lancer le BOT](#lancer-le-BOT)
5. [Collaboration](#collaboration)
6. [FAQs](#faqs)

# 1) General Info
The bot disk allows to execute a number of tasks, it suffices to keep the main structure then you can add the lines of codes corresponding to the functionality you want to add.
the bot is available in every server you want to create


### prerequisites:
you need the following module: 
- node.js (npm i node)
- fs (npm i fs)
- mysql (npm i mysql)

 - create the bot with the discord API and configure it according to the expectations (see tuto)

# 2) Foundation
this is the main structure
![This is an image](https://media.discordapp.net/attachments/892670018960117790/911340191246065724/unknown.png)
![This is an image](https://media.discordapp.net/attachments/892670018960117790/911340259348971560/unknown.png)

# 3) Installation
The languages ​​used for bot programming are JS and Json. 

ben explique comment le rendre fonctionnel sur le discord
mettre des screens potentiellemen


### Create new commands:

to create a new command you just have to create a new file in the commands folder 
it is imperative that ends with .js
then it is enough to note that in it

![This is an image](https://media.discordapp.net/attachments/892670018960117790/910557269001928754/unknown.png)

 
### Create a new event:

to create a new event you just have to create a new file in the events folder
it must end with .js
then you just have to write that in 

![This is an image](https://media.discordapp.net/attachments/892670018960117790/911208042689863700/unknown.png)

### Connect to a database: 
to connect to a database you just have to fill in the information with your own db code in the index file : line 10 to 13

![This is an image](https://cdn.discordapp.com/attachments/892670018960117790/910486786692771840/unknown.png)

when you want to use the db in a command or an event you have to add this :

![This is an image](https://cdn.discordapp.com/attachments/892670018960117790/910556192818987008/unknown.png)

### Example:

![This is an image](https://media.discordapp.net/attachments/892670018960117790/910556879137169478/unknown.png)

# 4) launch the BOT :
  to launch the bot locally you have to launch the index file with node
  (for the code editor vs code you just have to position yourself in the index file then press f5, select node and enter)


# 5) Collaboration
Our project was created by 3 people, Gabriel Changrenier, Benjamin Dupain and Romain Bonmarché. 
The goal of this project was to create a totally autonomous intelligence, which executes the list of 
programs that you have previously given it.
It is customizable and easy to use.
We are proud to present you our project.

# 6) FAQs
-> how to add a new command?

-> how to know if the program is running/parked?

-> how to modify a command?

-> Is it 100% autonomous?

-> Can we customize it as we wish?
