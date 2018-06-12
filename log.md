# 100 Days Of Code - Log

### Day 0: May 21, 2018

**Today's Progress**: 
Currently house-sitting for two bengal kittens in Singapore
finished the amazing React web dev class from @andrew_j_mead, made some progress on my React + Node portfolio / blog app

**Thoughts:** 
Spent a good amount of time messing around with the 'wave' background effect, still not completely happy with it. Might want to try automating the opacity, reducing the number of waves, making the ovals even bigger, and anchoring the ovals further off-screen. 

I'm also not completely satisfied with the header at this moment: after the elements break down into a centered column I believe it takes up a bit too much of the screen's real estate and messes with the page flow on smaller / mobile devices. I may just break the nav / social icons into a button for modal navigation somewhat like bootstrap, but this remains to be seen.

Aside from that, I have a decent idea of how I want the portfolio to look / function. Tomorrow I'll spend some time building out the portfolio component and learning about page transition animations to solidify my portfolio flow.

**Link to work:** 
https://github.com/T-parrish/portfolio


### Day 1: May 22, 2018

**Today's Progress**: 
Worked on the portfolio some more, Fixed up some of the main page styling, added some animations, and integrated the Typist library. 

**Thoughts:** 
I spent a good deal of time trying to write a custom typewriter-esque React Component, pulling from a bunch of different examples I found on Github. After several failed attempts, I decided it would be a better use of my time to build off of a library. In the end, I chose Typist and integrated it into my homepage.

All said and done, I didn't get as much accomplished today as I had hoped. However, I did learn a good deal about some of React's limitations.

In preparation for the upcoming job hunt, I'll start to work some leetcode / hackerrank exercises into my daily programming mix. 

**Link to work:** 
https://github.com/T-parrish/portfolio

### Day 2: May 23, 2018

**Today's Progress**: 
Started studying via LeetCode, did a couple algorithms and did some work towards optimizing them / understanding why certain patters are more efficient than others. Also, feels good to brush back up on Python - really missed it with all the Javascript these days.

Put some work into the portfolio project section of my portfolio app. managed to get things up and running with some custom project cards. Styling isn't quite there yet, but it's good enough to keep moving along. Next thing I need to figure out is how to render the cards to screen responsively without the current sizing issues.

**Thoughts:** 
Good progress today. Knocked out a lot with the projects section and did some good studying for algorithms. 

**Link to work:** 
https://github.com/T-parrish/LeetCode
https://github.com/T-parrish/portfolio

### Day 3: May 24, 2018

**Today's Progress**: 
More algorithms from leetcode, feel like I'm starting to get the hang of it again. Most importantly, learned some nifty use cases and implementations for XOR gates and hash-tables.

Progress was slow on the portfolio app today, managed to create a 'carousel' of sorts for the project cards. However, I keep running into walls when it comes to animating the transitions. 

**Thoughts:** 
Trouble sleeping the night before left me feeling a bit foggy today. Progress was slow, but at least I'm having a blast just poking and prodding React; great way to learn about its limitations and effective design patterns. Working with React is a total joy so far, can't wait to figure out how to animate components dynamically.

**Link to work:** 
https://github.com/T-parrish/LeetCode
https://github.com/T-parrish/portfolio

### Day 4: May25 , 2018

**Today's Progress**: 
More algorithms, trying to learn multiple ways of solving each problem while paying attention to time / space complexity. Found a problem that I was able to brute-force, but struggling to understand the hash-table implementation. Tradeoff between time / space between the two, definitely important to understand both. Will come back to this in the future.

Finally managed to implement ReactCSSTransitions - discovered I was using the wrong library for a portion of time. (Doh!) After correctly setting it up, managed to get the animations to work... but only in one direction. Progress!

**Thoughts:** 
Good progress on algorithms, Python is coming back to me much faster than I expected. Had some trouble on a hash-table implementation for solving an an array addition problem, but I was able to write a brute-force solution quite easily. 

