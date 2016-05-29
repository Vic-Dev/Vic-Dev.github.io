---
layout: page
title: Portfolio
---

# Bet Me

Bet Me is a demo project of a web app where users can post challenges they hope to accomplish.

**[Live on Heroku](https://bet-me.herokuapp.com/)**

![Bet Me login]({{ site.url }}/assets/Bet-Me-login.png)

## Description

This app is intended to allow users to post personal challenges and invite friends to vote on their completion of the challenge. For example, a user may post a bet that they will do spring cleaning by the end of the fall, and place $100 for their bet. The user also adds friends to the challenge, who will later vote on whether they have successfully completed their challenge. Once their deadline has reached completion, they are prompted to add a picture as proof of completing their challenge. The voters are then prompted to vote on whether the user has passed or failed in completing their challenge. The votes are tallied, and if the user is judged as completing their challenge, the retain their $100 wager. However, if the challenge is deemed unsuccessful, the $100 wager is split evenly among the voters.


### Features

- Developed using [ruby](https://www.ruby-lang.org/en/) and [sinatra](http://www.sinatrarb.com/)
- Secure sign up, login, logout using [bcrypt](https://github.com/codahale/bcrypt-ruby)
- Database in [postgres](https://www.postgresql.org/)
- There's a ball involved. And paddles. Feature!

Question? Problems? Email me! <a href="mailto:{{ site.email }}">{{ site.email }}</a>