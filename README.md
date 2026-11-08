# RockPaperSnap

RockPaperSnap is a Rock Paper Scissors mobile game built with React Native and Expo Router for the Mobile Application Development practical.


## What Was Built

The app has two tabs. The Play Game tab contains the main game engine, in which the player chooses Rock, Paper, or Scissors and the computer's weapon is selected at random using `Math.random()`. 

The outcome is determined by the classic rules, and the result message, its colour, and a running scoreboard of wins, draws, and losses are updated through `useState`.

A reset function is also included to clear the game state. The Rules tab is a scrollable screen that explains how each weapon beats another and how a round is decided.

Navigation was set up with Expo Router. A root `_layout.tsx` was created with a Stack navigator that hides its own header, and a second `_layout.tsx` inside `app/(tabs)` was created to define the Play Game and Rules tabs, with Ionicons used for the tab bar icons. 

A custom splash screen was configured in `app.json` using `assets/images/appIcon.png`.

