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

### Day 10: Saturday, January 21st, 2017

**Today's Progress**: Added a few validations to my user model.

**Thoughts**:  I hopped on my laptop today aiming to write a few tests but ended up writing validations first.. and then wound up trying to understand how to make flash error messages display.  I was able to do so earlier when I included the flash message inside a controller method, but while writing validations I saw that there was a message: key available.  I spent the majority of my time trying to figure that out.  I wasn't able to get a whole lot done this time, because today I only had my one hour and a lot of it was spent reading and trial/error.  I'll pick back up on this tomorrow.  My goal is to get as many validations / tests done before implementing any new features to my project.


**Link(s) to work**: [Rails Online Shop User Model Validations](https://github.com/benjaminhyw/rails-online-shop/pull/20)

### Day 11: Sunday, January 22nd, 2017

**Today's Progress**: Figured out flash messages from validations.  Added validations to my item model, quick update to README.

**Thoughts**:  Today was productive!  I figured out how to display the correct validation error messages, so I did that for my user model and added some for my items.


**Link(s) to work**: [Rails Online Shop User Model Validations](https://github.com/benjaminhyw/rails-online-shop/pull/21) | [Rails Online Shop Item Model Validations](https://github.com/benjaminhyw/rails-online-shop/pull/25)

### Day 12: Monday, January 23rd, 2017

**Today's Progress**: Got some practice writing out tests!  Short and simple.. but tests nonetheless.  AND THEY PASS!!

**Thoughts**:  I dove into writing tests.  Wrote a few out.  Today was a mix of studying and writing.  I followed this [guide](https://www.railstutorial.org/book/static_pages) which was pretty insightful.  Will probably keep referencing it for future tests.  Learned about a few useful gems.  FOUND A BUG IN MY CODE.  So this is where some of my testing stops for now.. Apparently my sessions aren't being saved 100%.  They save for a few clicks and then it goes away.  Soon, there will be a test to make sure this doesn't happen!!  As well as fully functional code making sure my users stay logged in until they choose not to be :]


**Link(s) to work**: [Rails Online Shop Tests](https://github.com/benjaminhyw/rails-online-shop/pull/27)

### Day 13: Tuesday, January 24th, 2017

**Today's Progress**: Found out my sessions weren't being saved because I wasn't using cookies correctly.  Figuring that out took some time.

**Thoughts**:  Today was slightly frustrating.  I spent a good chunk of time trying to figure out what was broken in my code, only to then find out hours later that I was just missing extra steps.  Essentially all I did was fix my layout.html.erb.  I guess it's all part of the job..  Came across this gem I used sometime in the past (and had forgotten about) [Devise](https://github.com/plataformatec/devise), which is pretty cool.  I wanna get my own basic authorization stuff going, so I will work on cookies tomorrow.  I'll use Devise in future projects.  I also briefly touched on SSL .. I definitely learned a lot, but getting there took more time than I would've hoped.  Here's to a more productive tomorrow!


**Link(s) to work**: [Rails Online Shop PR 28](https://github.com/benjaminhyw/rails-online-shop/pull/28)

### Day 14: Wednesday, January 25th, 2017

**Today's Progress**: Fixed my sessions issue.  Added cookies.  Made updates when finding users/items and added conditionals to prevent users from accessing user/item :id pages they shouldn't.

**Thoughts**:  Super productive!  I asked for help yesterday on my sessions issue (they wouldn't persist) and was told to add cookies.  Added cookies then experienced the same issue.  After some digging I FOUND MY ISSUE! It had to do with my links in my application.html.erb.  My logout link was accidentally calling on the logout method because I had logout instead of logout_path.  Whoops.  After fixing it I felt good moving forward, and had a very pleasant coding day!  I'm about to tackle admin stuff, briefly touched on it today and will try and knock that out tomorrow!


**Link(s) to work**: [Rails Online Shop Cookies](https://github.com/benjaminhyw/rails-online-shop/pull/30) | [Rails Online Shop User Redirecting Conditionals](https://github.com/benjaminhyw/rails-online-shop/pull/31) | [Rails Online Shop Admin](https://github.com/benjaminhyw/rails-online-shop/pull/32)

### Day 15: Thursday, January 26th, 2017

**Today's Progress**: Began fixing things to make way for admin functionality.

**Thoughts**:  Productive day codewise but have had a day-long headache making today not so fun.  Happy to say my code works exactly the way it's supposed to right now!  I think I have to decide how I want my admin to work, so while I edited my code so it would work the way it stands both for admin/non-admin users.. I think I might have to scrap some of that and move the functionality over to a separate admin controller/views/etc.  Which is fine, shouldn't be difficult.. just kinda slightly feels like this is something I should've thought about in more detail before implementing code.


**Link(s) to work**: [Rails Online Shop Admin Conditionals](https://github.com/benjaminhyw/rails-online-shop/pull/33) | [Rails Online Shop New Admin Paths In The Making](https://github.com/benjaminhyw/rails-online-shop/pull/34)

### Day 16: Friday, January 27th, 2017

**Today's Progress**: Got all of my admin features done!

**Thoughts**:  Got all of my admin stuff done!  I refactored a little, making my code easier to read.  Added conditionals that redirected admin users to the admin page off the bat.  Also added an admin link throughout the layout that only shows up if you are an admin user.  I decided to keep my functionality where it was for the most part, realized it didn't really affect the functionality of my code other than the route names.. but conventionally I think they should be the way they currently stand (so for example, a new item should be item/new rather than admin/item/new or whatever variation).  Good productive Friday!


**Link(s) to work**: [Rails Online Shop Admin](https://github.com/benjaminhyw/rails-online-shop/pull/35)

### Day 17: Saturday, January 28th, 2017

**Today's Progress**: Updated README and played FlexboxFroggy.

**Thoughts**:  Today, I am sick :[
So, I took it easy and just updated my README file so it better reflected the current status of the project, and played [FlexboxFroggy](http://flexboxfroggy.com/)!  I will be applying styles and CSS soon so I decided to use today to brush up a little!


**Link(s) to work**: [Rails Online Shop README](https://github.com/benjaminhyw/rails-online-shop/pull/36)

### Day 18: Sunday, January 29th, 2017

**Today's Progress**: Flexbox CSS Styles!.

**Thoughts**:  I'm still sick!  So today I played with flexbox!  Implemented it in my application and added very basic placeholder styles.  The application still looks very plain, but my objects respond to location styles etc the way I want them.  I'll be adding more later, and I will definitely have to refactor my CSS styling but pretty good for today!


**Link(s) to work**: [Rails Online Shop CSS(Flexbox)](https://github.com/benjaminhyw/rails-online-shop/pull/37)