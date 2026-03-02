# Three-Card-Poker
Browser-based Three Card Pokwer game. HTML/CSS/JS.

Download the HTML and play locally or just go to https://saturnitygl.github.io/Three-Card-Poker

## How to play
-Place your ante bet using chips
-You and the dealer are dealt 3 cards
-Choose to play (match your ante) or fold
-Dealer needs queen-high or better to qualify.
-Win both bets if your hand beats the dealer

## Built primarily for HF

## Currently set to allow you to just simply go to zero and tell you that you have no more, reset. 

## To change starting balance

const CONFIG = {
  startingBalance: 1,000, // Change this, of course. 

## To change starting balance and link to an API (Maybe, grain of salt) Replace the whole line with

startingBalance: await fetch ('/api/yourcurrency/balance').then(r => r.json()),

## To change min and max

const CONFIG = {
  startingBalance: 1,000,
    minBet: 2,  // change this
    maxBet: 500,  // change this