For React, gaining a more intuitive feel for how state and props can be manimpulated and passed around. Was really stoked to implement ReactCSSTransitionGroup, but also a bit bummed that it currently only animates to one direction. Small wins! 

**Link to work:** 
https://github.com/T-parrish/LeetCode
https://github.com/T-parrish/portfolio

### Day 5: May 26, 2018

**Today's Progress**: 
Learned how to execute functions and update state repeatedly with a specific time-frame. Used this to build a little background component out of colored tiles that randomly update color every ~500ms.

**Thoughts:** 
Learned some new tricks today, built a nifty component and learned some stuff I'll be applying to other portions of the app. Next, I want to figure out how to properly cover the background with repeating tiles by grabbing the window size before the component mounts and using that to math the height of the tiles. After that, I want to experiment with using ReactCSSTransitionGroup to add a little animation each time the tiles are updated.

**Link to work:** 
https://github.com/T-parrish/portfolio

### Day 6: May 27, 2018

**Today's Progress**: 
Really productive day, updated the boxy component to now generate boxes that fit the screen perfectly every time. Secret sauce was to grab the window size when the component mounts and push it into the component's state. After that, I divided the window height by how many rows I wanted and pushed that down into the box props for styling. Learned a good bit about component lifecycle methods during all this.

Also got started on the blog portion of the portfolio, built the scaffolding and a bare-bones form component that I plan to dial up and put behind an authenticated route so I can create blog posts and push em to a database from my own dashboard. But that's for another day.

**Thoughts:** 
Got a lot done today, which is good because I'll be heading off to Italy this coming Tuesday for a bunch of adventures. #100daysofcode is about to go into hard mode, but that just makes me want to push harder :)

**Link to work:** 
https://github.com/T-parrish/portfolio

### Day 7: May 28, 2018

**Today's Progress**: 
Started refactoring my portfolio to work with MongoDB rather than firebase. Took a little while to get my node / mongoose chops back up to speed, but things are cruising along smoothly now. First batch of blog routes ironed out before lunch, ironed out user signups before dinner, now I just have to figure out how to connect Redux to Mongo for persistent authentication.

Read up on a few different articles and it seems like there are a few ways to do it. Time to experiment!

**Thoughts:** 
Feels good to brush back up on my Node.js and Express.js. Something I've always struggled with is connecting the front end to persistent databases, so this is helping me break down what I've learned before (pure Node + Express API w/ MongoDB, React frontend w/ Node + Express on top of Firebase). Excited to put everything together!

**Link to work:** 
https://github.com/T-parrish/portfolio

### Day 8: May 29, 2018

**Today's Progress**: 
24 hours of travel later, made it to Milan. Didn't get internet until the next day, but was able to code for a couple hours on the plan ride over. Progress was slow without being able to ask questions to the internet, but still learned a couple neat things

**Thoughts:** 
Was trying to debug some errors yesterday while building out mongoose / redux authentication. Turns out, I need to run build:prod or build:dev before booting up the node server to reflect the changes I made to the front end. Got so used to dev-server handling everything for me that this definitely threw me for a loop. 

**Link to work:** 
https://github.com/T-parrish/portfolio

### Day 9: May 30, 2018

**Today's Progress**: 
Spent a good portion of today exploring Milan and recovering from the insane travel day yesterday. Managed to crank out a solid hour of algorithms from leetcode, plan to iron out Authentication for my app over this next week

**Thoughts:** 
Wasn't as productive as I had hoped, but proud that I'm still hitting at least 1 hour per day of coding with all the added travel stuff. 


**Link to work:** 
https://github.com/T-parrish/LeetCode

### Day 10: May 31, 2018

**Today's Progress**: 
Cranked out some algorithms focused on string methods from Leetcode today. Knowing that a good portion of the day would be spent driving, (Milan -> Lake Como -> Cinque Terre), I woke up extra early to squeeze in an hour and a half of coding time before heading out for the day.

