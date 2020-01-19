---
layout: post
title:      "How I Made My Own CLI Gem"
date:       2020-01-19 23:31:30 +0000
permalink:  how_i_made_my_own_cli_gem
---


The process to making a CLI Gem from scratch is both easy and hard. Knowing code and how it functions is great and all but writing code that's legible, clean, and DRY is a bit of a toughie. Its easy to just rush through and code everything at once but once you really try to clean that up after finishing, it's easy to lose track of certain elements. It doesn't take long until you start moving code, shortening and deleting lines, and repeating yourself to try fit multiple processes into the same couple lines and although you understand what your code does it becomes a totally foreign language once you read it back.

The big struggle for me when I was starting this project was really finding an idea and website that made sense to make a CLI gem for. I played with a couple ideas but ended up being stopped by an idea or website being too simple or the scraping was too complex. Ultimately I decided to go along with making TechDeals and although I'm not happy with the idea being so similar to the DailyDeals demo, It also pushed me to try a lot harder to make my gem stand out as more complex.

The coding part, admittedly, was easy. I think that as long as I had the right idea for how a certain block of code or method should work, actually writing code that worked wasn't too hard. However, writing code that made sense in the context of the whole project was a lot harder. To explain, there were instances in the cli.rb code that I would look at and think "oh I could have moved this to another part of the code" or "I could add this kind of functionality to my methods" and it really gunked up my code. I tried pretty hard to make my code DRY and really clean up the mess that altering code had on the readability of my code and although I'm not 100% satisfied, given the time frame that I had to work and edit my code, I think it's acceptable. A big thing I tried to add to improve my code was making my code intuitive for the user and making sure the user couldn't "break" the program by inputting anything that wasn't allowed. To that end, I think I succeeded.

Moving forwards I'd like to be better at commenting code, mostly leaving notes so that if I were to come back and edit them later, I wouldn't have any problems understanding what that code was initially meant to do. If I had more time I would definitely make more changes but I definitely feel the frustration of having to change and break and rewrite code just so it makes more sense. Hopefully I could get over that kind of frustration and really strive to make my code cleaner.
