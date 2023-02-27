---
toc: true
layout: post
description: CPT
categories: [markdown]
title: Create Performence Task
---

# Video:
[](https://youtu.be/XkIJ-Kru4co)

# 3 a.
## 3.a.i
The purpose of this program is to teach about the dangers of gambling by showing a realistic simulation of a blackjack game
## 3.a.ii.
The video shows a game of blackjack being played by pressing different buttons pertaining to different aspects of a game of blackjack. In the first part he wins due to blackjack rules and in the second part he loses.
## 3.a.iii.
The input is pressing two buttons which represent different decisions made during a blackjack game. The output is the display of the cards which represent randomly drawn cards during a blackjack game, along with the display of whether you won or lost.

# 3 b.
## 3.b.i.
![]({{ site.baseurl }}/images/cpt3bi.png "An image")
## 3.b.ii.
![]({{ site.baseurl }}/images/cptbii.png "An image")
## 3.b.iii.
The array I chose was Cards
## 3.b.iv.
The data in this array is all of the possible values of a card. 
## 3.b.v.
When it is called, a random index of the array is called. The value of this is then displayed in a text element. This effectively allows a random card to be shown, just like when drawing a card in a game of blackjack. One way to write this functionality without the use of an array would be to display the number if it is between 2 and 10, and have if/else statements for the numbers that need to be text, like the ace and jack. It would be much longer and much more cluttered than using an array.

# 3 c.
## 3.c.i.
![]({{ site.baseurl }}/images/cptci2.png "An image")
## 3.c.ii.
![]({{ site.baseurl }}/images/cpt3cii.png "An image")
## 3.c.iii.
The program selected calculates the current score of the player based on the cards that they have drawn. The parameter makes it so that a different value is returned based on whether the player or the dealer is being calculated. It allows the program to update the score when the game starts, when the player hits, and when the game ends.
## 3.c.iv.
The program first initializes a variable sum and sets it's value to zero. It then checks if the player is being calculated and loops through each element in the playerCards array adding each element to the sum. If the player went over 21, all of the aces that the player has are converted to 1 instead of 11. If the dealer was selected to calculated, the same process is applied but instead of the playerCards the dealerCards array is iterated upon.

# 3 d.
## 3.d.i
First Call:
The first call will set the dealer's score: 
document.getElementById("DealerScore").innerHTML = "The Dealer's Score is: " + CalculateScore(false);
The second call will set the player's score:
document.getElementById("PlayerScore").innerHTML = "Your Score is: " + CalculateScore(true);
## 3.d.ii.
Condition tested by first call:
(isP == true) is tested.
Condition tested by second call:
(isP == true) is tested.

Results of the first call:
10
Results of the second call:
25