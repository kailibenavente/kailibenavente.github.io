---
layout: project
type: project
image: img/love-match-2.jpg
title: "Love Match"
date: 2024
published: true
labels:
  - User Interaction
  - Data Structure
  - Java
summary: "I developed a mini name-compatibility game after taking ICS 211."
---

Love Match is a mini, terminal-based game I created after taking ICS 211 where we learned a lot about user interaction from the terminal. This program was written in Java and uses unique elements of the language to form the simple algorithm this game is based off of, such as Hash Maps to track certain qualities in a parameter passed through by the user in the terminal. 

Compatibility is tested by counthing the amount of common characters there are in the names given by the user. That amount is then used as a numerator. The denominator is the total amount of all characters in both names added together. This gives us a fraction of commonality, but I chose to make the uncommon characters determine compatibility. To calculate the percentage of compatibility, we take the fraction of commonality and subtract it from one, giving us a value to convert into decimal form to deliver as a percentage. 

I coded this program on my own during the earlier weeks of ICS 211, having been inspired by the material we were covering at the time and I enjoy how amusing and quaint it is for a smaller first project. Though repetitive and limited, it demonstrates clearly what I took away from an introduction to Java and user interaction.

Here is one example run from the program:

<hr>

<pre>

Welcome to the LOVE MATCH game where we test the compatibility of two given names!
When you are finished typing a name, hit the ENTER key.

Enter the first name: 
Johnny Appleseed

Enter the second name: 
Cat in the Hat

You are 86.67% compatible!
Wow! You two should REALLY get together! <3

</pre>

<hr>

See more here: [github.com/kailibenavente/love-match-game](https://github.com/kailibenavente/love-match-game).
