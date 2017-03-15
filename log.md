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

### Day 19: Monday, January 30th, 2017

**Today's Progress**: More CSS Styles, added an extra iteration to readme.

**Thoughts**:  Sickness coming to an end, decided to add a little more CSS styling today.  Also updated my README a little.  Today didn't feel all that productive, but I think that's mostly due to the fact that today was a lot of looking over / CSS (as opposed to new functions/controllers/models/views being added etc).  Even though my CSS looks very elementary, I'll probably move on to more functionality tomorrow.  I do want to improve my CSS styling and will do so with this project, but I think I'm prioritizing functionality at the moment.


**Link(s) to work**: [Rails Online Shop CSS Pt1](https://github.com/benjaminhyw/rails-online-shop/pull/39) | [Rails Online Shop CSS Pt2](https://github.com/benjaminhyw/rails-online-shop/pull/41) | [Rails Online Shop README](https://github.com/benjaminhyw/rails-online-shop/pull/40)

### Day 20: Tuesday, January 31st, 2017

**Today's Progress**: Made a bunch of minor fixes.  Little details.

**Thoughts**:  I thought I was going to implement more new features today but I ended up just polishing up some more.  I was mainly focusing on functionality but after adding some CSS styling to what already worked.. I just want it to look nice!  So I did these things:
  * Created a seed file for dummy data (for users and items)
  * Price displays correctly (so $10.00 instead of $10.0)
  * Added a color changing nav bar upon scrolling (jQuery)
  * Fixed nav link spacing and added new flex containers to help with future nav bar.
  * Updated README!
A bunch of little things.  Nothing new functionality wise, but looks cleaner than it did yesterday!  Definitely needs more work but I'm happy.

**Link(s) to work**: [Rails Online Shop Seed Data](https://github.com/benjaminhyw/rails-online-shop/pull/42) | [Rails Online Shop Currency Display](https://github.com/benjaminhyw/rails-online-shop/pull/43) | [Rails Online Shop jQuery (Color Changing Nav)](https://github.com/benjaminhyw/rails-online-shop/pull/45) | [Rails Online Shop Layout Nav Links](https://github.com/benjaminhyw/rails-online-shop/pull/46) | [Rails Online Shop README](https://github.com/benjaminhyw/rails-online-shop/pull/44)

### Day 21: Wednesday, February 1st, 2017

**Today's Progress**: Implemented MOST of the category features..

**Thoughts**:  I added a lot of the basics for my categories (routes, controllers, models, views, etc) and will focus on the tougher implementation details tomorrow (items displaying the categories they belong to, categories displaying all items under their category etc).  It's probably not all that tough, but will involve a little more thought.  I have some cleaning up to do, I applied some of the same CSS as items for categories for the sake of visually moving forward so I'll make those changes tomorrow as well.  I came across this weird little detail where unless I specify a width in my .individual-item{} CSS, clicking on item links (item, edit or delete) will first quickly readjust my item.. sometimes successfully redirecting me and sometimes not doing anything other than the resize until I click the link again.  It's weird, and I want to figure out why that's the case.  It might not even be an issue once I give categories their own specific CSS (instead of borrowing from Items), but still.  

**Link(s) to work**: [Rails Online Shop Categories](https://github.com/benjaminhyw/rails-online-shop/pull/47) 

### Day 22: Thursday, February 2nd, 2017

**Today's Progress**: Failed at getting the rest of my categories working.

**Thoughts**:  Today was tough!  And I think I frustrated myself to the point where I just wasn't moving productively.  Gonna try again tomorrow... Accidentally forgot to switch branches on what little work I did tho, so worked on development branch and pushed that up (so no pull request today). *sigh*.  I might just be overthinking this.  The issue I'm having trouble with.. is saving an array inside a database column.  I need to do this, because categories have multiple items and items have multiple categories.  The array is to store the product_id & item_id (which is also accidentally product_id right now.. will change that tomorrow as well).  I've gotten it to where on the console, an empty array is shown as default.. I can push items into the array fine and it sometimes it updates sometimes it doesn't.. but no matter what I can't get it to save correctly. If it can't save, it doesn't register the fact that there is content inside the array.  If there isn't anything inside the array, then my logic to loop through doesn't work. I need to get it to accept pushed items into the array, and save succesfully.  I'm ending my day .. and will try and knock this out tomorrow.  I'm a little crunched for time the next few days so I really hope I can crank this all out tomorrow. 

**Link(s) to work**: Not including one today, because there is no PR for me to link to.  I might end up writing over what I did today, so stay tuned.. 

### Day 23: Saturday, February 4th, 2017

**Today's Progress**: Fixed broken code that wouldn't save any updates to the category_id or item_id.

**Thoughts**:  I had to skip a day yesterday because I needed some personal time off.  Long day.  Today, I went back into trying to figure out why my code wouldn't save correctly.  Turns out the attr_accessors i included somehow weren't letting me save my database object, so I removed those and finally moved forward.  Figuring that out took me some time, so I didn't get to add a whole lot of new code.  After fixing it I was able to move forward and things work now!  I still have to add a way for admin users to make changes regarding categories by using the app itself and not the console.  I also have to fix my CSS and apply more specific styles accordingly.  Happy I fixed this bug today, because the rest should be relatively easy!  Will pick back up tomorrow.

**Link(s) to work**: [Rails Online Shop Categories](https://github.com/benjaminhyw/rails-online-shop/pull/48)

### Day 24: Sunday, February 5th, 2017

**Today's Progress**: Creating/editing items will accurately update category show page with individual items!

**Thoughts**:  I wrote some ugly code today.  Ugly, *working* code.. but still ugly.  I was having a hard time deleting items from category.item_id if they were updated.  This is necessary because otherwise the category display show page would still show an instance of an item object that shouldn't be there anymore.  I got it to work but it can definitely be made better.  Essentially what my current code does is delete all instances of items inside every category.item_id array.. and then pushing items inside the array again.  There should be something simpler / not as weird but I can't come up with anything else at the moment so I will refactor this later.  Otherwise, my app is looking okay.  More CSS styles need to be added, and a few other features remain (Like successful checkout, update stock quantity, etc).  I think I want to fully clean up categories and maybe update my CSS a little more.. My application is currently at a stage where it's not complete but deserves to start looking nicer :P

**Link(s) to work**: [Rails Online Shop Categories](https://github.com/benjaminhyw/rails-online-shop/pull/49)

### Day 25: Monday, February 6th, 2017

**Today's Progress**: Updated CSS, tried to refactor yesterday's logic.. updated README.

**Thoughts**:  I fixed some CSS that was starting to get a little buggy.  Categories each look a little more individual now that I don't rely on the same CSS class as individual-item.  Similar CSS, but a lot more specific to categories.  I tried to refactor yesterday's item/category update logic (so item only shows up under current category and not any previous ones) but didn't make any progress.  I definitely practiced good git workflow however, so no damage done.  I then updated my README a little.  Now, I need to make purchases.. Which means update my user so it has a cart column that can save items.. then a purchase function that creates an order (that my user should be able to look back to if they want) which will successfully update the stock quantity.  Oh, and an actionmailer.  I know there are gems that could've helped me (for mail, for authentication, etc all that) but doing these things myself are making me feel more confident in my ability to make whatever I want and have it work the way I want it to!
I think that might be it functionality wise.  Of course there will be more little things that I need to add (Like cart functionality.. have a cart page, easy mod to cart items, etc) but otherwise this is kind of it.  I feel like the project is starting to drag on a little because one hour a day minimum while jobhunting makes for little project progress..  So I'll try and spend more solid chunks of time to crank this out.. I need to add some SUPER nice CSS.  I'm happy with my flexbox implementation (and so glad I understand it now) but that's kind of as visually appealing as it gets.  It needs a wow factor.  I've also started thinking about how I want to make my personal portfolio website after this, so my mind feels like it's wandering around a bunch.  This project is a lot more back-end heavy, which is cool because it's letting me understand things I used to not understand.. and makes me wanna show just as much hard work CSS wise so .. time to get to it!  I need more front-end work here.

**Link(s) to work**: [Rails Online Shop Categories CSS](https://github.com/benjaminhyw/rails-online-shop/pull/50) | [Rails Online Shop README](https://github.com/benjaminhyw/rails-online-shop/pull/51)

### Day 26: Tuesday, February 7th, 2017

**Today's Progress**: Created an ActionMailer!  Updated README.

**Thoughts**:  My application now sends emails when a user registers for the first time successfully!  I think that's pretty cool.  Very simple generic 'welcome' email but.. it works!  I had such a hard time getting categories down 100% that I'm a little afraid of the upcoming shopping cart.  I feel like this project is near completion (as close as I can get it to right now at least).. so close yet so far!  Lots of hard work ahead of me.  I also need to add more CSS, JavaScript, more jQuery, some AJAX etc.  Here we go!

**Link(s) to work**: [Rails Online Shop Action Mailer](https://github.com/benjaminhyw/rails-online-shop/pull/52) | [Rails Online Shop README](https://github.com/benjaminhyw/rails-online-shop/pull/53)

### Day 27: Wednesday, February 8th, 2017

**Today's Progress**: FINALLY fixed my weird categorize logic!  Updated seed data to better reflect recent changes..

**Thoughts**:  I started off fixing my seed file.  Doing so made me realize that my categorize method didn't work the way I wanted it to.  Initially it wouldn't run until a new item was created, which meant just calling my categorize method inside index/wherever else needed.. Except since my logic was all wonky it kept doing all this extra work it totally didn't need to.  So I created a new branch, commented out the existing categorize code and basically started with a fresh mindset about the problem.

When I was trying to make edits previously my mind had a hard time thinking outside of the solution I already had, so I commented out that code to see if there was a different approach I could take.  There totally was, and it's a lot cleaner and doesn't do the extra unnecessary work it was previously doing.  My code day seems small today because that's all I'm pushing up today, but it required a lot of white boarding away from the computer, playing with the console etc.

Anyway, I'm super glad I knocked this out!  Implementing logic for Shopping Cart & Checkout should be somewhat similar to this .. so I'm glad I cleaned up this code before moving on to the new task!

**Link(s) to work**: [Rails Online Shop Seed](https://github.com/benjaminhyw/rails-online-shop/pull/54) | [Rails Online Shop Categorize Refactor](https://github.com/benjaminhyw/rails-online-shop/pull/55)

### Day 28: Thursday, February 9th, 2017

**Today's Progress**: Began implementing orders/shopping cart functionality!

**Thoughts**:  Today I got started on my shopping cart.  So far things makes sense, I had a little trouble with my nested routes but figured it out.  I'm currently a little stuck making my "Add To Cart" button work.  I'll pick it back up again tomorrow, hopefully finish implementing everything.

**Link(s) to work**: [Rails Online Shop Orders](https://github.com/benjaminhyw/rails-online-shop/pull/56) 

### Day 29: Friday, February 10th, 2017

**Today's Progress**: More work on cart/orders.

**Thoughts**:  I don't know why I'm stuck here but I am!  I feel like I barely chipped away today.  Hopefully tomorrow will be better.

**Link(s) to work**: [Rails Online Shop Orders](https://github.com/benjaminhyw/rails-online-shop/pull/57) 

### Day 30: Monday, February 13th, 2017

**Today's Progress**: CART/ORDERS!

**Thoughts**:  This is HARD!  I'm having such a hard time with this.  I even took the weekend off to cool down from Friday.  I couldn't get it to work!  After chipping away for hours today, I made SOME progress.. But I'm having this weird password issue that seems completely unrelated to anything!!

So I'm calling it a day and will be back tomorrow... Hopefully tomorrow makes for an easy fix!  My brain can't function anymore today.

**Link(s) to work**: [Rails Online Shop Orders](https://github.com/benjaminhyw/rails-online-shop/pull/58) 

### Day 31: Tuesday, February 14th, 2017

**Today's Progress**: My shopping cart works!  Very basic at the moment, but it works!

**Thoughts**:  I FINALLY got my shopping cart to work!  Weird, I have to look into a password_digest validation or something because my previous password validation was preventing me pushing items into my user shopping_cart array.  I removed that for the time being, and now I'm finally able to successfully update my shopping cart.
I was also having an issue with my button.  My brain forgot how to brain these past few days!  Quick and easy fix on my button (after asking for help on the slack channel).  My syntax was off and I wasn't calling my route correctly.  Instead, I was accidentally triggering my add_to_cart method as soon as the item show page loaded.
Fixed all of that, and calling it a day.  These two issues took a toll on me lol I had such a hard time!  So now that this is fixed i'll implement more minor details tomorrow.

**Link(s) to work**: [Rails Online Shop Orders](https://github.com/benjaminhyw/rails-online-shop/pull/59) 

### Day 32: Wednesday, February 15th, 2017

**Today's Progress**: More work on shopping cart.  Lots tiny details.

**Thoughts**:  My shopping cart isn't as annoying to work with anymore!  Hooray!  Today I mostly spent moving views from orders/ to cart/, so cart and order functions are kept separately.  Added basic CSS for shopping cart and also added basic logic backing up cart features (no duplicates).  Keeping today's work to a minimum, gonna start up on a python project soon so gonna spend some time studying that now!

**Link(s) to work**: [Rails Online Shop Orders](https://github.com/benjaminhyw/rails-online-shop/pull/60)

### Day 32: Friday, February 17th, 2017

**Today's Progress**: More CSS, light coding day..

**Thoughts**:  I took yesterday off from this project to work on a Python code challenge and that drained me so going back into this project I decided to take it easy.  Just fixed a couple of little things that were bothering me about the display.

**Link(s) to work**: [Rails Online Shop CSS](https://github.com/benjaminhyw/rails-online-shop/pull/61) 

### Day 33: Monday, February 20th, 2017

**Today's Progress**: Worked on more cart functionality, added more to orders functionality.

**Thoughts**:  This weekend put me in a bit of a funk so I took most of it off to just get back in touch with the world.  I needed it.

Once I came back, I was a dedicated coder.  I worked on my shopping cart some more.  Checking out is now kinda working.  KEYWORD: "kinda".  Right now, a checkout does the most basic.  It takes the shopping cart and successfully creates an order object with it.  It also clears itself out once the order is created, but not before updating the user object with this order in the user.orders array.

What it DOESN'T do .. is update stock.  I need more work on my order functionality as well.  Order index, show, etc.  So far, the index provides a clickable link that takes the user to the order/:id show page.  Great!  More on this tomorrow.  I feel good.

Oh and, I also updated the readme file early on this weekend :P

**Link(s) to work**: [Rails Online Shop Shopping Cart](https://github.com/benjaminhyw/rails-online-shop/pull/63) | [Rails Online Shop README](https://github.com/benjaminhyw/rails-online-shop/pull/62)

### Day 34: Tuesday, February 21st, 2017

**Today's Progress**: Remove item from cart finally works correctly.

**Thoughts**:  Removing items was a little harder than I thought!  But I finally got it down!

Definitely required more research today though.  I see that I've written some excessive code so I'll need to do a refactor sweep soon.  Keeping today simple, since it took so much time out today.  Will spend the rest of the day reading up on tech stuff and pick this back up again tomorrow.  I have a few tech related events coming up the next couple of weeks so I'll be a little crunched on time during then.. Hopefully still productive!

**Link(s) to work**: [Rails Online Shop Shopping Cart](https://github.com/benjaminhyw/rails-online-shop/pull/64) | [Rails Online Shop Shopping Cart Pt2.](https://github.com/benjaminhyw/rails-online-shop/pull/65)

### Day 35: Wednesday, March 8th, 2017

**Today's Progress**: Finally came back from a long break.  Started a new project, this time with emphasis on my front-end.

**Thoughts**:  I'm doing a photography portfolio website for a friend, and focusing on my front end first this time.  I'm having fun, since I usually do it the other way around and don't spend enough time on front end work.  I feel happy with what I want, but stopping because I got stuck and it's dinner time!  Here's to a quick minor reset.

**Link(s) to work**: [Rails Photography Portfolio Users](https://github.com/benjaminhyw/photography_portfolio/pull/2) | [Rails Photography Portfolio Photos](https://github.com/benjaminhyw/photography_portfolio/pull/3) | [Rails Photography Portfolio Front-End](https://github.com/benjaminhyw/photography_portfolio/pull/4)

### Day 36: Wednesday, March 9th, 2017

**Today's Progress**: Fixed my nav, added a page scroll animation effect!

**Thoughts**:  I should do my front end first more often lol.  I had fun today, just playing around with styling etc.  Managed to fix my weird nav spacing, and added this cool scroll animation when a button is clicked.  That's it, but it was tough work!  And I definitely lost track of time playing/working today.

**Link(s) to work**: [Rails Photography Portfolio Front-End](https://github.com/benjaminhyw/photography_portfolio/pull/5)

### Day 37: Thursday, March 10th, 2017

**Today's Progress**: Finished up minor animation stuff, got started on implementing a few gems for the back end!

**Thoughts**:  I finished the basics for the front-end, at least what I can do right now.  I want to have my photos working properly before touching the photo portion of my CSS because I want to make equal progress on both sides, rather than focusing too much on one and not enough on the other like I have on previous projects.

So this time after I finished up the button hover & nav color change, I went and looked for gems for my backend.

I've used both rails_admin & devise in the past.  I haven't recently, but I'm trying to give this project a more professional touch and I'm a lot more comfortable on my own rails now (I've created my own authentication & admin so, this is really just a timesaver for a clean experience).  BECAUSE I'm using gems this time tho, I spent a good chunk of time today just understanding the documentation before getting too deep into trying to make them work.  So I feel like today was minimal in progress because they felt like babysteps, but at least now I'm more familiar with how to manipulate and customize gem features to better fit my own.

Tomorrow will be spent just finishing the basics of my back-end.  The project itself doesn't seem to hard.  Each day I realize something I hadn't before, but I feel like I did a pretty good job wireframing/whiteboarding/fleshing out this project before even touching code so I'm happy, confident, and excited for the rest!

**Link(s) to work**: [Rails Photography Portfolio Front-End](https://github.com/benjaminhyw/photography_portfolio/pull/6) | [Rails Photography Portfolio Back-End(gems: devise & rails_admin)](https://github.com/benjaminhyw/photography_portfolio/pull/7)

### Day 38: Tuesday, March 14th, 2017

**Today's Progress**: Inched away at setting up custom user fields while working with Devise gem.

**Thoughts**:  I didn't get to work on this today as much as I wanted to because I had a lot of things scheduled today.  Still, I cracked Devise open and started adding custom fields that are necessary for my project to work the way I want it to.  Will try and wrap this up tomorrow.

**Link(s) to work**: [Rails Photography Portfolio Admin](https://github.com/benjaminhyw/photography_portfolio/pull/8)