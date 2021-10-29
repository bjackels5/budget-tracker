# ProjectName
This challenge for Module X of the Coding Bootcamp is to ...

* [User Story](#userStory)

* [Requirements](#requirements)

* [Technologies Used](#techUsed)

* [What I Learned](#whatILearned)

* [ProjectName Screenshot](#webImage)

* [Sample Generated Webpage](#sampleOutput)

* [ProjectName Demo](#projectDemo)

* [ProjectName URL](#projectURL)

* [Contact Me](#contactMe)


---

<a id="userStory"></a>
## User Story

User Story
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 

--- 

<a id="requirements"></a>
## Requirements

GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated

Once you’ve updated the existing budget tracker, it should provide the following functionality:

The ability to enter deposits offline.

The ability to enter expenses offline.

Offline entries should be added to the tracker when the application is brought back online.
Web Manifest
Because this will be a mobile-first application, you’ll also need to add a web manifest to your application with the app’s metadata, to let users’ devices know what they’re installing and how the app should look on the home screen.

This manifest.json file for this project will contain the following properties:

name

short_name

icons

theme_color

background_color

start_url

display

IMPORTANT
In the module project, you used webpack to create the manifest.json file. For this application, you’ll need to create it manually and add it to the root of the public/ directory of your application. You can also review Module 19: Progressive Web Applications (PWA), Lesson 5: Convert the App to a PWA as a refresher on web manifests.

Deployment to Heroku Using MongoDB Atlas
Finally, the budget tracker has a server and uses MongoDB as its database, so you’ll need to deploy this application to Heroku using MongoDB Atlas. To review this process, look at Module 18: NoSQL, Lesson 5: Add Mongoose Validation, specifically 18.5.5: Deploy to Heroku.

---

<a id="techUsed"></a>
## Technologies Used

--- 

<a id="whatILearned"></a>
## What I Learned

---

<a id="webImage"></a>
## ProjectName Screenshot

![ProjectName](./media/project-name.png)

---

<a id="sampleOutput"></a>

<a href="./dist/sampleOutputFile">Sample ProjectName Output</a>

---

## ProjectName Demo

<a id="projectDemo"></a>

<a href="https://youtu.be/TRyEJ-cYpcg">
   <img src="./media/ProjectName-demo.png">
</a>

---

<a id="projectURL"></a>
## ProjectName URL
[ProjectName URL](https://bjackels5.github.io/ProjectName/)

---

---

<a id="contactMe"></a>
## Contact Me
You can reach me, Brenda Jackels, at bjackels5@gmail.com.






What You Will Learn
I've learned that while previous modules had a few errors here and there, this Module is a dumpster fire.

By completing this module, you'll learn how to do the following:

Identify performance bottlenecks in web applications.

Explain how performance can be measured in web applications.

Explain the five main categories measured in a Lighthouse audit.

Optimize CSS, JavaScript, and media assets for performance.

Set up webpack in a new front-end project.

Use service workers to cache assets for offline functionality.

Convert an existing web application to a PWA.

How to use a manifest.json in our projects, and how that will work along with a service worker to make our app a PWA.

How to link a manifest to the HTML to let the browser know the app is a PWA.

How to use webpack to dynamically create a manifest.json based on configurations provided in webpack.config.js.

How to add properties to the manifest.json so the user can add the PWA to the home screen of their mobile device.

Measured performance metrics for a website using Chrome DevTool's Lighthouse app.

Performed audits to expose performance flaws which are especially critical when dealing with slower mobile devices on sluggish networks.

Learned how to use an automated build tool like webpack to bundle assets through a dependency graph to optimize performance by lazy loading and minification.

Used service workers to cache the websites assets for offline functionality.

Offered installable icons for quick access to our app using PWAs.