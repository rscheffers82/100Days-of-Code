# 100 Days Of Code - Log

<!--
### Day 26: January 27th, 2017 ()

**Today's Progress:**


**Thoughts:**

**Link(s) to work:** [JSBIN - Using CSS transition property](http://jsbin.com/bopizej/1/edit?html,css,js,output)

_____________________________________________________________________
-->

### Day 26: January 27th, 2017 (On the menu today: CSS styles)

**Today's Progress:**
Today I've worked on getting the styles sorted for a react component that will allow a user to add annotations to an article. The main work I've done was creating the visual elements on the screen that use for user input eg. creating and editing annotations.

**Thoughts:**
I needed to overlay several items on top of each other using CSS. I used a combination of the below tags to get it sorted, as well as created two JS bins to try a few things out. (<i>Hot reload in react is great but still not as fast as jsbin)
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