**Thoughts:** 
It's tough to make progress on a project in such a limited window of time. I definitely find that spending 2-3 uninterrupted hours on a project is ideal.

**Link to work:** 
https://github.com/T-parrish/LeetCode

### Day 11: june 1, 2018

**Today's Progress**: 
Since the internet is practically useless, (can't even push to Github 😂), I've spent a bit more time on my personal portfolio and some algorithms from leetcode (Even though it takes like 5 minutes to load each one 😓). 

**Thoughts:** 
Progress is slow without stable / reliable internet, but I'm pleased with myself for waking up extra early and making sure that I can set aside between 1-2 hours for coding each morning before heading out on adventures. Once we make it back to an area with more stable internet, I'm super excited to start Brad Traversy's MERN stack class - I'm a huge fan of his free content on Youtube, and I can't wait to see what a full, paid course of his is going to be like.


**Link to work:** 
https://github.com/T-parrish/LeetCode
https://github.com/T-parrish/portfolio

### Day 12: june 2, 2018

**Today's Progress**: 
Woke up nice and early to do some more coding, internet access even more finickey than the day before. Mostly stuck with algorithms and LeetCode since I hit a roadblock on my project that requires internet access to get past.

After a nice long drive and a day of exploring Florence, we made it to our new AirBNB and finally have access to functional internet. Spending the last part of my day going through Brad Traversy's MERN stack course and using the new info to start chipping away at my portfolio roadblock.

**Thoughts:** 
Always forget how much I take internet for granted until I find myself in a remote place with a particularly nasty coding problem to solve. Something that could be solved in 10-15 minutes suddenly takes 30-45 minutes or gets put on hold until the Googs are back within reach.

**Link to work:** 
https://github.com/T-parrish/LeetCode
https://github.com/T-parrish/MERN_stack

### Day 13: june 3, 2018

**Today's Progress**: 
Learned a good deal about passport and JWT authentication today. Filled in a lot of conceptual / technological gaps for some of my other projects, but still need to figure out the best way to integrate React Router and Redux without stepping on Node / Express' toes.

**Thoughts:** 
Things are making sense much faster now, and being exposed to new technologies / libraries is helping me to identify and solve problems that would have taken forever to dissect without an internet connection. Feels good to be back.

**Link to work:** 
https://github.com/T-parrish/MERN_stack

### Day 14: june 4, 2018

**Today's Progress**: 
Spent a good deal of time fleshing out the back end for this MERN app. Things are coming togther, but I'm still curious to learn how things are going to connect with the front end. 

**Thoughts:** 
Lots of time spent on making the back end of this application robust. A bit tedious at times, but almost done with routing and validation. After that, should have more time to play around on the front end and wire things up with React + Redux.

**Link to work:** 
https://github.com/T-parrish/MERN_stack

### Day 15: june 5, 2018

**Today's Progress**: 
First day in Venice - it's everything I could have hoped for. Did a little bit of exploring, then did some work on LeetCode algorithms. Specifically, I started tackling the Linked List section - something that's always given me trouble. 

After a knocking out a couple of the Linked List problems, I went back to the MERN stack application and finished all the routes / validation for User profiles. Wrote a few routes for Posts as well, should have it ironed out shortly, then I'll be able to get started on the front end.

**Thoughts:** 
Starting to get a better feel for routing with Express, happy to have knocked out a couple of the Linked List problems. I'm interested to see practical applciations of Linked Lists in production - so far it seems like they're more useful as a theoretical concept when it comes to web development. I can see how they could be useful for low level programming languages or system design, however.

**Link to work:** 
https://github.com/T-parrish/MERN_stack
https://github.com/T-parrish/LeetCode

### Day 16: june 6, 2018

**Today's Progress**: 
Long day of photography and exploration, spent my coding time for the day trying to wrap my head around Linked List manipulation. Finally making some progress, but still really difficult for me.

**Thoughts:** 
Kinda bummed I'm having so much trouble manipulating a data structure that, on the surface, is fairly simple and straightforward. A bit worried about binary trees and other more complicated constructs... Feeling that imposter syndrome pretty hard today.

**Link to work:** 
https://github.com/T-parrish/LeetCode

### Day 17: june 7, 2018

**Today's Progress**: 
Started off the day with a photoshoot for a hotel in Venice. After that, some lunch and some coffee before diving back into Linked Lists and algorithms. I learned how to merge two sorted Linked Lists three different ways: with pointers / iterative, recursively, and by using a memory stack. Then I learned how to find out of a Linked List is a palindrome in two different ways: with a memory stack and interatively / with pointers. 

**Thoughts:** 
My understanding of the Linked List data structure is much stronger now and I feel a lot more confident than yesterday. I was planning to get more work done on Node / React this evening, but we wound up having a 3 hour dinner. That, and considering a few healthy pours of wine we had to celebrate our photography / marketing gig this morning, I do not presently feel capable of putting any meaningful effor into coding for the time being. I will have to pick things back up in the morning 😁

**Link to work:** 
https://github.com/T-parrish/LeetCode

### Day 18: june 8, 2018

**Today's Progress**: 
Finished the Node back end for my MERN test app. Went back to refactor a couple of the routes and optimize a couple others. Tested myself for retention on the Linked List stuff I've been learning, managed to reproduce solutions in ~10 mins rather than 1-2 hours.

**Thoughts:** 
Repetition is key. Been having a lot more success with algorithms since I started drilling for at least ~1 hour per day. Stepping away from stuff I've been working on for a couple days has also been super helpful in gaining perspective. For example, after coming back to the Node portion of my MERN test app after a couple days of nothing but algorithms, everything started clicking almost immediately. 

**Link to work:** 
https://github.com/T-parrish/MERN_stack
https://github.com/T-parrish/LeetCode

### Day 19: june 9, 2018

**Today's Progress**: 
Slow day, made a lot of progress on music projects but didn't accomplish much on the coding front. Did manage to squeeze out the last Linked List problem from LeetCode and start with Binary trees... going to be fun.

**Thoughts:** 
Bummed that the place we're staying has questionable internet again. Makes progress a whole lot slower.


**Link to work:** 
https://github.com/T-parrish/LeetCode

### Day 20: june 10, 2018

**Today's Progress**: 
Internet is still in shambles. Made a bit of progress on my MERN app today: completed a couple of components and rigged them up to communicate with the back end via Axios. Learned some interesting things about using the axios api vs the fetch api, and also some interesting tidbits with dynamic classNames.


**Thoughts:** 
Things are starting to come together with the front end and back end, once I figure out how the login tokens can be wrangled with application state via redux, I'll be ready to take the next steps with my personal portfolio.


**Link to work:** 
https://github.com/T-parrish/MERN_stack

### Day 21: june 11, 2018

**Today's Progress**: 
Long day of travel today. Did some algorithm work / review before kicking things off. Made it to Prague in time for dinner a couple beers. Winding down the day by configuring Redux and wiring up some reducers.


**Thoughts:** 
Czech beer is cheaper than water, and I'm staying in an AirBnb that was built during a time when America was still a British colony. What a trip.

**Link to work:** 
https://github.com/T-parrish/MERN_stack
https://github.com/T-parrish/LeetCode

### Day 21: june 11, 2018

**Today's Progress**: 
Drilled some algorithms earlier this morning before heading out to explore Prague with Chris who got in this morning at 8am from Iceland. did some hiking, got some lunch, took a ton of pictures. Did some work on the reducers + action generators for the MERN app. Some things are starting to make more sense.


**Thoughts:** 
Feeling a bit sluggish today, not super productive. Made some good strides with the app and my algorithm drills, but it seems like progress is taking me longer than usual.

**Link to work:** 
https://github.com/T-parrish/MERN_stack