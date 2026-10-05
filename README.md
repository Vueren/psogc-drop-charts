# PSO Drop Charts (GC)

Welcome to the Phantasy Star Online drop charts for GameCube!

The data for these drops was put together by the effort of the community. Special thanks go out to PhantasyStarved and all those who helped him put together his spreadsheet, which I uploaded here in the repository. The data on PSO World is *sometimes* inaccurate.

The .js file is basically just a copy and paste of all of that data done in the single most inefficient manner I could do. Because screw pulling the data from the spreadsheet programmatically.

The .html file just displays that data and allows you to filter through it.

Without further ado... Enjoy the website!

[PSOGC Drop Charts](https://vueren.github.io/psogc-drop-charts/)


# Updates as of Oct 5th 2026:

- Feature: **Added a Monster Name filter**
- Data Entry: **Fixed numerous drop rate issues (majority of which were in normal difficulty and majority of which were off-by-one) by using actual game data**
  - *DISCLAIMER: Box rates have not been reviewed just yet!*
- Data Entry: Yellowboze Ult Caves Migium/Hidoom now show the correct rares (they were swapped)
- Data Entry: Typo fix on Greenill and Gillchic(h) (previously only 1 L)
  - *There are still many other typos present, primarily in item names. These typos will be handled in a future update.*
- Style: Re-enabled text selection. Sorry that this was disabled previously. I don't know why I did that.
- Style: Removed the differently sized border separating item name/drop rate/enemy from area/difficulty/section id

Additional Notes:

Previously, this pulled from a version of Phantasy Starved's drop chart spreadsheet that had been "reviewed" by someone. I fixed as many typos as I could find with it, but I could not catch everything. Once I manually copied all of the drop charts into code for use in my Console drop charts application so that I could filter by area/difficulty/section ID while I was playing, I got a Steam Deck and needed to view the drop charts from my phone. Sooooo, I transpiled the data part of that console application codebase over to JavaScript and built this simple website around that data. This was primarily meant to be a personal project for my own use.

I have many regrets in how I handled this process, but at the time, it was the single most accurate spreadsheet circulated around on the web. Just to reiterate: there were NUMEROUS points of manual editing and typing involved in the creation of this website, and only ONE single pair of drops was outright incorrect across all monsters, difficulties, and section IDs.

Many thanks to valued community member AKDylie for handing me the data he pulled programmatically from the raw game files. I have reviewed every single monster drop and updated all of the rates manually (for now). My schedule is quite busy so EVENTUALLY I will be rebuilding this website's backend to pull directly from files that AKDylie provided, but for now, the least I could do was fix all of the data entry errors that this site originally had in it for the last few years now. AKDylie's work will enable me to develop several newer features such as drop rate breakdowns with details such as the drop anything rate and the rare drop rate, pulling the actual item names as they are in-game which should also allow translations to other languages, and more. Stay tuned and look forward to it!

I am also available in the Hunter's Guild Discord by the same name as here on GitHub if you would like a breakdown on the EXACT changes that I entered in today, e.g. if you are doing a rare drop completionist challenge and need to update your own sources for a specific Section ID. 
