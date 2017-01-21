# 100 Days Of Code - Log

<!-- ### Day 0: February 30, 2016 (Example 1)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link to work:** [Calculator App](http://www.example.com) -->

### Day 1: Thursday, January 12th, 2017

**Today's Progress**: Began working on a Rails Online Shop.  Did schema, wrote user stories, and achieved MVP (basic CRUD functions for items).

**Thoughts**: I had a great day today!  This challenge is actually a group challenge that I was assigned when I did my coding bootcamp, and at the time I felt like I was really struggling.  I'm re doing the challenge solo this time because I think it's a great challenge to get back into the game.  Felt comfortable with everything I did today, which I'm sure will change soon enough once I try and implement more features.  Didn't time myself, but definitely put in at least 5+ hours today!  Day 1 rocked.

**Link(s) to work**: [Rails Online Shop Items](https://github.com/benjaminhyw/rails-online-shop/commit/ad39723145a645f0be47be9d2ecf5b3700170cab)

### Day 2: Friday, January 13th, 2017

**Today's Progress**: Began writing tests for my application.

**Thoughts**: I tried implementing tests today and that did not go as well as I thought it would go.  As a result, a lot of my time today was research and looking for good examples and guides online.  I was only able to write one passing test.. BUT I did learn a few things!  Had to update one of my fixtures because I made a minor mistake yesterday, and my test initially wouldn't run because of that.  Also learned about where certain tests should go.  I feel pretty meh about today because there wasn't a whole lot of new code added to my project, but I feel like I just chipped a little at something big so I'm still feeling positive!


**Link(s) to work**: [Rails Online Shop Tests PR #9](https://github.com/benjaminhyw/rails-online-shop/pull/9)

### Day 3: Saturday, January 14th, 2017

**Today's Progress**: Cleaned up items a little but, got started on fleshing out my code for user profiles!

**Thoughts**: Today was a productive Saturday!  It being the weekend I thought it would be hard to stay on track, but that wasn't the case.  I did feel like I was having a hard time getting approaching code work today, but that didn't last long.  I mostly worked on user profiles, which meant creating new routes, generating a controller and generating a model.  I reached out to the Rails Slack Channel when I had questions (I was wondering if I even needed to create a route for /users if I didn't plan on ever letting my users see a list of other users, was given good info and linked to the [docs](http://guides.rubyonrails.org/routing.html)).  Overall great productive day.


**Link(s) to work**: [Rails Online Shop Users](https://github.com/benjaminhyw/rails-online-shop/commit/2685840076763c2f2c19b844e5fc11a7dc81169d)

### Day 4: Sunday, January 15th, 2017

**Today's Progress**: Kept working on my User model/controller from yesterday.  Chipped away, not done.

**Thoughts**: Today was a kind of whatever productive day.  The past few days I spent more than an hour, spent a good chunk of time.. from start point until I just wanted to end for the day.  Have plans today though so couldn't dedicate as much time.  Didn't learn anything new, just coded a lot of stuff I know but necessary for the functionality of my app.  Everything's good!  And it's a sunny day in San Francisco so off to Dolores I go.


**Link(s) to work**: [Rails Online Shop Users](https://github.com/benjaminhyw/rails-online-shop/pull/13)

### Day 5: Monday, January 16th, 2017

**Today's Progress**: More work on my users controller/model, and got started on sessions!

**Thoughts**:  I didn't get a chance to work on this today until early in the evening, had a bit of a long day so my motivation was a bit chopped.  Still, I got an okay amount of work done and got started on creating user sessions!  I didn't complete sessions, just barely started getting things going.  I'm glad though, because I have a lot more time to spend on the project tomorrow.  When I first worked with sessions at my bootcamp the information kinda flew past me.. grasped some concepts that didn't really solidify, so I'm excited to make sense out of it tomorrow!


**Link(s) to work**: [Rails Online Shop Sessions](https://github.com/benjaminhyw/rails-online-shop/pull/15)

### Day 6: Tuesday, January 17th, 2017

**Today's Progress**: More work on sessions.

**Thoughts**:  Today was a little frustrating.  Sessions is going to take me longer than I thought.


**Link(s) to work**: [Rails Online Shop Sessions](https://github.com/benjaminhyw/rails-online-shop/pull/16)

### Day 7: Wednesday, January 18th, 2017

**Today's Progress**: Inching my way through sessions..

**Thoughts**:  Okay I figured out something I couldn't yesterday so yay!  But also spent a lot of time on the road and couldn't dedicate as much time today.. it's technically yesterday's tomorrow now!  However the little bit I got done was productive.


**Link(s) to work**: [Rails Online Shop Sessions](https://github.com/benjaminhyw/rails-online-shop/pull/17)

### Day 8: Thursday, January 19th, 2017

**Today's Progress**: Close to finishing sessions, began to introduce bcrypt.

**Thoughts**:  I bit a little more than I could chew today!  I'm almost done with sessions but noticed that my user passwords weren't encrypted whatsoever.. I tried to implement bcrypt and had to stop.  I get the implementation  but the docs I have to spend a little more time to pay attention to detail.  I'll get this down tomorrow for sure, I'm feeling a little drained today.


**Link(s) to work**: [Rails Online Shop Sessions](https://github.com/benjaminhyw/rails-online-shop/pull/18)

### Day 9: Friday, January 20th, 2017

**Today's Progress**: Sessions are done!  Bcrypt is done!.

**Thoughts**:  TODAY WAS SO FRUSTRATING!!!  I spent the earlier half of my day trying and failing to get my bcrypt to work correctly.  Felt like I was going in circles, I actually decided to go restart my work and go back to my last pushed commit because I felt like I was spiraling down a path that wasn't correct.  WHO KNEW my issue had to do with generating a new migration that added to my previous user migration (rather than db:reset after making a manual change in the existing migration).

I actually looked this up yesterday, wondering which of the two was better to do.  People were mixed online.  Very strongly in favor to new migrations being generated when working on a team with people, very lax on working on solo projects.  By not generating a new migration, I kept coming across this error saying "password_digest=" not found.  I'm not sure why figuring that out took me forever, so I took a break and came back to work later at night.  SO HAPPY to say that I FIXED IT, everything works!  EVERYTHING WORKS!!! <3


**Link(s) to work**: [Rails Online Shop bcrypt](https://github.com/benjaminhyw/rails-online-shop/pull/19)