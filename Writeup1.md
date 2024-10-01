## Introduction:
Spencer Smith  
16 September 2024  
Lab 1  

## Executive Summary:

In this this lab I uploaded and hosted a webpage that acts as a reminder page.  I used a mix of CSS, HTML, and JavaScript to create the webpage.  The webpage isnt yet fully functional, but I will continue to work on it in the following labs to make it functional. 

## Design Overview:

I started out by writing an HTML page that has all of the elements necessary to start out.  I then added in a CSS page that included lots of design elements.  These elements helped to enhance the pages overall appeal.  Overall the HTML and CSS pages helped to provide the backbone for my webpage.  
After this I added a JavasScript page that will help with the form submission and adding of taks onto the task list.  So far the JavaScript just sends a form using the JSON format.  I will add more to this page in later labs.  Once this was all done I hosted the webpage using github and AWS schools.  

### My Webpage
![My Webpage](./img/webpage.png)

### JSON request
![My Webpage with JSON Submission](./img/JSON.png)

### File Descriptions

* index.html - Contains the basic HTML formatting for the page
* favicon.ico - This contains a favicon image of Jennifer Lawrence
* script.js - Contains the JavaScript for the webpage
* style.css - Contains the CSS styling for the webpage
* docker-compose.yml - Is the the docker file the helps put it into a contatiner


## Questions:

### What is the purpose of using Docker containers?
The purpose of using Docker containers is so that we have a set apart speace where all of the code can run together.  The way a TA explained it to me was kind of like a VM that is a lot smaller and only has the purpose of running whats in the container
### Why is it useful to have both a development environment and a live server environment?
Becuase having two enviroments lets you edit or change one without effecting the other.  I can edit my development enviroment and if anything goes wrong it won't crash my live server.  
### What is the purpose of using a code versioning tool (i.e. Git)?
We use git because it allows for coders to ee back on changes that they have made, they can also make branches to test out progams on the code.  It allows for many people to work on code and upload it to one main branch.  
### What is the difference between a CSS rule with an element selector (i.e. h1,p,div etc.) and one with a class selector (i.e. .task, .task-done etc.)? When would you use each?
element selectors select all of the elements of that type for example h1 classes on the other hand effect everything that is marked to have the certain class. 
### What are the advantages of putting your styles in a separate .css stylesheet instead of in the <style> element of <head>?
This allows you to write CSS that can effect and change multiple pages.  You can have a uniform CSS page for your entire website instead of writeing the same code multiple times.  
### How do web browsers choose which CSS to use for an HTML element when the CSS rules contradict each other? What is the order of precedence for CSS rules?
It is whatever was last said basically.  if you link two css sheets it will be the one thats put last that will take presidence.  
### Why should you disable directory access for your server?
This helps to keep information secure.  people can't access information in the directory that could be sensitive.  


## Lessons Learned:
### Docker Problem
One of the problems that I had while doing this lab was setting up docker.  Docker is a complicated program that requires experience to work properly.  When I started this project I couldn't get Docker set up.  I spent a couple of hours on it, I eventually ended up going to one of the TAs to help me with my problem.  It ended up being that I hadn't set up the docker file correctly.  

### Margins and Formatting
Another problem that I had was getting the formatting and margins correct in the webpage.  I was trying to get the webpage to look good on a mobile screen.  I couldn't get the webpage to format correctly.  It was happening becuase I was trying to format using specific measurements instead of relative measurments that could change around depending on the size of the screen.  The solution was changing all of my measurments to be dynamic for individual screens.  

### Favicon
Favicons are small images that are on the corner of the webpage tab.  I couldn't get my favicon to load.  This was due to the fact that I hadn't done a hard refresh.  I finally figured how to due so and once I did it the favicon loaded.  
## Conclusions :

- Put Favicons on webpages
- Use CSS in all three ways of linking to HTML
- Create and use Javascript
- Create and input data into an HTML file

## References

https://www.w3schools.com/html/default.asp
https://csszengarden.com/