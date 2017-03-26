# 100 Days Of Code - Log
<!--
### Day 82: March 26th, 2017 ()

**Today's Progress:**  

**Thoughts:** 

**Link(s) to work:**
<br />[Exercise Tracker API - on Heroku](https://rs82.herokuapp.com/exercise/)
<br />[Exercise Tracker API - on GitHub](https://github.com/rscheffers82/API-microservices)
https://rs82.herokuapp.com/
_____________________________________________________________________
-->

### Day 81: March 25th, 2017 (Meteor exploration)

**Today's Progress:** Tried out the meteor framework by installing it and building a small hello world app.

**Thoughts:** I'm looking forward to start working more with Meteor and build a bigger app. The framework seems to be a great package to build full stack apps.

**Link(s) to work:**
No link as this was a simple and local hello world app
_____________________________________________________________________


### Day 80: March 24th, 2017 (Cruise Countdown - add mobile styles)

**Today's Progress:**  Added several media queries to make sure the app looks good on mobile devices too.

**Thoughts:** 

**Link(s) to work:**
<br />[Exercise Tracker API - on Heroku](https://rs82.herokuapp.com/exercise/)
<br />[Exercise Tracker API - on GitHub](https://github.com/rscheffers82/API-microservices)
https://rs82.herokuapp.com/
_____________________________________________________________________


### Day 79: March 23rd, 2017 (Cruise Countdown page is up)

**Today's Progress:** Mainly worked on the functional and visual parts of displaying the time component. I figured out that I cannot access `DOM` elements in the ComponentWillMount function. :) Stating the obvious here, but at the time it was too late to see the simple mistake. Lesson learned:
- More clarity gained regarding react's lifecycle components
- How to deploy the react-create-app boilerplate to GitHub Pages and my own FTP server.

**Thoughts:** A few smaller tweaks are needed to make sure the page displays nicely on mobile too. Probably something for tomorrow.

**Link(s) to work:**
<br />[Cruise Countdown Page](http://cruise.royscheffers.com/)
<br />[Cruise Countdown Code](https://github.com/rscheffers82/cruise-countdown-page)

_____________________________________________________________________


### Day 78: March 22nd, 2017 (Side project Cruise Countdown)

**Today's Progress:** Added some minor style updates but the majority of the time I tried to figure out how to use `moment.js` and the `moment-precise-range` plugin to provide the difference between the current date/time and when the cruise leaves.

**Thoughts:** I managed to get the difference between the times, but the app breaks as soon as I implement a `setInterval` for countdown, unsure why that's the case.

**Link(s) to work:** [Cruise Countdown Page](https://github.com/rscheffers82/cruise-countdown-page)
_____________________________________________________________________


### Day 77: March 21st, 2017 (Side project Cruise Countdown)

**Today's Progress:** Used `create-react-app` boilerplate to start a short project for two of my friends who will be going on a cruise this summer. I'm going to make a countdown page and will probably create a react countdown component that others can use in their projects if they wanted to. Today I managed to have the boilerplate working and show a static countdown timer.

**Thoughts:** I enjoyed working with the `create-react-app` boilerplate as it is fairly straight forward out of the box and their documentation is solid. 

**Link(s) to work:**
[Cruise Countdown Page](https://github.com/rscheffers82/cruise-countdown-page)
_____________________________________________________________________


### Day 76: March 20th, 2017 (Learn more about eslint)

**Today's Progress:**  Read up on `eslint` and how to use it for future projects.

**Thoughts:** Added eslint to my own personal portfolio website and the Simon and Tic Tac toe games. The lint picked up several code mistakes and I cleaned them up, more projects will follow.

**Link(s) to work:**
<br />[Portfolio website](https://github.com/rscheffers82/personal-site)
<br />[Simon game](https://github.com/rscheffers82/Simon-game)
<br />[Tic Tac Toe game](https://github.com/rscheffers82/Tic-Tac-Toe-JS-game)
_____________________________________________________________________


### Day 75: March 19th, 2017 (Optimize build process)

**Today's Progress:** Improved my build process by adding several optimizations to gulpfile.js 
`gulp-sourcemaps`
`gulp-autoprefixer`
`gulp-uglify`
`gulp-cssnano`
`gulp-imagemin`
`run-sequence`

**Thoughts:** Resources for my portfolio project files are now optimized, due to
- `autoprefixer` adds CSS prefixes are automatically added which removes the risk of manual errors.
- JS, CSS and Images are now minified and optimized with the use of `gulp-uglify` `gulp-cssnano` `gulp-imagemin`.
- No more struggle to find certain CSS rules in SASS because `sourcemaps` now adds references to the SCSS file in my browser developer tools.

**Link(s) to work:**
[Gulp build process](https://github.com/rscheffers82/personal-site/blob/master/gulpfile.js)
_____________________________________________________________________


### Day 74: March 18th, 2017 (Personal Website)

**Today's Progress:**  Implemented the zoom on hover and overlay effect in my own personal portfolio, projects area.

**Thoughts:**
- This made me better understand the structure of how to use a parent and child divs and which CSS styles to use to display the image and overlay and zoom on hover. Practice and applying what I've learned two days ago paid off today! It does still need a little more work to make it better responsive on mobile devices.

**Link(s) to work:** [royscheffers.com](http://royscheffers.com)
_____________________________________________________________________


### Day 73: March 17th, 2017 (WordPress)

**Today's Progress:** Created a services page with custom styles. This page lets any business or blogger display their services in a simple and quick to understand overview of images and a few key words.

**Thoughts:** I learned more about CSS and how to use background within a div element instead of using the `img` tag.
- With the above comes responsiveness and how to implement that. In this case I used a static width and height and used media queries to make the blocks break a certain screen sizes to show either 3, 2 or 1 element(s) in a row.

**Link(s) to work:** [WordPress development repo](https://github.com/rscheffers82/wordpress-custom-design)
_____________________________________________________________________


### Day 72: March 16th, 2017 (Zoom image on hover)

**Today's Progress:** Created a JSbin to build a zoom on hover effect.

**Thoughts:** I wanted to implement this effect in prior projects but always lacked the knowledge on how to implement it. Finally, I had time to get my head around this effect and built it in a JSbin. Can't wait to add this to future projects! Things learned:
- You can apply effect on a child element when hovering over a parent.
- A better understanding of `transform: scale()`, `overflow: hidden`, and `transition` css properties.

**Link(s) to work:** [Zoom image on hover effect](http://jsbin.com/doricib/edit?html,css,output)
_____________________________________________________________________


### Day 71: March 15th, 2017 (WordPress fixes)

**Today's Progress:** Created a trello list of the items still outstanding to fix. These tasks include:
- Add mobile styles to fix the rates page to display properly
- Style the contact page to look more subtle
- Update several images throughout the website, (better quality or less black)
- Fix some animation glitches on the Guidelines page
- Update menu navbar styles

**Thoughts:** 

**Link(s) to work:** [Black Belt Proofreader](http://blackbeltproofreader.com)
_____________________________________________________________________


### Day 70: March 14th, 2017 (API projects bundling)

**Today's Progress:** 
<br />1) Added the final layout improvements and bug fixes to Exercise Tracker and released it into the wild through social media.
<br />2) Updated the layout of all other 4 API projects to make them look more appealing. Added a menu at the top so any user can quickly switch between the various projects.
<br />3) Updated the main intro page of the API collection by adding a brief descriptions of each project and an intro image to the Exercise Tracker and URL Shortener. The collection is complete :)
<br />4) Updated my personal website by adding a back-end section to my portfolio and add the API collection, Node project.

**Thoughts:** A lot of things came to a close today and it's very rewarding to see the fruits of several weeks / months of work!

**Link(s) to work:**
<br />[API Collection - Five Node.js projects](https://rs82.herokuapp.com)
<br />[Exercise Tracker API](https://rs82.herokuapp.com/exercise)
<br />[Portfolio page - royscheffers.com](http://royscheffers.com)
_____________________________________________________________________


### Day 69: March 13th, 2017 (Exercise Tracker - display logs)

**Today's Progress:**  Continued to build on the front-end log display of the exercise app. I started to build the layout to display the data beneath the current three boxes. It will only appear once data is fetched and the logs screen is closed when the x is pressed. At that point and all data is cleared.

**Thoughts:** The app is almost ready except for a few small tweaks to tidy up the app.

**Link(s) to work:**
<br />[Exercise Tracker API - on Heroku](https://rs82.herokuapp.com/exercise/)
<br />[Exercise Tracker API - on GitHub](https://github.com/rscheffers82/API-microservices)
_____________________________________________________________________


### Day 68: March 12th, 2017 (Exercise Tracker - display logs)

**Today's Progress:** Added front-end structure and logic to display the logs. Changed the button action on the log form. Now the form is not submitted to the /log route but instead routes to a function that makes an AJAX GET call to the /log route. Currently data is being returned and errors are handled.

**Thoughts:** 

**Link(s) to work:**
<br />[Exercise Tracker API - on Heroku](https://rs82.herokuapp.com/exercise/)
<br />[Exercise Tracker API - on GitHub](https://github.com/rscheffers82/API-microservices)
_____________________________________________________________________


### Day 67: March 11th, 2017 (JS API & WordPress development)

**Today's Progress:** 
- Further improved my wife's WordPress site by optimizing the Home, Rates and Guidelines pages. I updated CSS styles to show the pages nicely for various screen sizes and added and styles some extra information to all pages.
- Worked on the Exercise Tracker API project. Fixed the GET exercise route query so all exercises are shown when no dates are selected.

**Thoughts:** 

**Link(s) to work:**
<br />[Exercise Tracker API - on Heroku](https://rs82.herokuapp.com/exercise/)
<br />[Exercise Tracker API - on GitHub](https://github.com/rscheffers82/API-microservices)
<br /> [Black Belt Proofreader](http://blackbeltproofreader.com)
_____________________________________________________________________


### Day 66: March 10th, 2017 (WordPress Blackbeltproofreader.com)

**Today's Progress:** My wife needed some help to make some changes to her website. Implemented several new images and updated the over style of her Rates and Guidelines page. We went with a much cleaner look which now places the attention better on those parts that matter.

**Thoughts:** 

**Link(s) to work:** [Black Belt Proofreader](http://blackbeltproofreader.com)
_____________________________________________________________________


### Day 65: March 9th, 2017 (WordPress final tweaks)

**Today's Progress:** Mainly styling and adding small content changes to place attention on certain parts, e.g. Subscribe to a newsletter and podcast on iTues.

**Thoughts:** 

**Link(s) to work:** [WordPress development repo](https://github.com/rscheffers82/wordpress-custom-design)
_____________________________________________________________________

### Day 64: March 8th, 2017 (WordPress development & styling)

**Today's Progress:** Adjusted `functions.php` to pull all blogposts when category podcast is being displayed.
Updated the media section to be more harmonious and elegant, it was at bit messy :-)

**Thoughts:** 

**Link(s) to work:** [WordPress development repo](https://github.com/rscheffers82/wordpress-custom-design)
_____________________________________________________________________


### Day 63: March 7th, 2017 (WordPress styling)

**Today's Progress:** Added further styles to several pages (home, blog and podcast) in order to make them mobile ready. The main work went into redoing the podcast category page; structure and layout. On the surface nothing much changed, but underneath the hood a lot did. e.g. I created a new podcast content page to have more control over what content is display and only change things for this category of posts. This also fixed a few layout bugs.

**Thoughts:** It was a rewarding coding session wherein WordPress PHP development blended in with some CSS styling.

**Link(s) to work:** [WordPress development repo](https://github.com/rscheffers82/wordpress-custom-design)
_____________________________________________________________________


### Day 62: March 6th, 2017 (WordPress styling)

**Today's Progress:** Made an initial start by adding mobile ready styles to the website. I added some initial styles for the overall layout of blogposts page and the individual blog pages.

**Thoughts:** Mainly CSS and the use of `@media` queries. Nothing hard but it takes time to get the layout right of multiple screen sizes.

**Link(s) to work:** [WordPress development repo](https://github.com/rscheffers82/wordpress-custom-design)
_____________________________________________________________________


### Day 61: March 5th, 2017 (Exercise Tracker - add initial exercise date filter)

**Today's Progress:** Gave it a first try to add the filter for exercises based on the chosen date range.

**Thoughts:** As the exercises collection is a sub-collection of users, it took me a while to figure out how to sort through this. I managed to get it working by using `.populate()` to pull in all exercises and within it adding `match: {}` to provide the date range. It is working, although the solution needs some clean-up.

**Link(s) to work:**
<br />[Exercise Tracker API - on Heroku](https://rs82.herokuapp.com/exercise/)
<br />[Exercise Tracker API - on GitHub](https://github.com/rscheffers82/API-microservices)
_____________________________________________________________________


### Day 60: March 4th, 2017 (working with WordPress)

**Today's Progress:** Worked on a personal page
- Chose a different font for the entire page, main text as well as headers
- Styled the blog area to look less busy
- Styled home to look cleaner
- Updated podcast area

**Thoughts:** Mainly styled and added content to the page. It was a nice change from coding the backend API in recent project. 

**Link(s) to work:** [WordPress development repo](https://github.com/rscheffers82/wordpress-custom-design)

_____________________________________________________________________


### Day 59: March 3rd, 2017 (Exercise Tracker bugfix)

**Today's Progress:**  Drawer menu options fixed as they weren't working anymore.

**Thoughts:** Short and sweet code session today.

**Link(s) to work:**
<br />[Exercise Tracker API - on Heroku](https://rs82.herokuapp.com/exercise/)
<br />[Exercise Tracker API - on GitHub](https://github.com/rscheffers82/API-microservices)
_____________________________________________________________________


### Day 58: March 2nd, 2017 (Exercise Tracker add backend logic)

**Today's Progress:**
- Added `POST` routes to add a user and an exercise
- Added `GET` route for requesting exercise logs
- Wrote queries for all three except for the date range parts. Saving exercises needs some more work to properly store dates. Then requesting them will be easier. 

**Thoughts:** It was a nice coding session. I really noticed how prior MongoDB projects helped to write the queries and promises with relative ease.

**Link(s) to work:**
<br />[Exercise Tracker API - on Heroku](https://rs82.herokuapp.com/exercise/)
<br />[Exercise Tracker API - on GitHub](https://github.com/rscheffers82/API-microservices)
_____________________________________________________________________


### Day 57: March 1st, 2017 (further style Exercise Tracker app)

**Today's Progress:**  Worked on the main menu and made it functional. Added the `datepicker` for when a user wants to enter a date.

**Thoughts:** Managed to deploy the app to Heroku but unfortunately something is wrong and functionality was missing. This turned out that the reference to jQuery should be `https://` instead of `http://`. Also added meta data for a card view on twitter and facebook. The UI is ready and next up will be writing the server side code that handles the API requests.

**Link(s) to work:**
<br />[Exercise Tracker API - on Heroku](https://rs82.herokuapp.com/exercise/)
<br />[Exercise Tracker API - on GitHub](https://github.com/rscheffers82/API-microservices)
<br />[Materialize CSS](http://materializecss.com)
_____________________________________________________________________


### Day 56: February 28th, 2017 (re-style Exercise Tracker app)

**Today's Progress:** Update app to Materialize CSS, the name is very similar but it's a different library. More options and better support.

**Thoughts:** Adding styles again to the app.

**Link(s) to work:** 
<br />[Exercise Tracker API - on GitHub](https://github.com/rscheffers82/API-microservices)
<br />[Materialize CSS](http://materializecss.com)
_____________________________________________________________________


### Day 55: February 27th, 2017 (Front-end development)

**Today's Progress:** 
* added eslint to the project and checked all code
* Styled the exercise UI using [MaterialCSS](http://www.material-css.com)

**Thoughts:** Loved using the MaterialCSS library to style the app. For now it looks good, although, I might make some small tweaks once the app is fully functional.

**Link(s) to work:** [Exercise Tracker API](https://github.com/rscheffers82/API-microservices)
_____________________________________________________________________


### Day 54: February 26th, 2017 (Exercise Tracker API)

**Today's Progress:** initial setup and start of the final API project from FreeCodeCamp.

**Thoughts:** I'm excited to start this new project. As it is the final API project of the [FreeCodeCamp](https://www.freecodecamp.com/rscheffers82) course (currently still in BETA). As I'm becoming more and more familiar with the setup and development process, I'm going to try and add an extra touch of design on top of this API and likely to the main intro page. For today, it kept simple and I've tied a few things together. The exercise route is setup in the router file and I've added some basic styles to the exercise intro page. This time I'll be using the [MaterialCSS](http://www.material-css.com) library to style it.

**Link(s) to work:** [Exercise Tracker API](https://github.com/rscheffers82/API-microservices)
_____________________________________________________________________


### Day 53: February 25th, 2017 (MongoDB - more advanced queries)

**Today's Progress:** Finished the Music Star App by updating the final search query as well as adding the retire and unretire queries.

**Thoughts:** These queries can become complex but it's good to know how to break them up into smaller pieces. The working app can be found at the repo below. Again special thanks to Stephen Grider for providing the initial repo [here](https://github.com/StephenGrider/UpStarMusic.git).

**Link(s) to work:** [MusicStar app](https://github.com/rscheffers82/MusicStarApp)
_____________________________________________________________________


### Day 52: February 24th, 2017 (MongoDB - more advanced queries)

**Today's Progress:** Added several advanced search queries to the Music Star App

**Thoughts:** definitely out of the comfort zone here, and it took some time to go through [mongo's documentation](https://docs.mongodb.com/manual/reference/operator/query/) and find what I need.

**Link(s) to work:** [MusicStar app](https://github.com/rscheffers82/MusicStarApp)
_____________________________________________________________________


### Day 51: February 23rd, 2017 (Add queries to the Music Star App)

**Today's Progress:** After a long day still managed to get in an hour of work on the Music Star App

**Thoughts:** Wrote both the queries for pulling the data for the age and yearsActive range selectors in the app.

**Link(s) to work:** [MusicStar app](https://github.com/rscheffers82/MusicStarApp)
_____________________________________________________________________


### Day 50: February 22nd, 2017 (Add queries to the Music Star App)

**Today's Progress:** Managed to get the app working by adding logic so that a user can create, add, search or update an artist 

**Thoughts:** OMG, I cannot believe I'm already at day 50! I should do a little recap and write, in a separate file, about the things I've learned, the pitfalls, and what I can improve. In just a nutshell, I do feel more familiar with the various technologies in the JavaScript ecosphere now that I've worked with Node.js and Express and Mongo. Which in turn helps to understand what the backend really is. So far, I really enjoyed the first 50 days, here's to the next 50.

**Link(s) to work:** [MusicStar app](https://github.com/rscheffers82/MusicStarApp)
_____________________________________________________________________


### Day 49: February 21st, 2017 (Mongo query modifiers)

**Today's Progress:** Wrapped up my first mongodb project by adding some final code that works with query modifiers like `.sort` `.skip` `.limit` 

I've also downloaded a starter repo which is a small electron app for music artists. The app is functional although no data is pulled in, no schema's are set up and no filters work yet. The next challenge will be to make the app fully functional. I'll track my progress in the repo listed below.

**Thoughts:** Short but sweet coding session today. More tomorrow...

**Link(s) to work:** 
<br />[GitHub repo](https://github.com/rscheffers82/mongodb-exploration)
<br />[MusicStar app](https://github.com/rscheffers82/MusicStarApp)
_____________________________________________________________________


### Day 48: February 20th, 2017 (Client WordPress site)

**Today's Progress:** A new website for a client wasn't showing correct navigation. Certain menu items were highlighted even though another link was clicked. These links were categories instead of pages. Initially, I thought this needed to be fixed with code in the template files. Later, I figured that some CSS would do the trick. It was a clean and simple solution, although it took a bit of time to figure it out. Stack Overflow to the rescue!

Besides that, I worked the featured blog area a little. It wasn't looking appealing, so with some styling it is looking better now.

**Thoughts:** WordPress (PHP) coding is quite different compared to JavaScript, so it took a bit of time to understand what the code was doing. Also each WP theme / template is different and in this case it was already customized. Nevertheless, it was a nice challenge.

**Link(s) to work:** [Custom design wordpress website](https://github.com/rscheffers82/wordpress-custom-design)
_____________________________________________________________________


### Day 47: February 19th, 2017 (MongoDB - model associations and middleware)

**Today's Progress:** Extended the current project to learn more about associations and middleware.

Firstly, I added the `Comment` and `BlogPost` models to the test suite. In the `User` model I link the field Blogposts to the `BlogPost` model. And within the `BlogPost` model, the comments field is linked up to the `Comment` model.<br />
Using `.populate()`, data which is linked to the user can be pulled in. Similarly, comments linked to a blogpost, can be pulled in too.

After that, I wrote some middleware to ensure any blogposts associated with a user who is removed will be removed too. <i>(e.g. when a user is banned)</i>

**Thoughts:** Leveling up with Mongo is awesome :)

**Link(s) to work:** 
<br />[GitHub repo](https://github.com/rscheffers82/mongodb-exploration)
<br />[Repo / Associations file](https://github.com/rscheffers82/mongodb-exploration/blob/master/test/associations_test.js)
_____________________________________________________________________


### Day 46: February 18th, 2017 (MongoDB)

**Today's Progress:** Looked at MongoDB, nesting subdocuments into the main model what some of the pros and cons are.

**Thoughts:** I'm starting to see that a mongoDB is quite different then a SQL DB. At the setup of an application, it seems vital to spend enough time on setting up the Models and how data will flow through the app. Looking forward to learn a more about this.

**Link(s) to work:** [GitHub repo](https://github.com/rscheffers82/mongodb-exploration)
_____________________________________________________________________


### Day 45: February 17th, 2017 (More MongoDB exploration)

**Today's Progress:** Learned more about MongoDB operators and having DB validation in a Schema

**Thoughts:** Expanded the test suite to:
- include a case when using the `$inc` operator. 
- Validate a property to exist
- Validate a property to have a certain length, name > 2 characters
- Example of catching a failed save and display the message from the Schema required field

**Link(s) to work:** [GitHub repo](https://github.com/rscheffers82/mongodb-exploration)
_____________________________________________________________________


### Day 44: February 16th, 2017 (Completed the File Metadata API challenge)

**Today's Progress:** Made a start at the next challenge, File Metadata API, things just flew and before I knew it the assignment was done.

**Thoughts:** Compared to the prior API project, this one didn't require any mongoDB configuration so setup was much quicker.
Although similar in structure, the main difference in this assignment was that the express server needed to fetch POST data instead of GET. Once that was in place, the API file catches the data on the `request` object and returns JSON data.

**Link(s) to work:** 
<br />[Live example on Heroku](https://rs82.herokuapp.com/filedata)
<br />[Code on GitHub](https://github.com/rscheffers82/API-microservices)
_____________________________________________________________________


### Day 43: February 15th, 2017 (COMPLETED: URL Shortener API :)

**Today's Progress:** Project clean-up and deployment to heroku and mlab.
- Connected the MongoDB on mLab to the app.
- Removed hard-coded URLs and set environment vars instead. This way the app will also work on Heroku without uploading sensitive information.
- Removed redundant code 

**Thoughts:** It was awesome to build this project. I'm coming to terms with coding on the backend side and can see the difference. Very pleased to see the webserver work with the mongoDB, first locally and finally all online. URLs are shortened and redirect when visiting them!

**Link(s) to work:** 
<br />[Live example on Heroku](https://rs82.herokuapp.com/shorten/)
<br />[Code on GitHub](https://github.com/rscheffers82/API-microservices)
_____________________________________________________________________


### Day 42: February 14th, 2017 (URL Shortener API)

**Today's Progress:** 
Things are started to work, longURL in, shortURL out :)

**Thoughts:** 
With the database setup, configured and a links Schema defined, I was quickly able to write some data to mongo. Once URLs were saved, using the `/shorten` route, I configured the `/short` route to catch the shortened URL, search the database for the shortcode and return the saved URL. The URL is then used to redirect the user to original website.

I only need to make sure URLs are saved with the http:// extension when it is provided in the url.

**Link(s) to work:** [URL Shortener API](https://github.com/rscheffers82/API-microservices)
_____________________________________________________________________


### Day 41: February 13th, 2017 (URL Shortener API)

**Today's Progress:** It was a long day but luckily managed to dedicate an hour to this project. Mainly setup...

**Thoughts:** 
I was unable to install mongoose-shortid as the module was having issues with dependencies. On GitHub I found [this tread](https://github.com/jjwchoy/mongoose-shortid/issues/23) which offers [another package derived from mongoose-shortid](https://github.com/leeroybrun/mongoose-shortid-nodeps) that doesn't require the bignum dependency. Installed that module and it seems to work. Next, I refined the Schema to include mongoose-shortId and connected the server to MongoDB which I'm running locally.

Today was mainly about setup, so hopefully I'll be able to write and read something from and to the DB tomorrow.

**Link(s) to work:** [URL Shortener API](https://github.com/rscheffers82/API-microservices)
_____________________________________________________________________

### Day 40: February 12th, 2017 (MongoDB and Mongoose side-project 2/2)

**Today's Progress:** Worked some more with MongoDB and Mongoose

**Thoughts:** Learned more about:
- updating records (<i>there are about 5 methods you can use</i>)
- deleting records (<i>there are about 4 methods you can use</i>)

Looking forward to implement this into the [URL shortener API project](https://github.com/rscheffers82/API-microservices) tomorrow :D

**Link(s) to work:** [GitHub repo](https://github.com/rscheffers82/mongodb-exploration)
_____________________________________________________________________



### Day 39: February 11th, 2017 (MongoDB and Mongoose side-project 1/2)

**Today's Progress:** To get more acquainted with MongoDB and Mongoose I deviated from the FreeCodeCamp course to do a little side project and brush up on database stuff.

**Thoughts:** Lovin' it! It's always nice to learn about something you need and when there's that click when it becomes familiar as well as see how you can use the new knowledge in the project you need it for. That is what happened today. Learned the following:
- connect to MongoDB using Mongoose
- Setup a Schema and Model and make it available in other files
- Create a new instance of the model e.g. a new user and save it to the collection (I love promises :)
- Search the DB using the `.find()` and `.findone()` functions available.
- NOTE: `._id` object on each entry needs `.toString()` function to be able to compare it's actual content (it's wrapped in an object and needs to be converted to a string)

**Link(s) to work:** [GitHub repo](https://github.com/rscheffers82/mongodb-exploration)
_____________________________________________________________________


### Day 38: February 10th, 2017 (URL Shortener API)

**Today's Progress:** Added some minor changes to the intro page and mainly gathered information on how to tackle this challenge. I do realise I have to study MongoDB and Mongoose a little more to establish a connection with the database. 
I also found a helpful library called [mongoose-shortid](https://www.npmjs.com/package/mongoose-shortid) which will help me to generate a unique identifier for the database which can also be re-used in the shortened URL.

**Thoughts:** I always feel lost at the beginning of a project, especially if I'm unfamiliar with the technology I'll be using. I do start to recognise it sooner and it seems to be natural. When everything is open, I can go many ways and that brings freedom but also insecurity of where to go. Next steps before I proceed with coding will be to learn more about Mongo and Mongoose. From there the rest should fall into place.

**Link(s) to work:** [URL Shortener API](https://github.com/rscheffers82/API-microservices)
_____________________________________________________________________


### Day 37: February 9th, 2017 (Annotation component)

**Today's Progress:** Created, for now, a static react component that displays one or several annotations made on a paragraph.

**Thoughts:** Created a static display component that shows one annotation. It will be re-used for each annotation made. The flow of those is managed by the annotation drawer. When an annotation is edited, it will be saved as a revision. When someone replies to an annotation, the create component will be loaded.

**Link(s) to work:** Unfortunately this project is private so I cannot share a link to this work, maybe later when the product is ready and live ;)
_____________________________________________________________________


### Day 36: February 8th, 2017 (URL Shortener API)

**Today's Progress:** Started the 3rd API project

**Thoughts:** Mainly worked on the foundation for the project to take off from. Here's the list of tasks done:
- Created an intro page for the API project that explains what the API does and how to use it.
- Added the default route `shorten` which shows the intro page
- Created the shortener route `short` which will be used to catch input and provide JSON data back
- Registered with mLab and setup a database that will be used
- Created a config file which stores login data (<i>later stored values will be used to set environment vars</i>)

**Link(s) to work:** [URL Shortener API](https://github.com/rscheffers82/API-microservices)
_____________________________________________________________________

### Day 35: February 7th, 2017 (Annotation paragraph hover mockup)

**Today's Progress:** worked on a mock up example to test functionality for a larger react app.

**Thoughts:** 
<br />An app has the following requirements:
- Initial paragraphs cannot be modified (<i>they are loaded in from an external source</i>)
- When hovering over a paragraph, annotation icons should show beside it
- When icons are clicked annotations related to that paragraph are be displayed.

I'm trying to mimic this behavior in a more simplistic way. So far I managed to display the icons on hover. Next step is to ensure a unique number is given to the icon, so when clicked the related annotation(s) are displayed. In this example a unique number will be shown. That's something for tomorrow.

**Link(s) to work:** [JSBIN - Paragraph hover, show icons](http://jsbin.com/kilajop/edit?html,css,js,output)
_____________________________________________________________________


### Day 34: February 6th, 2017 (Header Parser API)

**Today's Progress:** Finished the Header Parser API service! :D

**Thoughts:** After not having coded for 2 days due to travel, I'm back on and to my surprise found the info I needed to completed this FreeCodeCamp Challenge. For some reason I was not able to find the correct way to obtain the requesters OS system. Turns out this information is tucked away in User-Agent and can be obtained using `req.get('User-Agent')`. Once I found this on stack overflow, I was able to use a regex to extract the info and add it to the json object that is send back. Job done! Sometimes these little things can take a long time. Part of a developer's life it seems.

**Link(s) to work:** 
<br />[Header Parser API](https://github.com/rscheffers82/API-microservices)
<br />[Free Code Camp Challenge](https://www.freecodecamp.com/challenges/request-header-parser-microservice)
_____________________________________________________________________

### Day 33: February 3rd, 2017 (Header Parser API)

**Today's Progress:** Worked a bit more on the API header parser app. Deployed it to heroku and it looks like the OS sytem is read from the host instead of the client. So have to find another way of getting the client's OS. Haven't found out yet how.

**Thoughts:** Busy day so only managed to spend about an hour on this.

**Link(s) to work:** [Header Parser API](https://github.com/rscheffers82/API-microservices)
_____________________________________________________________________


### Day 32: February 2nd, 2017 (Header Parser API & RedHat's OpenShift platform)

**Today's Progress:** 
Worked for about an hour and a half on the request header API project. Currently all the information is gathered from the header either directly from the request object or with the use of the os and accepts libraries. Last thing is to display the information a bit better.
Besides that I was finally given an account on [RedHat's OpenShift platform](https://www.openshift.com). I registered and managed to deploy my first example app on their service. Pretty straight forward and awesome to see how GitHub Webhooks can be used to automatically trigger a build when a new update is pushed to the remote. As they are testing their service, only developer accounts are available for maximum a month ( for free though :) ) 

**Thoughts:** 
Little steps made again in this busy week, but nevertheless, many small steps forward make a mile :)
<br />The OpenShift platform is pretty cool. Hopefully I'll be able to test my prior server auth app there as it offers several environments e.g. NodeJS and MongoDB.

**Link(s) to work:** 
<br />[Header Parser API](https://github.com/rscheffers82/API-microservices)
<br />[First app on RedHat's OpenShift platform <i>(1 month available only)</i>](http://nodejs-mongo-persistent-testapp-on-openshift11.44fs.preview.openshiftapps.com)
_____________________________________________________________________


### Day 31: February 1st, 2017 (Header Parser API)

**Today's Progress:** Today was busy, but luckily managed to spend an hour on the next API project.

**Thoughts:** Created a new route in the API app to display the request header request details. Besides that I researched how to request user data from the request object returned from Express.js. Little progress and more resource gathering at this stage.

**Link(s) to work:** [Header Parser API](https://github.com/rscheffers82/API-microservices)
_____________________________________________________________________


### Day 30: January 31st, 2017 (React Component)

**Today's Progress:** Managed to get the small React ES6 Component to work. App.js is the parent and container component that manages state. It passes a function to component Toggle as a prop. Toggle displays two buttons that pass input back through the prop function to the parent. The parent then passes the state to the View component as a prop and displays is.

**Thoughts:** A very simple app that helped me to understand how to pass a function down as prop to child components and how they in turn return input to the parent. State in this way in managed in one component and this component can pass its data down to other child components. As simple as this exmple is, it'll be a useful reference when apps become more complex and look back on how to manage state in a container component and gather and pass it to children.

**Link(s) to work:** [React ES6 Component function to child](https://rscheffers82.github.io/ES6-component-function-to-child/)
_____________________________________________________________________


### Day 29: January 30th, 2017 (React and CSS)

**Today's Progress:** 
Wored more on my possible app drawer and tried to implement it in the main project for the client. Managed to get through 75% of the implementation and static components are created. Tomorrow I'll add the functionality.
Besides that I created a little react project to explore the React ES6 class Component. This project I want to use to learn more about how a container component can pass down a function to it's child. The child receives input, works it and passed it back to the parent through the function.

**Thoughts:** 
See above. Busy day but managed to get a lot of things done.

**Link(s) to work:** 
<br />[JSBIN - Possible App Drawer, desktop and mobile view](http://jsbin.com/muxuba/edit?html,css,output)
<br />[ES6 react Component test](https://github.com/rscheffers82/ES6-component-function-to-child)
_____________________________________________________________________


### Day 28: January 29th, 2017 (CSS flexbox and fixed positioning)

**Today's Progress:** Worked a bit on a different solution for replacing the Material UI drawer component but mimicing its behavior.

**Thoughts:** With flexbox, fixed positioning and CSS media queries I've created another mock solution to create a drawer that could be used in the annotations app. It definitely testing my understanding of flexbox. I have to sit down and work with it more often to wrap my head properly around all the available options.
One good resource I found is [Flexy Boxes](http://the-echoplex.net/flexyboxes/) which allows you to quickly layout flexboxes by setting the options for the container and child boxes.

**Link(s) to work:** [JSBIN - Possible App Drawer, desktop and mobile view](http://jsbin.com/muxuba/edit?html,css,output)
_____________________________________________________________________


### Day 27: January 28th, 2017 (Material UI - Drawer component)

**Today's Progress:** Trying to figure out if I can use the app drawer from Material UI for an app I'm developing. The app is a reader for texts and the drawer will be used to make annotations.

**Thoughts:** At this stage I managed to get the app working with the drawer but I'm unsure if I can use this component. One requirement for the project is that the annotations show up next to the text on normal to large screens. For mobile devices the annotations should display at the bottom of the screen. Until now it looks like the app drawer will only show up on the side with no easy option to move it to the bottom of the screen when the screen-size is smaller.
Unfortunately, the repo is private so I cannot share a link to my work but here's the link to the component I'm referring to and used.

**Link(s) to work:** [Material UI - Drawer](http://www.material-ui.com/#/components/drawer)
_____________________________________________________________________


### Day 26: January 27th, 2017 (On the menu today: CSS styles)

**Today's Progress:**
Today I've worked on getting the styles sorted for a react component that will allow a user to add annotations to an article. The main work I've done was creating the visual elements on the screen that use for user input eg. creating and editing annotations.

**Thoughts:**
I needed to overlay several items on top of each other using CSS. I used a combination of the below tags to get it sorted, as well as created two JS bins to try a few things out. (<i>Hot reload in react is great but still not as fast as jsbin</i>)
- flexbox
- absolute and relative positioning
- z-index
- used wildcards in CSS and JS to select multiple classes at once

**Link(s) to work:** 
<br />[JSBIN - Centering in CSS](http://jsbin.com/jaxilib/3/edit?html,css,output)
<br />[JSBIN - Wildcards in CSS and JS](http://jsbin.com/bubeco/edit?html,css,js,output)
_____________________________________________________________________


### Day 25: January 26th, 2017 (Improving CSS skills with transition and animation props)

**Today's Progress:**
In one of my projects I needed to animate certain aspects of the app, e.g. make the app drawer content appear smoothly. To get some experience with the CSS needed I created a small JS bin to experiment with this and used the article on MDN as a reference.
https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions

**Thoughts:**
Learned something new in CSS. I never really went into animating things much, although, now I see it adds something extra to the user experience.

**Link(s) to work:** [JSBIN - Using CSS transition property](http://jsbin.com/bopizej/1/edit?html,css,js,output)
_____________________________________________________________________


### Day 24: January 25th, 2017 (Node & Express project)

**Today's Progress:** Finished the timestamp microservice app today

**Thoughts:** 
- Fixed the bugs related to the date conversion. The problem lay in the order in which I made the conversion.
- Refactured the code and migrated the conversion logic to its on module (keeping only the app setup and route logic in server.js)
- Added some basic styles to the landing page
- Deployed the app to heroku
- Did my little victory dance :)

**Link(s) to work:** [Timestamp Microservice on Heroku](http://rs-timestamp-ms.herokuapp.com)
_____________________________________________________________________


### Day 23: January 24th, 2017 (Node & Express project)

**Today's Progress:** Check for valid input. When valid convert to human and unix dates

**Thoughts:** Wrestled with date conversation, human to unix and visa versa. Some helpful resources that I've used are:
- [Moment.js](http://momentjs.com/docs/#/parsing/string-format)
- [MDN Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)
- [MDN Date.parse()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/parse#Using_Date.parse())

The app converts almost all valid input to a human and unix date except for a few odd ones. eg. 3311 and human dates with st, nd or th added to the day. Will add some error checking and handling tomorrow.

**Link(s) to work:** [Timestamp Microservice](https://github.com/rscheffers82/timestamp-microservice)
_____________________________________________________________________


### Day 22: January 23rd, 2017 (Node & Express project)

**Today's Progress:** Managed to complete a few lectures on node and express on beta.freecodecamp.com which helped me along the way in my express / node project

**Thoughts:**
Learned more about express and how to use different routes and serve files and data base. I also figured out how to read user's input off the url using req.params and req.query. In the app I've added route logic as well as some basic function structure that will be used to check the input for a valid unix time stamp or a human readable date.

**Link(s) to work:** [Timestamp Microservice](https://github.com/rscheffers82/timestamp-microservice)
_____________________________________________________________________


### Day 21: January 22nd, 2017 (Node & Express project)

**Today's Progress:** Started the first backend project from FreeCodeCamp, Timestamp Microservice

**Thoughts:** Today was a fresh start in a new area for me, backend development. I've worked a little bit before with express and node.js but that was minimal. This project will be the next step to take backend development to the next level. I setup my initial files needed like index.html, server.js and README.md. Uploaded it all to GitHub and will continue with this tomorrow.

**Link(s) to work:** [Timestamp Microservice](https://github.com/rscheffers82/timestamp-microservice)
_____________________________________________________________________


### Day 20: January 21st, 2017 (React - explore test driven development)

**Today's Progress:**
Went back to the Advanced React - Redux course to finish the inner workings for the test suite section and complete the entire course! yay! :)

**Thoughts:**
Missed yesterday due to being away most of the day and coming home late at night, so continueing again today. I went over the test suite that was part of the advanced react redux course. I looked deeper into the Mocha and Chai libraries as well as react test utilities. It definitely helped me to understand where components are rendered to when running mocha from the command line as well as again an insight into the inner workings of the helper functions and the different assertions in the tests itself. This part was the last section I needed to finish before completing the course.

**Link(s) to work:** 
<br />[Front-End login app on React and Redux](https://github.com/rscheffers82/front-end-login-app)
<br />[Advanced React Redux course certificate](https://www.udemy.com/certificate/UC-43P3PBTW)
_____________________________________________________________________


### Day 19: January 19th, 2017 (Webpack with CSS Less)

**Today's Progress:**
A hard day where I tried to figure out to work out how to incorporate Less into the Isomorphic React Boiler plate.

**Thoughts:**
This boilerplate was given to me to build a new project on. I stripped out what was needed and started to implement several libraries to start working. Down the line Less files needed to be incorporated which I tried to figure out today. For some reason webpack was giving me a lot of problems. So I moved to a smaller project (listed below) and implemented it there, without too much struggle. It seems that the React Boiler plate renders code on both the server and client. (which is called Isomorphic). Called it a day as this template might be too complex to work off of for future projects and instead the stand alone single page app might be sufficient.

At least learned to:
- persist when things get tough and keep going with trying to figure out why things don't work
- extend webpack to work together with Less, fairly similar as Sass
- work with webpack and configure it to suite the project needs (still ongoing :)

**Link(s) to work:** 
[isomorphic React Boiler Plate](https://github.com/kriasoft/react-starter-kit)
[Webpack project now using CSS Less](https://github.com/rscheffers82/webpack-exploration)
_____________________________________________________________________


### Day 18: January 18th, 2017 (Did maintenance on my portfolio site)

**Today's Progress:** Minor bugfix for my portfolio site

**Thoughts:** Nothing major, updates the HTML template to load the styles correctly.

**Link(s) to work:** [Portfolio Site](http://royscheffers.com)
_____________________________________________________________________


### Day 17: January 17th, 2017 (Final finishing touch to the front-end login app)

**Today's Progress:**<br>
Managed to finish the basic functionality and display of my front-end login app. Here are the accomplishments:
- user can register
  failure handling in case incorrect input is provided or if the email address is already in use
  
- user can login
  Login details are validated on the front-end first
  - Once validated the back-end server (express, node and mongodb) is contacted to check login details there.<br>
  - If the user is registered and login details are correct, a token is returned can the '/feature' route is available to them with protected info.
  - Else an error message is returned and displayed on the login page.


- user can visit protected area when logged in
  - When not, the route will not be available for the user

**Thoughts:**<br>
Gave it an initial try to deploy the app to heroku but failed so far.
1. There are some issues with package.json
2. Have to figure out how to setup mongodb in the cloud, if a free service is available.


**Link(s) to work:** <br>
[Front-End login app on React and Redux](https://github.com/rscheffers82/front-end-login-app)<br>
[API auth server](https://github.com/rscheffers82/API-auth-server)
_____________________________________________________________________


### Day 16: January 16th, 2017 (Login App pull secure data with token in our app)

**Today's Progress:**
Managed to further build out the secure part of the application. Used the axios library to make a get request and include additional header information for authentication. The server comes back with a failure or successful response. In case of the latter the user will be provided with with the secure data.

**Thoughts:**
Nothing spectacularly new learned, just implementing the techniques that I've used before which helps to become more familair with building apps on react. A few more days to go and the app will be finished.

**Link(s) to work:** [Front-End login app on React and Redux](https://github.com/rscheffers82/front-end-login-app)
_____________________________________________________________________


### Day 15: January 15th, 2017 (Login App - connect front-end to back-end)

**Today's Progress:** Added further form validation to the signup component and on a successful form submit, data is send to the back-end server. I've also added successful and failure logic which routes the user to the feature route on success and display the failure reason when signup fails.

**Thoughts:** Studied the axios library more to better understand and how data is send back from an API request when successfull or when it failed.

**Link(s) to work:** [Front-End login app](https://github.com/rscheffers82/front-end-login-app)
_____________________________________________________________________


### Day 14: January 14th, 2017 (Build upon the login app - signup component)

**Today's Progress:** Add login component and front-end password validation

**Thoughts:** Short but sweet session for about an hour and a half today. I managed to put some code down and create the login component and use redux-form again to hook up the html elements. Front end form validation for the password is done, tomorrow email validation and hopefully tie in with the back-end for email validation and error handling.

**Link(s) to work:** [Front-End login app on React and Redux](https://github.com/rscheffers82/front-end-login-app)
_____________________________________________________________________


### Day 13: January 13th, 2017 (Further build out login app)

**Today's Progress:** I spent roughtly 3 hours on building the login and route logic for the header component of the app.

**Thoughts:** Used react-router from react and the connect component from react-redux to create a basic but functional header component. I have used both before in prior projects, so today was more of a day in where I repeated some of the concepts I learned about. I had to refer back to prior projects to check out how I did some parts again, so it was a good repeat to hopefully remember this for next time. I'm finding myself putting down a fair amount of code before needing to go back and check code. Using react and redux slowely but surely starts to feel familiar :)

**Link(s) to work:** [Front-End login app on React and Redux](https://github.com/rscheffers82/front-end-login-app)
_____________________________________________________________________


### Day 12: January 12th, 2017 (Further build upon front-end login app)

**Today's Progress:** Today I managed to setup the basic structure of the site. The React Router is now in place as well as some redux components that are needed to get the job done (e.g. redux-thunk). This will allow for a more complex action generator that dispatches different actions based on the outcome. (redux thunk provides access to the dispatch function) This in specifically useful for the login action generator that needs to handle (login failed / is successful, and the user needs to be redirected to the feature part of the app)
So far the login part is working after resolving a CORS issue on the server side. Currently a token is returned when a user logs in with an already existing email and password. I'll work on error handling and the re-route on success another time.

**Thoughts:** Although challenging, I like hooking things up as done in this project. It's awesome to see an app connect with the back and based on the outcome render output. Although this is still a basic setup, I use it to explore the concept that I'll likely will use for a later project. I still have 88 more days to go, so no sweat :)

**Link(s) to work:**<br>
[Front-End login app on React and Redux](https://github.com/rscheffers82/front-end-login-app)<br>
[API auth server (fix CORS)](https://github.com/rscheffers82/API-auth-server)
_____________________________________________________________________


### Day 11: January 11th, 2017 (Starting a new React and Redux project to explore login)

**Today's Progress:** Initial start of the project, more planning than coding and uploaded a boilerplate repo to github.

**Thoughts:** Today I spend most of the time to hash out the specifics of this project before starting to code. This little app will be build on React and Redux and it will use the prior API project I build to login. This app will have 4 different routes. "/", "/login", "/logout", "/feature". The "feature" route should only be accessible when a use has signed up and logged in. Looking forward to roll this out over the next week or so. :)

**Link(s) to work:** [Front-End login app on React and Redux](https://github.com/rscheffers82/front-end-login-app)
_____________________________________________________________________


### Day 10: January 10th, 2017 (Deep dive into JavaScript)

**Today's Progress:** Coded along with some examples in the book You Don't Know JavaScript, chapter Scope & Closures.

**Thoughts:** Glad I went back to basics. It's nice to really try to understand JavaScript well. It's one thing to put code down that works, and another to put code down that works and you understand why you choose this solution. I feel I'm moving towards the latter :) and I'm looking forward to work my way through the series.

**Link(s) to work:** [Scope and Closures - You Don't Know JavaScript](https://github.com/getify/You-Dont-Know-JS)
_____________________________________________________________________


### Day 9: January 9th, 2017 (Deployment to Heroku and AWS)

**Today's Progress:** Made the webpack project production ready and deployed it to Heroku and AWS.

**Thoughts:** Added a small node / express server to the webpack project which allows local development and production deployment to Heroku and AWS. Fun stuff and I'm looking forward to deploy more projects.

**Link(s) to work:** [Influence on Codepen](https://github.com/rscheffers82/webpack-exploration2)
_____________________________________________________________________


### Day 8: January 8th, 2017 (More webpack exploration)

**Today's Progress:**
Build another webpack project from scratch and used an existing react project to apply several optimization techniques on. Massive build process improvements! :-)

**Thoughts:**
Had quite some time on Sunday to explore webpack, performance, and process optimization again. It was really mind blowing. I definitely learned more about webpack and how modules and plugins work together. But more so the process I use to build projects has massively improved. This will surely shave off some valuable time during next development projects. More feedback on this you'll find in the [README](https://github.com/rscheffers82/webpack-exploration2/blob/master/README.md) file within the GitHub repo.

**Link(s) to work:** [More webpack exploration and build process optimization](https://github.com/rscheffers82/webpack-exploration2)
_____________________________________________________________________


### Day 7: January 7th, 2017 (Webpack exploration)

**Today's Progress:**
Managed to finish the first part of a webpack tutorial.

**Thoughts:**
Having used webpack for several React projects. I did not fully understand how to create a `webpack.config.js` file. Some code within it made sense, while other parts were like Chinese to me. Creating such a file from the group up and reading up on those parts helped to wrap my head around the various options in there. For future projects, I now know which parts to include and which to leave out.

**Link(s) to work:** [GitHub repo](https://github.com/rscheffers82/webpack-exploration)
_____________________________________________________________________


### Day 6: January 6th, 2017 (Update portfolio website)

**Today's Progress:**
Made some improvements to my portfolio website

**Thoughts:**
It was nice to fiddle around again with some CSS and make things look nice on the screen. The last few days I've worked more with code and backend stuff, so this was a nice change. I also worked on updating the description of some projects so they highlight the things I learned and which technologies I used.

**Link(s) to work:** [royscheffers.com](http://royscheffers.com)
_____________________________________________________________________


### Day 5: January 5th, 2017 (Spontaneous bug fix day)

**Today's Progress:**
Felt the need to bugfix an older app

**Thoughts:**
I've build this little app on codepen a while ago to determine which numerological day the current day adds up to. I had some bugs for certain days, so fixed those bugs and ran some tests. Thinking of adding react to the app and several views, today, monthly overview, search.

**Link(s) to work:** [Influence: a  CodePen project](http://codepen.io/roycode/pen/RKNzao)
_____________________________________________________________________


### Day 4: January 4th, 2017 (Worked on boilerplate API auth server)

**Today's Progress:**
Completed the API auth server.

**Thoughts:**
Wrestled quite a bit with passport and the setup of strategies. Luckily, I had enough time on my hands to sit down with the code and make it work. <i>#feelingsatisfied</i>

**Link(s) to work:** [API authentication server](https://github.com/rscheffers82/server-authentication)
_____________________________________________________________________


### Day 3: January 3rd, 2017 (Express and NodeJS authentication)

**Today's Progress:**
Created new repo and setup a fair chunck of the server and user authentication using Express and NodeJS

**Thoughts:**
Definitely enjoyed working with the backend and I love those moments when things start to work. Luckily I had a few hours of undisturbed coding time which helped to get my mind around some of the new concepts.

**Link(s) to work:** [API authentication server](https://github.com/rscheffers82/server-authentication)
_____________________________________________________________________


### Day 2: January 2nd, 2017 (Redux middleware)

**Today's Progress:**
Managed to code a couple of hours and explore redux middleware

**Thoughts:**
Wrapping a function into a function into a function is mind boggling but at least I understand how to tap into middleware and add it to React-redux.

**Link(s) to work:** [Redux middleware](https://github.com/rscheffers82/redux-middleware-exploration)
_____________________________________________________________________


### Day 1: January 1st, 2017 (Explore higher order components in React)

**Today's Progress:**
Created a simple component in React and added functionality to it by creating a higher order component and wrapping this around it.

**Thoughts:**
This upcoming week I want to get more familiar with React and Redux and will pick up a few projects along the way to put into practice what I'm studying.

**Link to work:** [Higher order components in React](https://github.com/rscheffers82/higher-order-components-in-react)
