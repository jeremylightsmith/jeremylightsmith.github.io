---
layout: post
title:  "How do you start a Startup Weekend company?"
date:   2011-05-04 12:00:00 -0700
categories: leanstartup
---
My friend, [Jennifer Cabala](http://www.jennifercabala.com/), asked me a while ago what tools a fledgling startup could use that [Startup Weekend](http://startupweekend.org/) could help provide. I was at a loss, because most of my toolset is free / opensource.

But it turns out that there are a LOT of things that I do when I start a Startup Weekend company. I watched myself do them over [Madrona Startup Weekend](http://madrona.startupweekend.org/) and now in the days afterward. Seems like maybe that is a list worth sharing.

So, in roughly chronological order :

### During the weekend:

It's a lot of steps but shouldn't take you too long once you've done it a couple times. This whole list took me 1 1/2 hours on Saturday morning before I came in.

* Get a list of everyone's email
* Decide on a name (it _really_ doesn't matter so much, just pick something that has a .com available)
* Get a dropbox folder and share it
* Buy the .com
* Sign up for twitter
  * put twitter user/pass in [dropbox folder]/accounts/twitter.txt


(we had a rails project)
* create a heroku project
  * add custom domain plugin
  * add zerigo addin (dns config)
* move nameservers to heroku
* create a google apps account for the domain name
  * create team@mydomain.com for sending emails from in the app
* get a google analytics account, add it to the layout of your rails app

### After the Weekend

Have the "morning after" conversation

* who has interest in going on?
* what availability do people have?
* what's the goal? exit? become funded? bootstrap?
* how do people get compensated for their time?
* ...

Assuming people want to continue, there's more stuff to do :

* Create a google group [mydomain]@googlegroups.com
* Create a google docs folder that's shared with the google group
* Give everyone on the team an e-mail on google apps
  * I set it up to forward to my main e-mail, and my main email to be able to send as jeremy@mydomain.com, I give it a custom sig too
* Create a [Tracker](http://pivotaltracker.com) project for tactical stuff
* Create a [Maptini](http://maptini.com) or [CardMapping](http://cardmapping.com) site for more long range planning (these are both my startups, so I'm biased, but please use something that let's you see the big picture)

Your mileage may vary. And while these are all great tools, they're just tools. They support your people - it's the people that are important.
