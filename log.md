# 100 Days Of Code - Log

### Day 1: July 29, 2020

**Today's Progress**: Dug into `box-shadow` and started a deep dive into CSS in general. 

**Thoughts:** My goal with 100 days of code is to become so confident with CSS that I can look at virtually any UI mockup and think "Yeah, I could make that".  So today I started with a design trend that really interests me, which is Neumorphism/Skeumorphism.  I took [these mockups](https://dribbble.com/shots/11652074-FREE-Neumorphism-UI-Kit) as inspiration.  

Tomorrow, I'll be implementing a dark theme, and (hopefully) a toggle for going back and forth between light and dark.  Optimally, I'll also clean up the CSS and introduce some variables. 

**Link to work:** [Neumorphic Profile Card](https://codepen.io/sRobDevGG/pen/ExPBPZE)

### Day 2: July 30, 2020

**Today's Progress**: Usage of `::before` and `::after` to create a slider, and programmatically changing CSS variables with JS 

**Thoughts:** Using `::before` and `::after` pseudo-elements to create a toggle out of a checkbox was weird, and not what I expected the solution to creating a toggle to be, but it worked pretty well.  Programmatically changing the CSS variables that control the background colors, box shadows, etc was also interesting and definitely illuminates how much easier frameworks make certain things (i.e. in AngularJS, I could have just thrown an ng-class on everything that looked at if the checkbox was checked or not and modified the theme accordingly).  However, this helped me in regards to JS fundamentals like getting the root element, getting arrays of elements, and manually changing styles on them.   

Tomorrow, I'm not entirely sure what I'll do.  I think I'll probably clean up this code a little bit, see if there's ways I can condense the JS side of things. After that, I'll probably find more elements to add to this page or build in this style.  Maybe I'll end up just making a full profile page?  We'll see!

**Link to work:** [Neumorphic Profile Card with Dark/Light Toggle](https://codepen.io/sRobDevGG/full/QWyXZqQ)

### Day 3: July 31, 2020

**Today's Progress**: Major refactor of CSS and JS to make theming easier

**Thoughts:** Didn't get a whole lot of progress outside of a refactor done due to having a super busy day, but thanks to [this](https://dev.to/ananyaneogi/create-a-dark-light-mode-switch-with-css-variables-34l8) tutorial, I was able to set up an actual dark theme and consolidate all the CSS into a light theme and a dark theme.  The JS also became _much_ more simple than before.

**Link to work:** [Updated Themed Neumorphic Card](https://codepen.io/sRobDevGG/pen/NWxQjGd)

### Day 4: August 1, 2020

**Today's Progress**: Started an API to interact with HLTV and gather team data.  Started an Express NodeJS API from scratch and learned the fundamentals of how to interact with MongoDB.

**Thoughts:** Will eventually build this out with a frontend as well, where users can add two teams and see a breakdown of their head to head, past results, etc, and get a prediction of the winner based on analysis of those stats.  Using [this](https://auth0.com/blog/node-js-and-express-tutorial-building-and-securing-restful-apis/) tutorial as reference.

**Link to work:** [cs-prediction-app](https://github.com/sRobDev/cs-prediction-app)

