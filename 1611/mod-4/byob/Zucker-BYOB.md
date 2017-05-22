# BYOB Submission Form

[Project Spec](http://frontend.turing.io/projects/build-your-own-backend.html)

* Fork this repo, if you haven't already and check out a branch
* Use this README as a template to create a file in this folder with your name as the title.
* Submit a pull request
* Pro Tip: You can use [recordit.co](http://recordit.co/) to record interaction gifs.
* Secondary Pro Tip: [Here's how to link to specific line number(s) in Github](http://stackoverflow.com/questions/23821235/how-to-link-to-specific-line-number-on-github)
* Tertiary Pro Tip: You can re-use some of these things in your portfolio/resume

------

# Basics

#### Link to the Github Repository for the Project
[Your projects's repo URL](https://github.com/zkc/antiqueBox)

#### Link to the Deployed Application
[Your project's production URL](https://antiquebox-stage.herokuapp.com/)

#### Link to Your Commits in the Github Repository for the Project

-[Commits - build branch](https://github.com/zkc/antiqueBox/commits/kz-build)

## Completion

#### Were you able to complete the base functionality?

* Seeded a database with at least 2 tables and 1 relationship?
(Yes)

* Had at least 10 endpoints that returned responses with appropriate status codes?
(Yes)

* Secured at least 4 endpoints with JWTs?
(Yes) - This is the first time I've ever had the problem where my tests PASS when they definitely should not. The JWT endpoints do function properly with manual testing.

* Enforced a linter and wrote code that conformed to it?
(Yes)

* Wrote tests for both happy and sad paths for each endpoint?
(~75% of current ep)

* Setup automatic deployments with CircleCI to a production app on Heroku?
(Yes)

# Code Quality

#### Link to a specific block of your code on Github that you are proud of
[Link to code block in repo](https://github.com/zkc/antiqueBox/blob/master/server.js#L33-L56)

* Why were you proud of this piece of code?

Initially I wasn't 100% sold on my choice to separating listings from individual items. This block gave me confidence that the division was a worthwhile. I'm proud of my mapping table that links items and listings.

#### Link to a specific block of your code on Github that you feel not great about
[Link to code block in repo](https://github.com/zkc/antiqueBox/blob/master/server.js#L118)

* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

This is kind of a bug with knex, ultimately I want to reorganize this promise flow

## Testing

Attach a screenshot or paste the output from your terminal of the result of your test-suite running

<img width="533" alt="screen shot 2017-05-20 at 11 52 08 am" src="https://cloud.githubusercontent.com/assets/5368526/26278243/da8e614e-3d52-11e7-94ba-d34b1ffbc17f.png">
## Linting

Attach a screenshot or paste the output from your terminal of the result of your linter running

current lint output: 
<img width="654" alt="screen shot 2017-05-20 at 11 54 23 am" src="https://cloud.githubusercontent.com/assets/5368526/26278260/18e49e22-3d53-11e7-8638-112687cf6ee2.png">

-----

#### Please feel free to ask any other questions or make any other statements below!

Anything else you wanna say!

May 21 - Added JWT. Came across a very wierd behavior where my tests pass despite the data clearly being different. 

May 20 - Built up more remaining base requirements besides JWT. Work continues. 

May 19 - I'm obviously not done with the project as of May 19. I will be continuing to work on this as I plan on building a front end and launching this site. This plan put me into a mindset where I felt compelled to make sure I was confident in my design decisions before progressing. Ultimately this created a reduction in priority of some elements of the assignment. Additionally I've had major job stress this week that I've yet to handle well and which hindered my progress. Overall I’m ecstatic to have a functioning pipeline, now I’m in a great place to be building up significantly more this weekend.

-----

# Instructor Feedback

- Points: x / 150