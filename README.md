# BacklogKeeper #

## What is this? ##
It is a simple spreadsheet to keep track of all your games across different platforms and their status

## Why? ##
Due to the increased affordability of games, today is very common to have tons of games in multiple platforms, and maybe even have some of them duplicated on multiple platforms. With such quantity of games, it often becomes a problem to decide what to play next, or keep track of the games you already finished, those that you dropped, those that you have pending, and those that you have not yet reviewed and assigned to one of those categories

## But, there are already ways to do this! ##
Yes, but I found none that fitted me. I didn't want to use online tools because they can disappear at any given time and so I would lose all my work spent on organizing my collection. Offline tools were often not multiplatform, and on top of all this I wanted an uncomplicated standard way to store my backlog data. Database apps (Like LibreOffice Base) were too complex, so in the end I settled for a spreadsheet. Easy to use, allowed me to filter data the way I wanted, and in sum offered all the features I needed

## How does it work? ##
The spreadsheet is filled with sample data. You can delete all rows except row 1 on the "Backlog" sheet and start from scratch, or you can check which games you own from the list and keep those rows to save some time and use it as a starting point for your own collection

Here is an explanation of the purpose of each column:

* **Game**: Game name
* **Status**: Game status (Explained below)
* **Duration**: Estimated time taken to beat the game (You can get this info on HowLongToBeat.com)
* **Multiplayer**: Used to specify if the game has multiplayer mode or not. Filtering by this column is useful to quickly find a list of games suitable to play when some friends come over
* **PCGamingWiki**: Pressing Ctrl+Click on a cell on this column opens a browser window with the corresponding game's page on PCGamingWiki. This is useful to find fixes for that game and also knowing if the version of the game distributed by the digital store where you acquired it is DRM-Free 
* **Trailer**: Pressing Ctrl+Click on a cell on this column opens YouTube with a search for the corresponding game's trailer
* **Backup**: Used to indicate if you have a physical or digital DRM-Free copy of the game (yes, I like to OWN my games and not depend exclusively on online platforms that may cease to exist, taking my games to the grave with them). It can also be used as a "platform" itself, when you don't own the game in any other online platform
* **Platform columns**: The rest of the columns are for the platforms where you own your games

The first row, the one with the column titles has some buttons with a down arrow that you can use to sort and filter your collection. I find it useful to filter out dropped and played games and sorting the duration column in ascending order to help me decide what to play next (short games are easier to start with and you can strike out items from your pending list faster, so it feels like you are making more progress)

Lastly, there is a "Stats" sheet that gives an overview of your collection's stats

## Game status ##
The possible statuses for the games are the following. I like to color each row for legibility:

* **Played (Green)**: Games that I have finished and I do not plan on playing anymore
* **Replayable (Blue):** Finished games that I plan on playing again
* **Dropped (Black):** Games that I found uninteresting and decided not to play them. Useful for those games that you got on a bundle, but didn't want
* **Pending (Orange):** This one is for games that interest me and I intend to play sometime
* **? (White):** The games that fall in this category are those that I have not yet reviewed, so I don't know yet if they will end up on pending or dropped

## FAQ ##
* Can I delete or add new platform columns?

Yes

* Do rows get auto colored when I change the game's status?

Nope, you have to do it manually

* Why are some of cells colored yellow? 

This marks the platform in which I intend to play the game. Most useful when you have the same game on different platforms, but also I use it with game that I own on a single platform 

* Why does the duration column doesn't get it's data automatically from HowLongToBeat?

Initially I planned on making this column work similarly to the PCGamingWiki or Trailer ones, but HowLongToBeat search doesn't allow for search keywords on the URL. I also looked into making it work via macros, but HowLongToBeat doesn't have a public API. Some unofficial API bindings exist for Python, but I found Python macros on LibreOffice are very cumbersome so in the end I ditched the idea

* What are those BW and BWL values on the Backup column of the sample data?

They specify if the backup copy I have works on Windows only (BW) or on Windows and Linux (BWL)


