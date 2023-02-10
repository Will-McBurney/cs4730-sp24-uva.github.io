---
layout: default
title: Quests
nav_order: 4
---

# Game Design Quests and Assessments
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

# Required Games

## Quest Information
{: .no_toc }
<img style="float: left; padding: 10px" src="/assets/images/quest.png"> For this class, you are required to play two different games that we will analyze throughout the semester.

| __A Short Hike__ by adamgryu | __Celeste__ by Maddy Makes Games |
| :----------------------------: | :--------------------------------------: |
| ![A Short Hike Title Card](/assets/images/ashorthike.png) | ![Celeste Title Card](/assets/images/celeste.png)
| Available at: [itch.io](https://adamgryu.itch.io/a-short-hike), [Steam](https://store.steampowered.com/app/1055540/A_Short_Hike/), Nintendo eShop, and other platforms | Available at: [itch.io](https://mattmakesgames.itch.io/celeste), [Steam](https://store.steampowered.com/app/504230/Celeste/), Nintendo eShop, and other platforms
| _Objective:_ Complete the main story of the game | _Objective:_ Complete through the beginning of Chapter 4 with and/or without assists turned on | 
| _Estimated time to complete:_ 2 hours | _Estimated time to complete:_ 3 hours |

_Note:_ We are going to be talking specifically about the assist options in _Celeste_.  Even if you can get to Chapter 4 without the assists, make sure to play the game with them at some point to see how they work.  Also, if you need to use the assists to make it to Chapter 4, that's fine.  Try to at least get through Chapter 1 without them, however.

## Quest Submission
{: .no_toc }
<img style="float: left; padding: 10px" src="/assets/images/turnin.png">  No submission required specifically for playing the games.

# Critical Analysis Quest

First, watch this:

<iframe width="800" height="450" src="https://www.youtube.com/embed/bb3HQlFmfds" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Quest Information
{: .no_toc }
<img style="float: left; padding: 10px" src="/assets/images/quest.png"> What is a critical analysis, and why do we care?

Critical analysis is not just a game review. We are not concerned with how many out of five stars, or any numbers from 0 to 10, or whether or not a game is “fun” (whatever that means to you).

Critical analysis does not just mean a list of things that are wrong with the game. The word “critical” in this context does not mean “fault-finding” but rather a thorough and unbiased look at the game.

Critical analysis is useful when discussing or comparing games. You can say “I like the card game Bang! because it’s fun” but that does not help us as designers to learn why it is fun. We must look at the parts of games and how they interact in order to understand how each part relates to the play experience.

Critical analysis is also useful when examining our own works in progress. For a game that you’re working on, how do you know what to add or remove to make it better?

To complete a Critical Analysis assignment, write a paper (probably at least 2-3 pages) that does the following (and most likely somewhat in this order):

* Give a high-level description of the game, game’s history, or other introductory information you think is appropriate. I would expect also to see what you believe the games main aesthetics are here (as defined by the MDA paper).
* Describe the game’s formal elements. Do not interpret at this point, simply state what is there.
* Describe the results of the formal elements when put in motion. How do the different elements interact? What is the play of the game like? Is it effective?
* Specifically discuss the mechanics, dynamics, and aesthetics of the game.
* Try to understand why the designer chose those elements and not others. Why this particular player structure, and why that set of resources? What would have happened if the designer had chosen differently?

Some questions to ask yourself during a critical analysis at various stages:

* What challenges do the players face? What actions can players take to overcome those challenges?
* How do players affect each other?
* Is the game perceived by the players as fair? (Note that it may or may not actually be fair. Perception and reality often differ.)
* Is the game replayable? Are there multiple paths to victory, varied start positions, or optional rules that cause the experience to be different each time?
* What is the game’s intended audience? Is the game appropriate for that audience?
* What is the “core” of the game - the one thing you do over and over that represents the main “fun” part?

NOTE: Literally just answering the above questions WILL NOT result in a good score.  I expect you to put some thought into how best analyze the game you are looking at.  Some of these questions make no sense for certain games and tossing "an answer" to them in your paper would be frowned upon.

## Quest Submission
{: .no_toc }
<img style="float: left; padding: 10px" src="/assets/images/turnin.png"> 

Submit a PDF of your paper to the appropriate assignment in [Gradescope]({{ site.data.externallinks.gradescope }}).

[An example Critical Eye on Hearthstone from Spring 2014](/assets/materials/HearthstoneCriticalEye.pdf)

You will complete this assessment at least twice: 

* once for either _A Short Hike_ or _Celeste_
* once for a game of your choosing (including the other option of _A Short Hike_ or _Celeste_) 
* optionally one more time as your Player's Choice Quest

If you choose your own game, it can be a game you have already played, although you may need to refresh your memory.  If you need some thoughts on what games to play, I'm happy to offer suggestions.  

Some content here used with permission from [Game Design Concepts by Ian Schreiber](http://gamedesignconcepts.wordpress.com/2009/07/06/level-3-formal-elements-of-games/).


# MonoGame: Level 1 - Animation and Control

## Quest Information
{: .no_toc }
<img style="float: left; padding: 10px" src="/assets/images/quest.png"> Over the course of three levels, you will be building out some basic functionality for a game built on MonoGame.  Level 1 will focus on animation and control.  You are welcome to use any tutorials or example code you find, but make sure to cite any sources used in your code and in the submission to Gradescope.

1. Accept the assignment from GitHub Classroom: [https://classroom.github.com/a/qa9BdJCd](https://classroom.github.com/a/qa9BdJCd)
2. Clone the repo locally and create a new project inside this folder named "Level 1".
3. Import a sprite sheet of your choosing, but it needs to be loosly a character with the following animation states for the noted XP:
   * When standing still (either at the bottom of the Cornflower Blue window or a platform (invidible or not)), there should be a minimum 3 frame idle animation [5 XP]
   * The idle animation should be mirrored when the character is turned left or right [5 XP]
   * The character should be able to be controlled in the following way: A moves left, D moves right, W jumps [5 XP]
   * Gravity should affect the character and bring it back down to a resting state in a "reasonable" way after they jump [10 XP]
   * When the character jumps, there should be a switch to an appropriate jumping animation set [10 XP]
   * Implement one other "action" of some kind with another animation set and map it to the space bar [10 XP] (Examples could include an attack animation, a slide animation, casting a spell, etc.)

If you are looking for spritesheets and assets there are MANY available at [https://itch.io/game-assets](https://itch.io/game-assets) for free or for a small price/donation.

## Quest Submission
{: .no_toc }
<img style="float: left; padding: 10px" src="/assets/images/turnin.png"> 

Make sure to push the final version of your code to GitHub before the deadline.

Answer the questions in [Gradescope]({{ site.data.externallinks.gradescope }}) under "MonoGame: Level 1" regarding your project [5 XP].