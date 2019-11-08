# BacklogKeeper #

## What is this? ##
It is a simple spreadsheet to keep track of all your games across different platforms and their status

## Why? ##
Due to the increased affordability of games, today is very common to have tons of games in multiple platforms, and maybe even have some of them duplicated on multiple platforms. With such quantity of games, it often becomes a problem to decide what to play next, or keep track of the games you already finished, those that you dropped, those that you have pending, and those that you have not yet reviewed and assigned to one of those categories

## But, there are already ways to do this! ##
Yes, but I found none that fitted me. I didn't want to use online tools because they can disappear at any given time and so I would lose all my work spent on organizing my collection. Offline tools were often not multiplatform, and on top of all this I wanted an uncomplicated atandard way to store my backlog data. Database apps (Like LibreOffice Base) were too complex, so in the end I settled for a spreadsheet. Easy to use, allowed me to filter data the way I wanted, and in sum offered all the features I needed

## Hey, this is not translated to english! ##
No, it's not, I didn't feel like translating it because I'm lazy. And because I didn't want to mantain two branches of the project in case I add more features to it later. However, there is very little text to translate, so it shouldn't be a problem. Here is a quick translation table:

* Jugado = Played
* Dropeado = Dropped
* Rejugable = Replayable
* Pendiente = Pending
* Estado = Status
* Juego = Game
* Duracion = Duration
* Estaditicas = Statistics
* Numero = Number
* Porcentaje = Percentage
* Dias = Days

## How does it work? ##
The spreadsheet is filled with sample data. You can delete all rows except row 1 on the "Backlog" sheet and start from scratch, or you can check which games you own from the list and keep those rows to save some time and use it as a starting point for your own collection

The sheet has a column for each platform, another one for the game status (more on this later), another one for the game name, and a last one for the estimated time taken to beat the game (You can get this info on HowLongToBeat.com). The first row, the one with the column titles has some buttons with a down arrow that you can use to sort and filter your collection. I find it useful to filter out dropped and played games and sorting the duration column in ascending order to help me decide what to play next (short games are easier to start with and you can strike out items from your pending list faster, so it feels like you are making more progress)

The possible statuses for the games are the following. I like to color each row for legibility:
* **Played (Green)**: Games that I have finished and I do not plan on playing anymore
* **Replayable (Blue):** Finished games that I plan on playing again
* **Dropped (Black):** Games that I found uninteresting and decided not to play them. Useful for those games that you got on a bundle, but didn't want
* **Pending (Orange):** This one is for games that interest me and I intend to play sometime
* **? (White):** The games that fall in this category are those that I have not yet reviewed, so I don't know yet if they will end up on pending or dropped

Some of the cells are colored yellow. This marks the platform in which I intend to play the game. Most useful when you have the same game on different platforms, but also I use it with game that I own on a single platform 

The first column (labeled "Backup") is used to indicate if you have a physical or digital DRM-Free copy of the game (yes, I like to OWN my games and not depend exclusively on online platforms that may cease to exist, taking my games to the grave with them). It can also be used as a "platform" itself, when you don't own the game in any other online platform

Lastly, there is a "Stats" sheet that gives an overview of your collection's stats

## FAQ ##
* Can I delete or add new platform columns?
Yes
* Do rows get auto colored when I change the game's status?
Nope, you have to do it manually
